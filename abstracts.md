---
layout: page
title: Abstracts
permalink: /abstracts/
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

<head>
  <style>
#myBtn {
    display: none; /* Hidden by default */
    position: fixed; /* Fixed/sticky position */
    bottom: 20px; /* Place the button at the bottom of the page */
    right: 30px; /* Place the button 30px from the right */
    z-index: 99; /* Make sure it does not overlap */
    border: none; /* Remove borders */
    outline: none; /* Remove outline */
    background-color: #9b4343; /* Set a background color */
    color: white; /* Text color */
    cursor: pointer; /* Add a mouse pointer on hover */
    padding: 15px; /* Some padding */
    border-radius: 10px; /* Rounded corners */
}

#myBtn:hover {
    background-color: #555; /* Add a dark-grey background on hover */
}
    
  </style>
</head>
<body>
<br>
  
<h1 style="font-size:40px;">Years</h1>

<div>
<button onclick="window.location.href='#2022';">2022</button>
<button onclick="window.location.href='#2018';">2018</button>
<button onclick="window.location.href='#2017';">2017</button>
<button onclick="window.location.href='#2016';">2016</button>
<button onclick="window.location.href='#2014';">2014</button>
<button onclick="window.location.href='#2013';">2013</button>
<button onclick="window.location.href='#2010';">2010</button>
<button onclick="window.location.href='#2009';">2009</button>
<button onclick="window.location.href='#2003';">2003</button>
<button onclick="window.location.href='#2002';">2002</button>
<button onclick="window.location.href='#1998';">1998</button>
<button onclick="window.location.href='#1996';">1996</button>
</div>

<!--
<br>
<b><a href="" title="">
""</a></b><br>
<br>
  
<br> -->

<br>
  
<h1 style="font-size:40px;" id="2022">2022</h1>

Niyo G, Almofeez LI, Woo J, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/2022_SFN_Almofeez_Voluntary_movement_in_the_presence_of_muscle_afferentation.pdf" title="Multiple computational models of neuromuscular control include cortico-spinal drive as the primary (or only) command signal to a muscle. However, actual α-motoneuron activation results from summation of excitatory and inhibitory descending, propriospinal, sensory and proprioceptive synaptic inputs. Muscle spindles provide homologous and heteronomous proprioceptive inputs encoding muscle fiber length and velocity, while γ-motoneurons can modulate these spindle outputs, the extent to which the spindle feedback inputs alters limb kinematics is unknown. Here we model the functional effects of excitatory spindle afferent signals on limb kinematics to quantify whether and how the open loop descending cortico-spinal drive to α-motoneurons needs to be adjusted to counterbalance spindle afferent signals. Similar to (Hagen and Valero-Cuevas 2017), we used a 31-muscle Macaque arm model in MuJoCo and generated 100 open loop α-motoneuron commands that produced random free arm movements lasting 2 seconds starting from rest. We then systematically added excitatory monosynaptic spindle afferent to each muscle. We compared the baseline motion to the resulting disrupted trajectories and endpoint location after using five incremental feedback gains, proportional to the lengthening and eccentric velocity of each muscle. As expected, movements inducing greater fiber lengthening and eccentric velocities tended to be more disrupted as gain increased. But these trajectory and endpoint disruption were neither linear nor necessarily kinematically significant. Our findings highlight that each arm movement must have a distinct, nonlinear compensatory interaction between α and γ motoneuron drives, which can range from subtle to strong. Moreover, our conceptual approach to computational neuromuscular control and learning should be broadened to encompass dynamic muscle afferentation.">
"How is voluntary movement disrupted in the presence of muscle afferentation?"</a></b><br>
Proceedings of the 51st Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2022<br>

<br>

Bartsch-Jimenez A, Erwin A, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/2022_SFN_Bartsch_Prediction_of_task_progress.pdf" title="Dimensionality reduction techniques are often applied to electromyographic (EMG) recordings to calculate basis functions that quantify muscle coordination strategies. Usually, muscle synergies are defined using these dimensionality reduction techniques from the basis functions that account for 90% of variance in the original signal. However, the residual activity (remaining 10%) is not entirely random and can inform the execution of motor tasks. To test the importance of residual activity to capture the fine features of upper-arm cyclical motion, we compared the task progress prediction error based on (i) EMG activity and (ii) after its dimensionality reduction.">
"Muscle synergy residuals are necessary for accurate prediction of task progress"</a></b><br>
Proceedings of the 51st Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2022<br>

<br>
  
Chakravarthi Raja S, Fannelle T, Lao JE, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/2022_SFN_Chakravarthi Raja_Abstract.pdf" title="It is still unknown in detail to what extent and in what way spinally-mediated sensorimotor mechanisms contribute to natural voluntary movement. Specifically, there is a need to disambiguate the functional contribution of descending alpha (α) and gamma (γdynamic, γstatic) cortico-spinal projections from propriospinal, sensory, and proprioceptive projections. As an extension of our neuromorphic computational  approach in Jalaledini et al. (2017), Niu et al. (2017) and Nagamori et al. (2021), we actuated a tendon-driven single-joint robotic finger using motors programmed to act in real-time as an agonist-antagonist pair of Hill-Type muscles. In addition to modeling spiking neurons (Izhikevich, 2003), muscle spindles (Mileusnic et al., 2006) and Golgi tendon organs (Mileusnic and Loeb, 2006), their stretch reflex pathways were also innervated by descending α, γdynamic, and γstatic drives. The α drive (in pulses per second, pps) was set to produce slow sinusoidal or point-to-point movements on the robotic finger's joint. By sweeping across  various values of amplitude and relative phase of the γdynamic and γstatic drives to the two muscles, we were able to quantify the effect of these various α-γ interactions on joint kinematics. 'Realism of movement' was quantified using three metrics: 1. magnitude of voluntary movement, measured in degrees; 2. deviation from minimum jerk to measure smoothness; and 3. two-thirds power law to compare movements with varying parameters. We saw that only a particular, typically phase-advanced family of γ drive profiles enables greater sinusoidal joint movements. Also, careful scheduling of γ drives during the ramp and hold phases is crucial to accurately start and stop point-to-point movement. Our results highlight that only certain families of task-specific amplitudes and phases of γ drives are sufficient (yet not necessary) to produceic motor action. This warrants further study in human neuromorphic models to validate the nuanced role of descending α-γ cortico-spinal commands in enabling spinal circuits to produce natural voluntary movement.">
"Only certain phase relationships of alpha-gamma coordination facilitate voluntary movement"</a></b><br>
Proceedings of the 51st Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2022<br>

