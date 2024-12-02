# LearningAnimations - XBot from Mixamo

## Project Overview
This project demonstrates basic animations using the Y-Bot model imported from Mixamo. The bot showcases three core animations:
Idle: The bot remains stationary.
Walk: The bot moves forward at a walking pace.
Run: The bot moves forward at a running speed.
The animations are managed in Unity using the Animator window, which facilitates seamless transitions between states. This setup allows the bot to fluidly shift between idle, walking, and running animations.

## Features
Idle Animation: The bot stays stationary when there is no movement input.
Walking Animation: The bot moves at a walking pace when a low movement input is received.
Running Animation: The bot accelerates to a run when a higher movement input is detected.
Smooth Animation Transitions: The transitions between animations are managed using Unity’s Animator Controller.

## Requirements
- Mixamo account for downloading Xbot or Ybot animations.
- Basic understanding of Unity’s Animator window and animation state machines.
  
## Detailed Description
1. Download the X-Bot Model and Animations from Mixamo:
- Visit the Mixamo website.
- Search for "X-Bot" or choose any character you prefer.
- Select the animations: Idle, Walk, and Run.
- Download the X-Bot model along with the selected animations in FBX format.
2. Set Up Your Unity Project:
- Open Unity Hub and create a new 3D project.
- Import the X-Bot model (the FBX file you downloaded) into Unity by dragging it into the Assets folder.
- In the import settings of the X-Bot model, make sure the Rig type is set to Humanoid.
- Import all animations (Idle, Walk, Run) linked to the X-Bot.
3. Create and Set Up an Animator Controller:
- Right-click in the Assets window, select Create > Animator Controller, and give it a name like XBot_Animator.
- Double-click the Animator Controller to open the Animator window.
- Drag the Idle, Walk, and Run animations into the Animator window as individual Animation States.
- Set up transitions between these animation states:
         Idle → Run → Walk → Idle (for looping between animations).
- Modify transition conditions to control when each animation is triggered (e.g., using parameters like Speed).
![walk](https://github.com/user-attachments/assets/ea4e044f-acfa-46a9-a95f-186bb281cdec)

