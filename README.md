# vertigosimulator
Simulator of BPPV Vertigo

This repository is an open-source simulation of vertigo, specifically Benign paroxysmal positional vertigo (BPPV). To help support this software and other open-source projects, please consider subscribing to my YouTube channel: https://www.youtube.com/@jeoresearch

To use the package, start your own Unity project and import the vertigo.assetpackage into your scene. You will need to import SteamVR into your project with the Unity package manager, which will populate the CameraRig object in the heirarchy. 

Under Build Settings -> Player Settings -> XR Plug-in management, ensure that OpenVR is checked. 

Ensure that SteamVR is running on your desktop. 

Hit play on the Unity player. To activate each simulation, you can press 1-4 on your keyboard, or use a controller to mash down the corresponding box. The simulation should roughly look like the following if it is working properly: https://www.youtube.com/watch?v=dA3Mdgb5q3I

*note that eye tracking is disabled in this version for simplicity. 

Requirements:
- Unity version 2022 or above 
- SteamVR
- HTC Vive or Vive Pro (or comparible VR headset*)
*This is tested with the HTC Vive pro, but could be use for other displays by modifying the CameraRig object in the scene.

***Release of Liability***
By using this vertigo simulation, you acknowledge that this application may cause unpleasant physical or psychological sensations, including but not limited to dizziness, disorientation, nausea, headaches, or vomiting. You are solely responsible for monitoring your own well-being while using this simulation and should discontinue use if you experience any discomfort.

***Disclaimer*** 
This simulation is provided "as is" without any warranties, either expressed or implied, including but not limited to fitness for a particular purpose. The creator(s) of this simulation are not liable for any physical, emotional, or mental distress, injury, or harm that may arise from the use or misuse of this software.

By downloading, installing, or using this software, you agree to release, indemnify, and hold harmless the creator(s) from any and all claims, damages, or liabilities resulting from its use.
