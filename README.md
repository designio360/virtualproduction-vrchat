# virtualproduction-vrchat

The virtual production package here is a real-time production environment that can be used in VR / PC 
inside the Unity Game Engine running with VRC SDK. This tool is great for
creating production environments for vTubing, vPodcasts, and vFilms, and 
endless over the network, real-time collaborative projects. If you have any questions
please feel free to reach out to me, Godfrey Meyer aka #boomboxhead. Thanks!


This package works with other custom packages in Unity3d. 
Dependencies; include Standard Assets / VRChat SDK before importing package.

Installation and Project Setup:
1. Create new Unity Project with version 2017.4.28f1 (or current version VRC runs on)
2. Import the VRC SDK to the project FIRST
3. Save Scene.
4. Import the package
5. Configure Camera Positions / Animations and Scene Adjustments
6. Adjust Scene Lighting
7. Configure Layers / Collision Matrix for VRC with VRCSDK before publishing
8. Publish to VRC

Camera Panel Instructions
1-9 swaps between cameras
0 goes to Overlay mode
"=" Shows/Hides the Camera Crane
"-" Changes to the Camera Crane once it is visible (it will not switch if it is hidden)
'F" will change the screen to Full Screen mode, and the camera output will be mapped to the screen

Lighting Panel Instructions
-You can change the screen colors by using the Lighting Panel

Generic Switches and Toggles
-You can show/hide the temp avatar placeholder with the Switch
-You can turn on real time lighting and change colors Lights Switch
-You can turn on real-time reflection probs with the RPROBE switch

Use Cases: vTubing, VR Podcasts, Virtual Film Making, Skits, VR Productions

I suggest using this as a boiler plate, and move the cameras around and create a sound stage / set that works for your needs

ProTips:
Only move the Master Root of the cameras, because the previews are in the exact same place as the actual cameras, so if you move the children, they will not be synced. Just move the Root Node of the cam
You can add a Parent object to the cameras, and animate those for animated camera tracks. 

If you have any questions please feel free to reach out to me #boomboxhead thank you! have fun and link me to the videos you make!