<br>
  
Erwin A, Bartsch-Jimenez A, Azadjou MH, Almofeez LI, Niyo G, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/2022_SFN_Erwin_Effect_of_age_on_coherence.pdf" title="Synchronous activity between electromyography (EMG) signals at high frequencies (>7 Hz), i.e., intermuscular coherence, is thought to reveal shared neural input to muscles.  As such it may be able to quantify ‘synergies of neural origin’.  As an essential step towards clinical utility of intermuscular coherence in neurorehabilitation, we extended Laine et al. (J Physiol, 2021) and contrasted alpha-band neural drive strength between four neurotypical young adults (23–29 years) and four neurotypical older adults (51–58 years—within the age range in the population of stroke survivors). Using their right arm, participants rotated an ergometer while surface EMG was measured from seven muscles including the upper trapezius, triceps (lateral head), biceps (short and long heads), and deltoid (anterior, middle, posterior). EMG data were high-pass filtered using a fourth-order Butterworth filter with a cutoff frequency of 250 Hz and then the signals were rectified. Magnitude squared coherence was estimated across all muscle pairs (21 comparisons), and a mean coherence per participant was estimated as the mean of the maximum coherence in the alpha-band (8-16 Hz) per muscle pair. A corresponding grand mean was estimated for each group (young adults vs. older adults). These preliminary data show that the averagecoherence per participant for young adults vs. older adults was 0.0262 (    0.0068) vs. 0.0363 (    0.0195), which were not statistically different (p = 0.14). Each group mean was significantly above the coherence threshold of 0.006. This preliminary study of the previously unexplored age-dependent nature of coherence during cyclical reaching movements suggests that aging does not affect mean coherence across all muscles and phases of the cycle. These preliminary results encourage further study of this lack of age-dependent coherence up to 58 years of age, and beyond. If this result is further validated, it would provide a rigorous biomarker baseline against which to compare motor impairment in adults after neurological injuries, suchas stroke.">
"Effects of age on intermuscular coherence in a cyclical upper-extremity motor task"</a></b><br>
Proceedings of the 51st Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2022<br>

<br>
  
Fanelle T, Urbina-Meléndez D, Chakravarthi Raja S, Marjaninejad A, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/2022_SFN_Fanelle_QuadrupedLocomotion.pdf" title="The ability to take a known skill and adapt it to a novel task is fundamental to lifelong learning (Kudithipudi et al., 2022). Here we show in hardware that the knowledge a quadruped gains by babbling and refining movement in-air is beneficial to further learning when transitioning from movement in-air to on-ground(Marjaninejad, Urbina-Mel´endez, et al., 2019b; Marjaninejad, 2021). The quadruped creates an implicit model of its own kinematics by undergoing five minutes of motor babbling and training an artificial neural network (ANN) to produce the inverse kinematics through usage of the General-to-Particular (G2P) autonomous learning algorithm (Marjaninejad, Urbina-Mel´endez, et al., 2019a; Sun et al., 2019). By feeding a set of desired kinematics into this ANN we produce a set of motor activations that the model predicts will result in those kinematics; the error between desired and actual kinematics obtained from the activations can then be used to refine the model with a few-shot learning approach.">
"The Translation of In-Air Movement to On-Ground Locomotion of a Tendon-Driven Quadruped Through Adaptive Learning"</a></b><br>
Proceedings of the 51st Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2022<br>

<br>
  
<h1 style="font-size:40px;" id="2018">2018</h1>

Cohn BA, Marjaninejad A, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/cohn_sfn_2018.pdf" title="Vertebrate systems operate limbs with many more muscles than degrees of freedom, which creates redundancies for isometric force production. Optimization is usually proposed as the means by which the nervous system solves such underdetermined problem. However, the learning and execution problem can also be approached from the geometric perspective of heuristic or systematic exploration of high-dimensional spaces, and exploitation of feasible regions found and remembered. We apply such approach to assess the learnability of the input-tension to output fingertip force mapping for the seven tendons of a human cadaver index finger. We applied five thousand different 7-dimensional tension vectors, while simultaneously recording the resulting isometric fingertip force outputs. We analyzed the relationship between the input and output in both the forward and inverse directions using. a linear regression model, an Artificial Neural Network, and a data-driven Nearest-Neighbor lookup table. We find that forward models perform more accurately than inverse models and that the Nearest-Neighbor approach has a notable fit error at the edges of the input space. These results open a new front for a thorough understanding of how the actual physics of an anatomical system (i.e., the plant the brain must contend with) fundamentally affects learning, memory, and performance of motor function in health, disease, and in an evolutionary context. Figure 1: A parallel coordinate plot of 5000 muscle tension patterns implemented on a human cadaver finger highlights how sparsely the edges of the input space are explored with uniform sampling.">
"Evaluating the learnability-dimensionality relationship in a tendon-driven finger"</a></b><br>
Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018<br>

<br>

