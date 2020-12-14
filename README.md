# RoboHands-UnityXR

![RH1-2](https://user-images.githubusercontent.com/12396056/102137488-e9611600-3e28-11eb-9f3a-149ee6549ff8.png)

A UnityXR package designed to quickly get hand controller animations up and running!

This package was created to make it easier to implement multi-pose hand gestures in your own VR games!
This package includes a custom hand model, rewritten hand presence script, custom designed 
animation controller, and several prefabs.

Look at this gallery for some examples of the hand poses included in the package - https://imgur.com/gallery/ub7G5VO

Installation instructions - 

Step 0. Download the unity package from here.

Step 1. Go to this link - https://www.youtube.com/watch?v=KHWuTBmT1oI - and watch the video
until the part where valem makes changes to the hand presence prefabs on the VR player rig.

MAKE SURE you install the XR Interaction Toolkit and the XR Legacy Input Helpers packages before continuing (Input Helpers should be included in the toolkit)


Step 2. When you get to that part, instead of editing the prefabs, delete them. 

Step 3. Then go into the Prefabs folder of this package and drop the RoboHand_Presence prefabs
I created onto the VR rig in the spots for each hand. The RoboHand_Presence prefabs are already
set up to work with the new animators and script!

Step 4. Put on your headset and grab a controller! If you're on Oculus, you should have a total
of 7 hand poses available:

- Idle (+ Idle Thumbs Up)
- Fist
- Grip (+ Grip Thumbs up)
- Pinch
- Point
- Finger Gun
- Thumbs Up
- Open Hand

And your VR hands should be complete! Feel free to make your own hand model and attach it to the
rig set up in the included Blend file too (for advanced users).

Want to add your own hand poses or make changes to the included ones?
Install Blender 2.79 and open the included .blend file to do so!

Download Blender 2.79 from this link - https://www.blender.org/download/releases/2-79/

If you make changes to the included .blend file (where the model was rigged), 
make sure to export the Blender project to the included fbx file so animations don't break.

This github repository is the home for the free version of the RoboHands package, which includes a limited but helpful amount of assets
for budding unity VR developers. However, if you would like a package with more features, I'm working on it currently and plan to
sell it for a few bucks on the Unity Asset Store soon! Keep an eye out for a new link here in the readme to it eventually!

Enjoy!

P.S. Thanks to Valem for creating the tutorial helping to teach me and many others how to code for VR in Unity.
I used what I learned from his videos to expand into this package. :D
