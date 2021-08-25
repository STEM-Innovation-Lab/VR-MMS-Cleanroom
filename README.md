# MMS Cleanroom Virtual Reality Experience

This is a build-only repository to help distribute this project to our communities. Please access this build by [downloading the PC installer](https://github.com/STEM-Innovation-Lab/VR-MMS-Cleanroom/releases/download/v0.1.1-beta/MMSCleanroom.Setup.x86_64.zip) from in the ["releases"](https://github.com/STEM-Innovation-Lab/VR-MMS-Cleanroom/releases) page.

## Get Started:

### [Download PC Installer](https://github.com/STEM-Innovation-Lab/VR-MMS-Cleanroom/releases/download/v0.1.1-beta/MMSCleanroom.Setup.x86_64.zip)

**Works with HTC Vive, Valve Index, and other SteamVR compatible devices and requires Steam VR be installed and running**

### Instructions:
* MMS Cleanroom (Magnetosphereic Multiscale Mission)
  * You will start out in the MMS Cleanroom in front of a partially built MMS spacecraft. Several of the instruments on the satellite are removeable and replaceable. Another point of interest in the room is the large bay door. Once you approach the door it will open where you can exit the cleanroom onto a "space balcony" and get a near-real-time view of Earth. This view of earth is taken directly from the Goes East Satellite data stream as long as the user has an internet connection while playing. Back in the cleanroom there is a joystick that operates the crane in the ceiling. At the present time the crane doesn't do anything other than move around, but in a future update we are hoping to put it to use. To move to the other scenes in this experience you can teleport over to the "teleportal" (blue glowing hexagon on the floor) or press the menu button on the controller to be transported there instantly. Once there, three scene menu items will appear and you can reach out and select another scene to explore.
* Magnetosphere
  * This is a space scene where the VR controllers are used to fly (front trigger on both controllers). The lines emanating out from the Earth are representations of the Earth's magnetic field lines, also called Earth's magnetosphere. The orange line represents the orbit of the four MMS space craft. To exit this scene click the menu button on your controller to be transported back to the "teleportal". Once there just select a different scene from the menu.
* Solar System, Parker Solar Probe
  * This simulation shows the sun and a volumetric visualization of a coronal mass ejection. Orbit lines for Mercury, Venus, Earth, and the Parker Solar Probe(PSP) spacecraft also exist. Along the PSP orbit you will find the PSP satellite. The touchpad(Vive controller) should now show three new icons: change color map, data voxelization, and jump to Parker Solar Probe. The triggers on your controller will allow you to flow just like in the magnetosphere scene.
* Steam Innovation Lab
  * This scene was originally our physical menu space, allowing you to move between the other three scenes and requiring the user to revisit the scene before moving to a different one. Because two of our scenes were so closely related we decided to create a different in-game menu system and have reserved this scene for information about the actual STEAM Innovation Lab in Goddard. At the present time this scene is very much a work in progress

## Known Issues:
* Some non-Vive VR controllers exhibit odd behavior and interaction doesn't always work
* Instruments in the Cleanroom scene occasionally fall through the floor
* Visuals in the HMD freeze during scene change (fixed in Steam VR 2.0 Interaction Kit)
* Over time instruments on the satellite will slowly move towards the floor
* Occasional crashes in the Solar System, Parker Solar Probe scene

## Roadmap:
In the coming months we will be re-focusing this project towards goal-oriented learning, adding narration, audio, and a few activities for the user to complete. We are also in the process of migrating this project to SteamVR 2.0, and possibly Unity's XR toolkit. If time permits we may create a low-poly condensed version of this project for the Oculus Quest.