Hagen DA, Laine CM, Chakravarthi Raja S, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/hagen_sfn_2018.pdf" title="Deciding how to move the hand along a given path to produce activities for daily living (ADLs) involves multiple factors such as limb kinetics, choice of muscle activation patterns, online error corrections, robustness to perturbations, accounting for length/velocity muscle mechanics and time-sensitive reflex modulation. In Hagen & Valero-Cuevas (2017) we show how the joint rotations associated with different paths induce different musculotendon (MT) velocities. While different paths will naturally produce different MT velocities, we found that similar paths can exhibit different MT velocity profiles. This matters at the level of individual muscles because differences in MT velocities will require unique muscle activation strategies to compensate for force-length/force-velocity properties and modulation of their spinal reflex mechanisms. Importantly, these differences in MT velocities within and across paths establish the neuromechanical landscape that determines the robustness of muscle coordination patterns and reflex modulation strategies during ADLs.Here we study how initial variability in the direction of a hand path affects the subsequent time histories of MT velocities. As in our prior work, we used an 18 muscle, 2 joint planar arm model to produce 100 random reaching paths for 6 different pairs of points on a tabletop (3 pairs shared the starting position, 3 pairs shared the ending location). Each valid, smooth reaching path was generated (and its MT velocities found) using a pseudo-random clamped cubic spline, parameterized to follow a bell-shaped tangential velocity curve, simulating reaching movements of 35 cm in length with initial errors compatible with those seen in reaching studies in humans.We find that uniform initial error (i.e., variability) across paths induces non-uniform distributions of MT velocities. That is, although the induced MT velocities follow a similar profile for each reaching movement, their distributions/deviations change across them. This implies that some reaching paths may be more or less forgiving to initial errors in muscle coordination or reflex modulation. This has important consequences to the study of healthy movement, as well as the rehabilitation of movement for ADLs in neurological conditions and stroke.">
"Small errors in movement paths can induce dramatic changes in musculotendon velocities"</a></b><br>
Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018<br>

<br>
  
Nagamori A, Laine CM, Loeb GE, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/Akira_Nagamori_SfN_2018_Abstract.pdf" title="Involuntary force variability is an inherent property of motor behavior. When exacerbated, it is a key contributor to performance errors and a feature of several neurological conditions. Some propose that involuntary force variability arises primarily through the conversion of motoneuron firing patterns into muscle force, i.e. “motor noise.” This mechanism has been tested using a model of recruitment and rate coding developed by Fuglevand et al. (1993). However, this model has several drawbacks that limit its ability to simulate force variability. First, it does not explicitly model the fusion of force twitches with increases in firing rate and concomitant saturation of calcium binding to troponin. Second, the model lacks a series elastic element (i.e., tendon), which damps out the effects of fluctuations of motoneurone firing by changing its length and, thereby, the velocity of the muscle fibers in an externally isometric system. We addressed these limitations by combining some elements of the Fuglevand model with physiological and mechanical features from a model by Song et al. (2008). This new model has improved predictions of force and force variability. Upon close inspection, we show the amplitude and spectral features of force variability are significantly influenced by the viscoelastic properties of musculotendons. This model of motor units produces a lower amplitude of force variability than previous models. Also, spectral features of this new model resemble more closely what has been observed experimentally. These results question current thinking attributing the majority of involuntary force variability to peripheral motor noise, and highlight the importance of closed-loop behavior including afferent feedback and error corrections.">
"Can Motor Noise Account for Force Variability?"</a></b><br>
Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018<br>
  
<br>
  
Chakravarthi Raja S, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/2018_SCRaja_SfNAbstract.pdf" title="In Niu, et al. (2017) we implemented a realtime Field-Programmable Gate Array  (FPGA)-based simulation of neuromorphic models of monosynaptic stretch reflex circuitry of an agonist-antagonist muscle-pair. We then characterized the system in Jalaleddini, et al. (2017) by coupling the simulation to the flexor digitorum profundus and the extensor carpi radialis longus tendons of the MCP joint of a cadaveric hand preparation to show that such systems can indeed evoke human-like stretch reflexes as in the work of Edin and Vallbo (1990). We now present improvements to that system such as including Golgi tendon organs, Renshaw cells, and polysynaptic interneuronal pathways to form a system akin to a simplified spinal-like regulator as in Raphael et al. (2010). Nonlinear adaptive controls and simple neural networks allow us tune the descending commands (pulse trains) to both fusimotor and alpha motoneuron pools. We use such time-based running of descending commands to demonstrate the ability to produce “voluntary” movement. We find that realistic models of muscle mechanics, force-velocity properties in particular, are critical to produce stable movements. By selectively adding/removing components and interconnections, we are also able to show the sufficiency of the same for enabling voluntary movement. Future extensions will include homonymous and heteronymous sensorimotor pathways to control more muscles and produce motor function in cadaveric human fingers.">
"An integrative neuromorphic approach to modeling of voluntary motor function."</a></b><br>
Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018<br>
  
<br>

Nagamori A, Laine CM, Valero-Cuevas FJ<br>
<b><a href="../Abstracts/AN_NCM_Abstract_2018.pdf" title="Accurate and precise movement executions are confronted with variability associated with generation of muscle force. Such variability arises from various sources including mechanical properties of muscles and limbs, motor unit properties, proprioceptive feedback, and descending neural commands. Previously, contributions of individual sources have been studied in isolation and in a feedforward manner. However, those factors interact during closed-loop control, which describes nearly all experimental paradigms in which muscle force must be voluntarily controlled. Recently, we showed using a closed-loop simulation of an afferented muscle that neuromechanical interactions among neural noise, mechanical properties of musculotendon unit, proprioceptive feedback and error corrective mechanism suffice to explain cardinal features of involuntary force variability previously observed experimentally. Here, we attempt to extend this observation by incorporating new elements in our model. New elements added to our existing model include stochastic motor unit firing patterns, conversion of neural firing into muscle force, and additional spinal feedback pathways within and across muscles (pathway involved with monosynaptic Ia excitatory feedback, Ia inhibitory interneurons, Ib interneurons, Renshaw inhibitory interneurons, propriospinal interneurons,). Our results show that motor unit properties are important, yet are typically insufficient to explain the majority of force variability or its frequency spectrum. Importantly, we demonstrate previously an unrecognized influence of coordinated activities between two muscles on the amplitude and spectral features of force variability. These results highlight potential importance of such neuromechanical interactions in understanding the generation of force variability in precise and accurate motor tasks and explaining physiological mechanisms of altered neuromuscular control in health and diseases.">
"A computational model of afferented muscles reproduces cardinal features of force variability"</a></b><br>
Proceedings of the 28th Annual Meeting of the Society for the Neural Control of Movement, Santa Fe, New Mexico, USA, May 2018<br>

