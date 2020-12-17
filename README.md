# RoboHands-UnityXR

![RoboHandsPackImage3_50x](https://user-images.githubusercontent.com/12396056/102532535-2409bf00-4072-11eb-874d-f9ed6cb4fe99.png)

ROBOHANDS XR
-----------------------------------------------------------------------------------------------

A UnityXR package designed to quickly get hand controller animations up and running!

This package was created to make it easier to implement multi-pose hand gestures in your own VR games! 
This package includes custom hand models, overhauled hand presence script, custom designed animation controller, and several prefabs.

Unlike some implementations, this package DOES use individual animations for each gameobject grabbed (not yet implemented) 
although inefficient for games with an enormous amount of interactable objects, for games with more streamlined controls this
package can lead to lively hand models with fine-tuned finger and grab animations. 
And as the RoboHands base package (what is found here on Github) is effectively free and open-source, it's easy to add your own functionality to the base scripts and prefabs.

Look at this gallery for some examples of the hand poses included in the package - https://imgur.com/gallery/ub7G5VO

/////////////////////////////////////////////////////////
INSTALLATION
////////////////////////////////////////////////////

Step 0. Ensure you're running Unity 2019.4.9f1

Step 1. Download the unity package from here - https://drive.google.com/drive/folders/1FjYzbB1yKYo6sWYWB7VclbF7_oXv62s1?usp=sharing

Step 2. Go to this link - https://www.youtube.com/watch?v=KHWuTBmT1oI - Watch until 7:15 and follow Valem's steps to set up the XR Rig. At 7:15, when he imports
his hand presence package, import my package instead!

MAKE SURE you install the XR Interaction Toolkit and the XR Legacy Input Helpers packages before continuing (Input Helpers should be included in the toolkit)

Step 4. Then go into the Prefabs folder of this package (RoboHand Package > Prefabs) and drop the Left and Right_Hand_Presence prefabs I created onto the VR rig in the spots for each hand. 

Step 5. Put on your headset and grab a controller! If you're on Oculus, you should have a total of 8 hand poses available:

- Idle (+ Idle Thumbs Up)

- Fist

- Grip (+ Grip Thumbs up)

- Pinch

- Point

- Finger Gun

- Thumbs Up

- Open Hand


And your VR hands should be complete! Feel free to make your own hand model and attach it to the rig set up in the included Blend file too (for advanced users).

/////////////////////////////////////////////////////////
EXTRA INFO, CREDITS & LINKS
/////////////////////////////////////////////////////////

An alternate hand model was provided by the amazing Robert Ramsay on Sketchfab! These hand models aren't free, 
but he's been incredibly generous and allowed me to use the model itself in the pack! Textures are not provided in the RoboHands pack, 
but if you'd like the textures for the models you can purchase them yourself on his Sketchfab page!

Robert's Sci-fi Gloves - https://skfb.ly/6AWNP

Robert's website - https://robertramsay.co.uk/

Thanks to Valem for creating the tutorial helping to teach me and many others how to code for VR in Unity. 
I used what I learned from his videos to expand into this package. :D 

Valem's Channel - https://www.youtube.com/channel/UCPJlesN59MzHPPCp0Lg8sLw

A Hand Model for this package was created by 3DMaesen on Sketchfab! Follow Maesen and check out more cool models here - https://sketchfab.com/bumstrum

Want to add your own hand poses or make changes to the included ones? Install Blender 2.79 and open the included .blend file to do so! (currently my hand model only)

Download Blender 2.79 from this link - https://www.blender.org/download/releases/2-79/

If you make changes to the included .blend file (where the model was rigged), make sure to export the Blender project to the included fbx file so animations don't break.

This GitHub Repository is the home for the free version of the RoboHands package, which includes a limited but helpful amount of assets for budding unity VR developers. 
However, if you would like a package with more features, I'm working on it currently and plan to sell it for a few bucks on the Unity Asset Store soon! 
Keep an eye out for a new link here in the readme to the Asset Store page eventually!

The Github Repo - https://github.com/InfernoDigital/RoboHands-UnityXR

Playable RoboHands Package Demos - https://drive.google.com/drive/folders/1G3x2topHxRTLfjWdo8vKiXtwc7KVEIIM?usp=sharing

Enjoy!
