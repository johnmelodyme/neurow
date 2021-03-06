# README #

![Unity Version](https://img.shields.io/badge/Unity%20Version-4.6-orange.svg)

NeuRow is Immersive VR Environment for Motor-Imagery training with the use of Brain-Computer Interfaces (BCIs). NeuRow is a rowing simulator with main target to capture as many flags as possible in a fixed time-window in a closed neurofeedback loop. Moreover, NeuRow is available for PC, Android OS and also with web browser support through the use of [RehaPanel](https://github.com/athanoid/rehapanel), a midleware between interfaces and VR.

[NeuRow Website](http://neurorehabilitation.m-iti.org/bci/)

[Video](https://www.youtube.com/watch?v=kHFfXIuESTc)

### NeuRow versions ###

* The **standalone version** for PC, supports high quality graphics for an immersive VR experience, with the support of the Oculus Rift headset (for developer kits), the Leap Motion hand controller and vibrotactile feedback. Moreover, data logging is supported for boat trajectory, target location, score and time.
* The **mobile version** is build for Android OS devices, receiving data through the RehabNet protocol through the [Rehapanel](https://github.com/athanoid/rehapanel). For phones, the VR feature can be utilized for VR glasses (e.g. Google Cardboard) by applying lens correction for each eye, and uses the phone gyroscope for head tracking, offering an immersive experience similar to the Oculus DK1, DK2 HMDs. Finally, NeuRow is available on [Google Play](https://play.google.com/store/apps/details?id=com.vourvopoulos.neurow).
* The **web version** is using the Unity web player (compatible only through Internet Explorer, Firefox or Opera), without the networking component due to security restrictions. Instead, the web NeuRow is acquiring emulated keyboard buttons through the [Rehapanel](https://github.com/athanoid/rehapanel).

![NeuRow](http://neurorehabilitation.m-iti.org/bci/wp-content/uploads/2016/01/20160118_165357-e1454019173422.jpg "NeuRow Setup")

## Required Software: ##
* [RehaPanel](http://neurorehabilitation.m-iti.org/tools/rehabnetcp)
* [OpenVibe v 0.18](http://openvibe.inria.fr/)

##Publications:##
**A Vourvopoulos**, A Ferreira, S Bermúdez i Badia. (2016). NeuRow: An Immersive VR Environment for Motor-Imagery Training with the Use of Brain-Computer Interfaces and Vibrotactile Feedback. Presented at the PhyCS 2016 - 3rd International Conference on Physiological Computing Syst, Lisbon.