<br>
<h1 style="font-size:40px;" id="2017">2017</h1>

Cohn BA, Jalaleddini K, Valero-Cuevas FJ<br>
<b><a href="../Papers/cohn_jalaleddini_valerocuevas_asb_2017.pdf" title="There exist analytical formulations for the transmission of muscle force to endpoint force in tendon-driven limbs, and how it changes nonlinearly with posture [1]. However, how this information is encoded by the nervous system to control limbs remains unknown. The neuroscience literature proposes neural control based both on deterministic (e.g., internal models, optimal control, synergies, etc) and probabilistic (e.g., Bayesian) models of limb physics and environment. To evaluate the neuromechanical advantages of probabilistic control, we characterized the statistical structure of the transmission of muscle forces for multiple postures of a tendon-driven mechanical finger.">
"Neuromechanical implications of postural changes to motor learning and performance"</a></b><br>
Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017<br>
  
<br>

Jalaleddini K, Nagamori A, Laine CM, Golkar MA, Kearney RE, Valero-Cuevas FJ<br>
<b><a href="../Papers/ASB2017_Poster_Kian.pdf" title="">
"Evidence That Tuning of Muscle Spindles Can Be Decoupled from Muscle Activation"</a></b><br>
Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017<br>
  
<br>

Marjaninejad A, Taherian B, Jalaleddini K, and Valero-Cuevas FJ<br>
<b><a href="../Papers/Ko2016Dynamic.pdf" title="">
"Simple and Two-Element Hill-Type Muscle Models Cannot Replicate Realistic Muscle Stiffness"</a></b><br>
Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017<br>
  
<br>

Nagamori A, Laine CM, Jalaleddini K, Valero-Cuevas FJ<br>
<b><a href="../Papers/ASB_2017_nagamori.pdf" title="">
"Interactions between Tendon Stiffness and Spindle Afferent Feedback Determine the Magnitude of Involuntary Force Variability"</a></b><br>
Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017<br>
  
<br>
  
Laine CM, Valero-Cuevas FJ<br>
<b><a href="../Papers/CML_FJVC_ASB_2017.pdf" title="">
"Specific Manual Tasks Transform EMG into a Probe for Neural Dysfunction in Parkinson’s Disease"</a></b><br>
Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017<br>

<br>
<h1 style="font-size:40px;" id="2016">2016</h1>

Ko N, Laine CM, Fisher BE, Valero-Cuevas FJ<br>
<b><a href="../Papers/Ko2016Dynamic.pdf" title="">
"Dynamic fingertip force variability in individuals with Parkinsons disease"</a></b><br>
Hand Rehabilitation Section, American Physical Therapy Association Combined Sections Meeting, Anaheim, CA, Feb 17-20, 2016<br>

<br>
<h1 style="font-size:40px;" id="2014">2014</h1>

Lawrence EL, Nagamori A, Valero-Cuevas FJ, Finley JM<br>
<b>"Prolonged immobilization and unloading leads to profound and long-lasting changes in spinal excitability."</b><br>
Proceedings of the 44th Annual Meeting of the Society for Neuroscience, Washington DC, November 15-19, 2014<br>

<br>
<h1 style="font-size:40px;" id="2013">2013</h1>

Lawrence EL, Lyle MA, Werner I, Krenn O, Lorenzi D, Kernbeiss S, Gondolatsch B, Frontull V, Zarfl M, Posch M, Valero-Cuevas FJ<br>
<b>"Participation in elite sports improves neuromuscular control as detected by the Lower Extremity Strength-Dexterity Test"</b><br>
Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013<br>
  
<br> 

Ko N*, Lawrence EL*, Dayanidhi S*, Hu W, DiConti A, Lerner J, Winstein CW, Requejo P, Fisher B, Valero-Cuevas FJ<br>
<b>"The Strength-Dexterity test can detect differences in dynamic control of fingertip forces between individuals with Parkinson's disease and non-disabled older adults"</b><br>
Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013<br>
*denotes equal contribution<br>
  
<br>             
     
Rocamora JM, Niu CM, Buchli J, Sanger TD, Valero-Cuevas FJ<br>
<b>"Physiologically-based control of a robotic tendon-driven system"</b><br>
Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013<br>
  
<br> 


Babikian S, Kanso E, Valero-Cuevas FJ<br>
<b>"Pre-tensioning of musculotendons is necessary to achieve finger postures and slow finger motions"</b><br>
Proceedings of the 43rd annual meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013<br>
  
<br>    


Reyes A, Lawrence EL, Babikian S, Liu CY, Heck CN, Valero-Cuevas FJ<br>
<b>"Spectral activity of cortical activity during manipulation of unstable objects revels task-dependent spatiotemporal features"</b><br>
Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013<br>
  
<br>   
<h1 style="font-size:40px;" id="2010">2010</h1>

Kurse MU, Schmidt M, Lipson H, Valero-Cuevas FJ<br>
<b><a href="https://usc-bbdl.github.io/Papers/Kurse2010mathematical.pdf" title="">
"Extracting mathematical models defining index finger kinematics using symbolic regression"</a></b><br>
Proceedings of the 14th Annual Fred S. Grodins Graduate Research Symposium, Los Angeles, CA, April 10th, 2010<br>
  
<br> 

Kurse MU, Valero-Cuevas FJ, Lipson H<br>
<b>"Estimating the Topology of the Extensor Mechanism of the Human Finger"</b><br>
Proceedings of the 12th Annual Fred S. Grodins Graduate Research Symposium, Los Angeles, CA, April 5th, 2010<br>
  
