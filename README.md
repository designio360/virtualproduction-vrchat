# virtualproduction-vrchat

This package is a starting point for anyone interested is making virtual productions over the network inside Unity and VRChat. You can create your own set or sound stange, and then use this camera system to help you speed up production and give you access to 10 cameras, a camera crane with controls, and 12 overlay slides. You can swap out the slides once you have setup a unity project and imported the package. This is used a is a real-time production environment and we fill the output with OBS (Open Broadcast Software) . VRChat runs on PC and VR, and you will need VRChat (and a VRChat account) to be able to build and publish worlds. This speeds up production when making rooms or builds for vTubing, vPodcasts, and vFilms, and endless "over the network, real-time collaborative" projects. We have filmed many music videos, podcasts and events in VR using this system, please check out some our productions on youtube "Godfrey Meyer" or #boomboxhead to find videos. If you have any questions please feel free to reach out to me on discord painterpainting#5603. Thanks!

Examples of Cameras in Use https://youtu.be/QaEonBvXMSA


This package works with other custom packages in Unity3d. Please read and follow these steps to setup the project. 
Dependencies; include Standard Assets / VRChat SDK before importing package.

Installation and Project Setup:
1. Create new Unity Project with version 2017.4.28f1 (or current version VRC runs on)
2. Import the VRC SDK to the project FIRST
3. Save Scene.
4. Import the camera package
5. Configure camera positions / animations and scene adjustments
6. Adjust scene lighting
7. Configure layers / Collision matrix for VRC with VRCSDK before publishing
8. Publish to VRC

Camera Panel Instructions
ALPHA 1-9 keys will swap between cameras
0 goes to Overlay mode
"=" Shows/Hides the Camera Crane
"-" Changes to the Camera Crane once it is visible (it will not switch if it is hidden)
'F" will change the screen to Full Screen mode, and the camera output will be mapped to the screen

You can also use the ingame buttons on the camera panel its self if you are in VR, also to be noted that the "VR Keyboard" works as well to switch cameras.

Lighting Panel Instructions
-You have to enable the lights, they are off by default
-You can change the screen colors by using the Lighting Panel
-You can change the colors of the lights, and move them with users in game to re-position them. (Careful laggy when you add many lights)

Generic Switches and Toggles
-You can show/hide the temp avatar placeholder with the Switch
-You can turn on real-time reflection probs with the RPROBE switch
-You can hide all the cameras if you need to

Use Cases: vTubing, VR Podcasts, Virtual Film Making, Skits, VR Productions

I suggest using this as a starting point, and move the cameras around to create a sound stage / set that works for your needs. 

ProTips:
Only move the Master Root of each camera, because the way the camera previews work.
You can add a Parent object to the cameras, and animate those for animated camera tracks. 

If you have any questions please feel free to reach out to me #boomboxhead thank you! have fun and link me to the videos you make!
