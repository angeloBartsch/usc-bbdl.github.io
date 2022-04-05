---
layout: page
title: Test Publications
permalink: /testpubs/
menu: main2
---

<div>
<button onclick="window.location.href='../publications/';">Publications</button>
<button onclick="window.location.href='../fulllengthpeerreviewedabstracts/';">Full-Length Peer-Reviewed Abstracts</button>
<button onclick="window.location.href='../peerreviewedabstracts/';">Peer-Reviewed Abstracts</button>
<button onclick="window.location.href='../abstracts/';">Abstracts</button>
<button onclick="window.location.href='../bookchpt/';">Book Chapters</button>
<button onclick="window.location.href='../invitedsymposia/';">Invited Symposia</button>
<button onclick="window.location.href='../dissertation_theses/';">Dissertations & Theses</button>
</div>

<script src="../publication_tags.js"></script>
<br>
<h3>Years</h3>
<link rel="stylesheet" type="text/css" media="screen" href="../css/styles.css" />
<div>
<div class="yearbuttons">
{% for year_of_interest in (1997..2022) reversed %}
  <a class="year_button_container" href="#{{year_of_interest}}">
    <button class="year_button">{{year_of_interest}}</button>
  </a>
  {% endfor %}
</div>
<br>
<h3>Topics</h3>

<button onclick="showAll()">Show All</button>
<button onclick="showOnly('.neuroscience')">Neuroscience</button>
<button onclick="showOnly('.computation_and_modeling')">Computation and Modeling</button>
<button onclick="showOnly('.robotics')">Robotics</button>
<button onclick="showOnly('.clinical_research')">Clinical Research</button>
<button onclick="showOnly('.biomechanics')">Biomechanics</button>
<button onclick="showOnly('.manipulation')">Manipulation</button>
<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>
</div>

<!-- make sure the max date is the current year! -->
{% for year_of_interest in (1997..2022) reversed %}

  {% comment %} casting an integer to a string {% endcomment %}
  {% assign yearAsString = year_of_interest | append:"" %}
  <div class='year_header_container'>
  <large_year id="{{year_of_interest}}">{{year_of_interest}}</large_year>
  <div>

  {% comment %} filtering datas {% endcomment %}
  {% assign selectedEntries = site.data.publications | where: "Year", yearAsString %}
    {% for paper in selectedEntries %}
             <div class="publication_card {{paper.Tags}}" >
             <div class="paper_author_container">
               {{paper.Author}} <a class="article_title" href="../../{{paper.Link}}"
               target="_blank"
               title="{{paper.Abstract}}">{{paper.Title}}</a> <i>{{paper.Journal}}</i>, {{paper.Year}} <br>
             </div>
             </div>
     {% endfor %}
 {% endfor %}

 
 <!-- scroll to top button -->

 <script>
 // When the user scrolls down 20px from the top of the document, show the button
 window.onscroll = function() {scrollFunction()};

 function scrollFunction() {
     if (document.body.scrollTop > 400 || document.documentElement.scrollTop > 20) {
         document.getElementById("myBtn").style.display = "block";
     } else {
         document.getElementById("myBtn").style.display = "none";
     }
 }

 // When the user clicks on the button, scroll to the top of the document
 function topFunction() {
     document.body.scrollTop = 0; // For Chrome, Safari and Opera
     document.documentElement.scrollTop = 0; // For IE and Firefox
 }
 </script>
 <!-- scroll to top button -->