<br> 

R&aacute;cz, K, Valero-Cuevas FJ<br>
<b>"Motion and force are not controlled independently in multi-finger manipulation tasks"</b><br>
40th Annual Meeting of the Society for Neuroscience, San Diego, CA, 2010<br>
  
<br> 

Kutch JJ, Kurse MU, Valero-Cuevas FJ<br>
<b><a href="https://usc-bbdl.github.io/Papers/Kutch2010Muscle.pdf" title="">
"Muscle redundancy does not imply robustness to muscle dysfunction"</a></b><br>
40th Annual Meeting of the Society for Neuroscience, San Diego CA, November 2010<br>
  
<br> 

Kutch JJ, Valero-Cuevas FJ<br>
<b>"Obtaining complete solution sets for neuromuscular models"</b><br>
ASME 2010 Summer Bioengineering Conference, Naples, FL, June 2010<br>

<br> 

R&aacute;cz, K, Inouye J, Valero-Cuevas FJ<br>
<b><a href="https://usc-bbdl.github.io/Papers/Kornelius2010spatio.pdf" title="">
"The spatio-temporal structure of force variability in static grasp suggests a continually active neural controller"</a></b><br>
Summer Bioengineering Conference of the American Society of Mechanical Engineers, Naples, FL, 2010<br>

<br>
<h1 style="font-size:40px;" id="2009">2009</h1>

Kutch JJ, Kurse MU, Hoffmann H, Kuo AD, Valero-Cuevas FJ<br>
<b>"Muscle synergies may be artifacts of biomechanics rather than neural constraints, and are not necessary to simplify control"</b><br>
39th Annual Meeting of the Society for Neuroscience, Chicago IL, October 2009<br>

<br>
<h1 style="font-size:40px;" id="2003">2003</h1>

Kuxhaus LC, Valero-Cuevas FJ, and Roach SS<br>
<b>"Effect of simulated low ulnar nerve palsy on the 3D force production capabilities of the thumb"</b><br>
Upstate Medical University Alumni Day, Syracuse University, Syracuse, NY, 2003<br>
  
<br> 

Santos VJ and Valero-Cuevas FJ<br>
<b><a href="https://usc-bbdl.github.io/Papers/Santos2003Stochastic.PDF" title="">
"Stochastic analysis of anatomical data suggests three characteristic types of thumb kinematics"</a></b><br>
Proceedings of the American Society of Mechanical Engineers Summer Bioengineering Conference, Key Biscayne, FL. 2003<br>
  
<br> 

Venkadesan M, Valero-Cuevas FJ, Guckenheimer JM<br>
<b><a href="https://usc-bbdl.github.io/Papers/Venkadesan2003dynamic.pdf" title="">
"The dynamic sensorimotor regulation of fingertip force vectors is independent of hand strength"</a></b><br>
33th Annual Meeting of the Society for Neuroscience. New Orleans, LA, 2003<br>

<br>
<h1 style="font-size:40px;" id="2002">2002</h1>

Valero-Cuevas FJ, Venkadesan, M, Talati, A Hirsch J<br>
<b>"How networks of cortical activity adapt in response to changes in the type and quality of sensory input during dynamic precision pinch"</b><br>
32th Annual Meeting of the Society for Neuroscience. Orlando, FL, 2002<br>

<br>
<h1 style="font-size:40px;" id="1998">1998</h1>

Valero-Cuevas FJ, Burgar CG, Johanson ME, Zajac FE<br>
<b>"Scaling of muscle activation patterns during generation of isometric fingertip forces"</b><br>
28th Annual Meeting of the Society for Neuroscience. Los Angeles, CA, 1998<br>

<br>
<h1 style="font-size:40px;" id="1996">1996</h1>

Valero-Cuevas FJ, Burgar C, Zajac FE, Hentz VR, McGill KC, An KN<br>
<b>"Muscle coordination during maximal index-finger ad-abduction forces"</b><br>
Abstracts V. I, 26th Annual Meeting of the Society for Neuroscience, Washington, DC., 1996<br>

<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>
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
</body>
<!-- scroll to top button -->

<!--
<head>
  <style>
    th
    {
      border-bottom: 1px solid #d6d6d6;
    }
    tr:nth-child(even)
    {
      background:#e9e9e9;
    }
  </style>
</head>

<body>

