# Distant-Lands

### Instructions to Build and Execute Code

#### Prerequisites:
- **Unity Version**: Ensure `Unity 2022.3.43f1` is installed.
- **Required Packages**:
  - Gaia for landscape generation.
  - ChatGPT integration or any specific landscape and AI generation packages.
- **Version Control**: Set up version control with `Unity Version Control (Plastic SCM)` or `GitHub with GitHub LFS` if using large assets.

#### Setup:
1. **Clone the Repository**:
   ```bash
   git clone [repository link]
- **Open the project in Unity 2022.3.43f1.
- **Download any dependencies specified in the "Packages" folder or within the Project settings.

#### Configuration:
- Ensure that Unity permissions for microphone and VR are enabled for voice command functionality.
- Configure the ChatGPT and Gaia APIs as per the setup in APIKeys.txt or relevant configuration file (as specified in the README).
- For VR testing, ensure VR hardware is connected and recognized by Unity.
    
#### Build and Run:
- Select the main scene (MainScene.unity or as specified) and set it as the starting scene in Build Settings.
- To test on desktop: Go to File > Build and Run.
- For VR testing: Adjust build settings for VR mode, then select Build and Run with connected VR hardware.
- Press the designated button on the VR controller to start voice recognition and initiate landscape generation.
  
#### Common Issues:
- Missing dependencies? Re-import assets under Assets > Reimport All.
- Audio or VR setup issues? Check permissions in Project Settings > Player.
