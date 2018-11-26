# Intro to VR Design
Course asset for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: VR Design
- Lesson: Intro to VR Design


### About the Course Asset
This course asset includes a Unity project with a basic scene illustrating the importance of deploying to device early and often to avoid costly mistakes that will take more time to address later.


### Versions Used
- [Unity LTS Release 2017.4.15](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.100.1)
- [Baker's House](https://assetstore.unity.com/packages/3d/environments/fantasy/baker-s-house-26443) v1.2


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### Unity Project Settings
- The project's `Player Settings` and `Quality Settings` are set to default values for the Unity version used.

>**Important!** When deploying to device, make sure you configure the `Player Settings` for the target platform according to what you learned in the previous courses.

>**Note:** When deploying to device, it is recommended to update the `Quality Settings` according to what you learned in the previous courses.


### Unity Lighting Settings
- The scene's `Lighting Settings` are set to default values for the Unity version used.

>**Note:** When deploying to device, it is recommended to update the `Lighting Settings` as well as optimize the scene according to what you learned in the previous courses.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is not included.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.


### Related Repositories
- VR Design - Intro to VR Design
- [VR Design - Movement Mechanics](https://github.com/udacity/VR-Design_Movement-Mechanics/releases)
- [VR Design - Presenting the Work](https://github.com/udacity/VR-Design_Presenting-the-Work/releases)
- [VR Design - Puzzler](https://github.com/udacity/VR-Design_Puzzler/releases)