<div data-role="page" id="pageone">
  <div data-role="header">
    <h1>Abstracts</h1>
  </div>

  <div data-role="main" class="ui-content">

    <table data-role="table" data-mode="columntoggle" class="ui-responsive ui-shadow" id="myTable" data-filter="true" data-input="#filterTable-input">
      <thead>
        <tr>
          <th>Citation</th>
          <th data-priority="1">PDF</th>
          <th data-priority="2">Supplemental Materials</th>
          <th data-priority="3">Year</th>
        </tr>
      </thead>

      <tbody>


      <tr title="Vertebrate systems operate limbs with many more muscles than degrees of freedom, which creates redundancies for isometric force production. Optimization is usually proposed as the means by which the nervous system solves such underdetermined problem. However, the learning and execution problem can also be approached from the geometric perspective of heuristic or systematic exploration of high-dimensional spaces, and exploitation of feasible regions found and remembered. We apply such approach to assess the learnability of the input-tension to output fingertip force mapping for the seven tendons of a human cadaver index finger. We applied five thousand different 7-dimensional tension vectors, while simultaneously recording the resulting isometric fingertip force outputs. We analyzed the relationship between the input and output in both the forward and inverse directions using. a linear regression model, an Artificial Neural Network, and a data-driven Nearest-Neighbor lookup table. We find that forward models perform more accurately than inverse models and that the Nearest-Neighbor approach has a notable fit error at the edges of the input space. These results open a new front for a thorough understanding of how the actual physics of an anatomical system (i.e., the plant the brain must contend with) fundamentally affects learning, memory, and performance of motor function in health, disease, and in an evolutionary context. Figure 1: A parallel coordinate plot of 5000 muscle tension patterns implemented on a human cadaver finger highlights how sparsely the edges of the input space are explored with uniform sampling.">
        <td>Cohn BA, Marjaninejad A, Valero-Cuevas FJ<br>
            <b>"Evaluating the learnability-dimensionality relationship in a tendon-driven finger"</b> <br>
            Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018</td>
        <td><a href="../Abstracts/cohn_sfn_2018.pdf">Link</a></td>
        <td></td>
        <td>2018</td>
      </tr>


      <tr title="Deciding how to move the hand along a given path to produce activities for daily living (ADLs) involves multiple factors such as limb kinetics, choice of muscle activation patterns, online error corrections, robustness to perturbations, accounting for length/velocity muscle mechanics and time-sensitive reflex modulation. In Hagen & Valero-Cuevas (2017) we show how the joint rotations associated with different paths induce different musculotendon (MT) velocities. While different paths will naturally produce different MT velocities, we found that similar paths can exhibit different MT velocity profiles. This matters at the level of individual muscles because differences in MT velocities will require unique muscle activation strategies to compensate for force-length/force-velocity properties and modulation of their spinal reflex mechanisms. Importantly, these differences in MT velocities within and across paths establish the neuromechanical landscape that determines the robustness of muscle coordination patterns and reflex modulation strategies during ADLs.Here we study how initial variability in the direction of a hand path affects the subsequent time histories of MT velocities. As in our prior work, we used an 18 muscle, 2 joint planar arm model to produce 100 random reaching paths for 6 different pairs of points on a tabletop (3 pairs shared the starting position, 3 pairs shared the ending location). Each valid, smooth reaching path was generated (and its MT velocities found) using a pseudo-random clamped cubic spline, parameterized to follow a bell-shaped tangential velocity curve, simulating reaching movements of 35 cm in length with initial errors compatible with those seen in reaching studies in humans.We find that uniform initial error (i.e., variability) across paths induces non-uniform distributions of MT velocities. That is, although the induced MT velocities follow a similar profile for each reaching movement, their distributions/deviations change across them. This implies that some reaching paths may be more or less forgiving to initial errors in muscle coordination or reflex modulation. This has important consequences to the study of healthy movement, as well as the rehabilitation of movement for ADLs in neurological conditions and stroke.">
        <td>Hagen DA, Laine CM, Chakravarthi Raja S, Valero-Cuevas FJ<br>
            <b>"Small errors in movement paths can induce dramatic changes in musculotendon velocities"</b> <br>
            Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018</td>
        <td><a href="../Abstracts/hagen_sfn_2018.pdf">Link</a></td>
        <td></td>
        <td>2018</td>
      </tr>

      <tr title="Involuntary force variability is an inherent property of motor behavior. When exacerbated, it is a key contributor to performance errors and a feature of several neurological conditions. Some propose that involuntary force variability arises primarily through the conversion of motoneuron firing patterns into muscle force, i.e. “motor noise.” This mechanism has been tested using a model of recruitment and rate coding developed by Fuglevand et al. (1993). However, this model has several drawbacks that limit its ability to simulate force variability. First, it does not explicitly model the fusion of force twitches with increases in firing rate and concomitant saturation of calcium binding to troponin. Second, the model lacks a series elastic element (i.e., tendon), which damps out the effects of fluctuations of motoneurone firing by changing its length and, thereby, the velocity of the muscle fibers in an externally isometric system. We addressed these limitations by combining some elements of the Fuglevand model with physiological and mechanical features from a model by Song et al. (2008). This new model has improved predictions of force and force variability. Upon close inspection, we show the amplitude and spectral features of force variability are significantly influenced by the viscoelastic properties of musculotendons. This model of motor units produces a lower amplitude of force variability than previous models. Also, spectral features of this new model resemble more closely what has been observed experimentally. These results question current thinking attributing the majority of involuntary force variability to peripheral motor noise, and highlight the importance of closed-loop behavior including afferent feedback and error corrections.">
        <td>Nagamori A, Laine CM, Loeb GE, Valero-Cuevas FJ<br>
            <b>"Can Motor Noise Account for Force Variability?"</b> <br>
            Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018</td>
        <td><a href="../Abstracts/Akira_Nagamori_SfN_2018_Abstract.pdf">Link</a></td>
        <td></td>
        <td>2018</td>
      </tr>


      <tr title="In Niu, et al. (2017) we implemented a realtime Field-Programmable Gate Array  (FPGA)-based simulation of neuromorphic models of monosynaptic stretch reflex circuitry of an agonist-antagonist muscle-pair. We then characterized the system in Jalaleddini, et al. (2017) by coupling the simulation to the flexor digitorum profundus and the extensor carpi radialis longus tendons of the MCP joint of a cadaveric hand preparation to show that such systems can indeed evoke human-like stretch reflexes as in the work of Edin and Vallbo (1990). We now present improvements to that system such as including Golgi tendon organs, Renshaw cells, and polysynaptic interneuronal pathways to form a system akin to a simplified spinal-like regulator as in Raphael et al. (2010). Nonlinear adaptive controls and simple neural networks allow us tune the descending commands (pulse trains) to both fusimotor and alpha motoneuron pools. We use such time-based running of descending commands to demonstrate the ability to produce “voluntary” movement. We find that realistic models of muscle mechanics, force-velocity properties in particular, are critical to produce stable movements. By selectively adding/removing components and interconnections, we are also able to show the sufficiency of the same for enabling voluntary movement. Future extensions will include homonymous and heteronymous sensorimotor pathways to control more muscles and produce motor function in cadaveric human fingers.">
        <td>Chakravarthi Raja S, Valero-Cuevas FJ.<br>
            <b>"An integrative neuromorphic approach to modeling of voluntary motor function."</b> <br>
            Proceedings of the 48th Annual Meeting of the Society for Neuroscience, San Diego, CA, USA, Nov 2018</td>
        <td><a href="../Abstracts/2018_SCRaja_SfNAbstract.pdf">Link</a></td>
        <td></td>
        <td>2018</td>
      </tr>


      <tr>
        <td>Nagamori A, Laine CM, Valero-Cuevas FJ<br>
            <b>"A computational model of afferented muscles reproduces cardinal features of force variability"</b> <br>
            Proceedings of the 28th Annual Meeting of the Society for the Neural Control of Movement, Santa Fe, New Mexico, USA, May 2018</td>
        <td><a href="../Abstracts/AN_NCM_Abstract_2018.pdf">Link</a></td>
        <td></td>
        <td>2018</td>
      </tr>


      <tr>
        <td>Cohn BA, Jalaleddini K, Valero-Cuevas FJ <br>
            <b>"Neuromechanical implications of postural changes to motor learning and performance"</b> <br>
            Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017.</td>
        <td><a href="../Papers/cohn_jalaleddini_valerocuevas_asb_2017.pdf">Link</a></td>
        <td></td>
        <td>2017</td>
      </tr>


      <tr>
        <td>Jalaleddini K, Nagamori A, Laine CM, Golkar MA, Kearney RE, Valero-Cuevas FJ<br>
            <b>"Evidence That Tuning of Muscle Spindles Can Be Decoupled from Muscle Activation"</b> <br>
            Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017.</td>
        <td><a href="../Papers/ASB2017_Poster_Kian.pdf">Link</a></td>
        <td></td>
        <td>2017</td>
      </tr>


      <tr>
        <td> Marjaninejad A, Taherian B, Jalaleddini K, and Valero-Cuevas FJ <br>
            <b>"Simple and Two-Element Hill-Type Muscle Models Cannot Replicate Realistic Muscle Stiffness"</b> <br>
            Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017.</td>
        <td><a href="../Papers/Ko2016Dynamic.pdf">Link</a></td>
        <td></td>
        <td>2017</td>
      </tr>

      <tr>
        <td>Nagamori A, Laine CM, Jalaleddini K, Valero-Cuevas FJ<br>
            <b>"Interactions between Tendon Stiffness and Spindle Afferent Feedback Determine the Magnitude of Involuntary Force Variability"</b> <br>
            Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017.</td>
        <td><a href="../Papers/ASB_2017_nagamori.pdf">Link</a></td>
        <td></td>
        <td>2017</td>
      </tr>

      <tr>
        <td>Laine CM, Valero-Cuevas FJ<br>
            <b>"Specific Manual Tasks Transform EMG into a Probe for Neural Dysfunction in Parkinson’s Disease"</b> <br>
            Proceedings of the 41st Annual Meeting of the American Society of Biomechanics, Boulder, CO. Aug 8-11, 2017.</td>
        <td><a href="../Papers/CML_FJVC_ASB_2017.pdf">Link</a></td>
        <td></td>
        <td>2017</td>
      </tr>

        <tr>
          <td>Ko N, Laine CM, Fisher BE, Valero-Cuevas FJ. <br>
              <b>"Dynamic fingertip force variability in individuals with Parkinsons disease."</b> <br>
              Hand Rehabilitation Section, American Physical Therapy Association Combined Sections Meeting, Anaheim, CA, Feb 17-20, 2016.</td>
          <td><a href="../Papers/Ko2016Dynamic.pdf">Link</a></td>
          <td></td>
          <td>2016</td>
        </tr>

        <tr>
          <td>Lawrence EL, Nagamori A, Valero-Cuevas FJ, Finley JM.<br>
              <b>"Prolonged immobilization and unloading leads to profound and long-lasting changes in spinal excitability."</b> <br>
              Proceedings of the 44th Annual Meeting of the Society for Neuroscience, Washington DC, November 15-19, 2014.</td>
          <td></td>
          <td></td>
          <td>2014</td>
        </tr>

        <tr>
          <td>Lawrence EL, Lyle MA, Werner I, Krenn O, Lorenzi D, Kernbeiss S, Gondolatsch B, Frontull V, Zarfl M, Posch M, Valero-Cuevas FJ. <br>
              <b>"Participation in elite sports improves neuromuscular control as detected by the Lower Extremity Strength-Dexterity Test."</b> <br>
              Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013.</td>
          <td></td>
          <td></td>
          <td>2013</td>
        </tr>

        <tr>
          <td>Ko N*, Lawrence EL*, Dayanidhi S*, Hu W, DiConti A, Lerner J, Winstein CW, Requejo P, Fisher B, Valero-Cuevas FJ. <br>
              <b>"The Strength-Dexterity test can detect differences in dynamic control of fingertip forces between individuals with Parkinson's disease and non-disabled older adults."</b> <br>
              Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013. *denotes equal contribution</td>
          <td></td>
          <td></td>
          <td>2013</td>
        </tr>

        <tr>
          <td>Rocamora JM, Niu CM, Buchli J, Sanger TD, Valero-Cuevas FJ. <br>
              <b>"Physiologically-based control of a robotic tendon-driven system."</b> <br>
              Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013.</td>
          <td></td>
          <td></td>
          <td>2013</td>
        </tr>

        <tr>
          <td>Babikian S, Kanso E, Valero-Cuevas FJ. <br>
              <b>"Pre-tensioning of musculotendons is necessary to achieve finger postures and slow finger motions."</b> <br>
              Proceedings of the 43rd annual meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013.</td>
          <td></td>
          <td></td>
          <td>2013</td>
        </tr>

        <tr>
          <td>Reyes A, Lawrence EL, Babikian S, Liu CY, Heck CN, Valero-Cuevas FJ. <br>
              <b>"Spectral activity of cortical activity during manipulation of unstable objects revels task-dependent spatiotemporal features."</b> <br>
              Proceedings of the 43rd Annual Meeting of the Society for Neuroscience, San Diego, CA, November 9-13, 2013.</td>
          <td></td>
          <td></td>
          <td>2013</td>
        </tr>

        <tr>
          <td>Kurse MU, Schmidt M, Lipson H, Valero-Cuevas FJ. <br>
              <b>Extracting mathematical models defining index finger kinematics using symbolic regression.</b> <br>
              Proceedings of the 14th Annual Fred S. Grodins Graduate Research Symposium, Los Angeles, CA, April 10th, 2010. </td>
          <td><a href="https://usc-bbdl.github.io/Papers/Kurse2010mathematical.pdf">Link</a></td>
          <td></td>
          <td>2010</td>
        </tr>

        <tr>
          <td>Kurse MU, Valero-Cuevas FJ., Lipson H. <br>
              <b>Estimating the Topology of the Extensor Mechanism of the Human Finger.</b> <br>
              Proceedings of the 12th Annual Fred S. Grodins Graduate Research Symposium, Los Angeles, CA, April 5th, 2010. </td>
          <td></td>
          <td></td>
          <td>2010</td>
        </tr>

        <tr>
          <td>R&aacute;cz, K, Valero-Cuevas FJ.<br>
              <b>"Motion and force are not controlled independently in multi-finger manipulation tasks."</b> <br>
              40th Annual Meeting of the Society for Neuroscience, San Diego, CA, 2010.</td>
          <td></td>
          <td></td>
          <td>2010</td>
        </tr>

        <tr>
          <td>Kutch JJ, Kurse MU, Valero-Cuevas FJ <br>
              <b>"Muscle redundancy does not imply robustness to muscle dysfunction"</b> <br>
              40th Annual Meeting of the Society for Neuroscience, San Diego CA, November 2010.</td>
          <td><a href="https://usc-bbdl.github.io/Papers/Kutch2010Muscle.pdf">Link</a></td>
          <td></td>
          <td>2010</td>
        </tr>

        <tr>
          <td>Kutch JJ, Valero-Cuevas FJ <br>
              <b>"Obtaining complete solution sets for neuromuscular models"</b> <br>
              ASME 2010 Summer Bioengineering Conference, Naples, FL, June 2010.</td>
          <td></td>
          <td></td>
          <td>2010</td>
        </tr>

        <tr>
          <td>Kutch JJ, Kurse MU, Hoffmann H, Kuo AD, Valero-Cuevas FJ. <br>
              <b>"Muscle synergies may be artifacts of biomechanics rather than neural constraints, and are not necessary to simplify control"</b> <br>
              39th Annual Meeting of the Society for Neuroscience, Chicago IL, October 2009.</td>
          <td></td>
          <td></td>
          <td>2009</td>
        </tr>

        <tr>
          <td>R&aacute;cz, K, Inouye J, Valero-Cuevas FJ. <br>
              <b>"The spatio-temporal structure of force variability in static grasp suggests a continually active neural controller."</b> <br>
              Summer Bioengineering Conference of the American Society of Mechanical Engineers, Naples, FL, 2010.</td>
          <td><a href="https://usc-bbdl.github.io/Papers/Kornelius2010spatio.pdf">Link</a></td>
          <td></td>
          <td>2010</td>
        </tr>

        <tr>
          <td>Kuxhaus LC, Valero-Cuevas FJ, and Roach SS. <br>
              <b>Effect of simulated low ulnar nerve palsy on the 3D force production capabilities of the thumb.</b> <br>
              Upstate Medical University Alumni Day, Syracuse University, Syracuse, NY, 2003.</td>
          <td></td>
          <td></td>
          <td>2003</td>
        </tr>

        <tr>
          <td>Santos VJ and Valero-Cuevas FJ. <br>
              <b>Stochastic analysis of anatomical data suggests three characteristic types of thumb kinematics. </b> <br>
              Proceedings of the American Society of Mechanical Engineers Summer Bioengineering Conference, Key Biscayne, FL. 2003.</td>
          <td><a href="https://usc-bbdl.github.io/Papers/Santos2003Stochastic.PDF">Link</a></td>
          <td></td>
          <td>2003</td>
        </tr>

        <tr>
          <td>Venkadesan M, Valero-Cuevas FJ, Guckenheimer JM. <br>
              <b>The dynamic sensorimotor regulation of fingertip force vectors is independent of hand strength.</b> <br>
              33th Annual Meeting of the Society for Neuroscience. New Orleans, LA, 2003.</td>
          <td><a href="https://usc-bbdl.github.io/Papers/Venkadesan2003dynamic.pdf">Link</a></td>
          <td></td>
          <td>2003</td>
        </tr>

        <tr>
          <td>Valero-Cuevas FJ, Venkadesan, M, Talati, A Hirsch J. <br>
              <b>How networks of cortical activity adapt in response to changes in the type and quality of sensory input during dynamic precision pinch.</b> <br>
              32th Annual Meeting of the Society for Neuroscience. Orlando, FL, 2002.</td>
          <td></td>
          <td></td>
          <td>2002</td>
        </tr>

        <tr>
          <td>Valero-Cuevas FJ, Burgar CG, Johanson ME, Zajac FE. <br>
              <b>Scaling of muscle activation patterns during generation of isometric fingertip forces. </b> <br>
              28th Annual Meeting of the Society for Neuroscience. Los Angeles, CA, 1998.</td>
          <td></td>
          <td></td>
          <td>1998</td>
        </tr>

        <tr>
          <td>Valero-Cuevas FJ, Burgar C, Zajac FE, Hentz VR, McGill KC, An KN. <br>
              <b>Muscle coordination during maximal index-finger ad-abduction forces. </b> <br>
              Abstracts V. I, 26th Annual Meeting of the Society for Neuroscience, Washington, DC., 1996.</td>
          <td></td>
          <td></td>
          <td>1996</td>
        </tr>

         </tbody>
         </table>
  </div>

  <div data-role="footer">
  </div>
</div>
-->
