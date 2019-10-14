# VRChat Virtual Productions

This package is a starting point for anyone interested is making virtual productions over the network inside [Unity](https://unity.com) and [VRChat](https://vrchat.com). You can create your own set or sound stage and then use this camera system to help you speed up production with access to 10 cameras, a camera crane with controls, and 12 overlay slides. 

![](https://i.imgur.com/dy1UsdH.jpg)

You can swap out the slides once you have setup a unity project and imported the package. This is used as a real-time production environment from which we capture the output with [OBS](https://obsproject.com). 


---
 
## Installation


You will need VRChat installed and an [account](https://vrchat.com/home/register) to be able to build and publish worlds. VRChat runs on PC and VR and is downloadable from [Steam](https://store.steampowered.com/app/438100/VRChat/) or [Oculus Store](https://www.oculus.com/experiences/rift/997678176960598/?locale=en_US).

This package works with other custom packages in Unity3d. Please read and follow these steps to setup the project. 

**Important**: Include Standard Assets / [VRChat SDK](https://docs.vrchat.com/docs/setting-up-the-sdk) before importing package!

1. Create new Unity Project with version 2017.4.28f1 (or current version VRC runs on)
2. **First** import the [VRC SDK](https://docs.vrchat.com/docs/setting-up-the-sdk) to the project
3. Save Scene
4. Import the camera package, drag prefab into the scene
5. Configure camera positions / animations and scene adjustments
6. Adjust scene lighting
7. Configure layers / Collision matrix for VRC with VRCSDK before publishing
8. Publish to VRC

---

## Buttons

### Camera Panel 

- `1-9` keys will swap between cameras 
- `0` goes to Overlay mode 
- `=` Shows/Hides the Camera Crane 
- `-` Changes to the Camera Crane once it is visible (it will not switch if it is hidden) 
- `F` will change the screen to Full Screen mode, and the camera output will be mapped to the screen

You can also use the in-game buttons on the camera panel itself if you are in VR mode. The "VR Keyboard" works as well to switch cameras.

### Lighting Panel 

- You have to enable the lights, they are off by default 
- You can change the screen colors by using the Lighting Panel 
- You can change the colors of the lights, and move them with users in game to re-position them. (Careful: laggy when you add too many lights)

### Camera Crane Controls

- The controls are labeled for each direction of movement 
- there is a stop button for each movement and direction 
- you must reset the room, to reset the crane position, since it is based off of root motion

### Generic Switches and Toggles 

- You can show/hide the temp avatar placeholder with the Switch 
- You can turn on real-time reflection probs with the RPROBE switch 
- You can hide all the cameras if you need to


---

## Information

I suggest using this as a starting point, and move the cameras around to create a sound stage / set that works for your needs.

**Pro-Tip**: Because of the way the camera previews work, only move the Master Root of each camera. You can add a Parent object to the cameras, and animate those for animated camera tracks. Also the names of the layers are reset when VRC SDK setups layers for a project, so the Layers that hide things from the camera lose their name (but still work)... if you would like to hide / show things in the camear view, please re-setup layers and use camera culling.

We have filmed many music videos, podcasts and events in VR using this system. It has sped up production when making rooms or builds for vTubing, vPodcasts, and vFilms, and endless "over the network, real-time collaborative" projects.

Please check out some our productions on [Youtube](https://www.youtube.com/results?search_query=godfrey+meyer&page=&utm_source=opensearch) "Godfrey Meyer" or [#boomboxhead](https://www.youtube.com/results?search_query=%23boomboxhead) to find videos. If you have any questions please feel free to reach out to me #boomboxhead on discord `painterpainting#5603`. Have fun and link me to the videos you make, thanks!
