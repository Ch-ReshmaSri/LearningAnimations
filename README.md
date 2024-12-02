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
![walk](https://github.com/user-attachments/assets/b32e1fa7-b516-45da-8fe3-7584227ac836)
4. Assign the Animator Controller to the X-Bot:
- Select the X-Bot object in the Hierarchy window.
- In the Inspector, find the Animator component.
- Assign the XBot_Animator Controller to the Animator component.
![run](https://github.com/user-attachments/assets/263b09e1-f0b3-4b9d-a059-05d97b4506b0)
5. Testing the Animation in Unity:
- Press Play in Unity to test the animations.
- The X-Bot will transition between Idle, Walk, and Run based on the Animator transitions.
Note: Since no user input or custom code is used, the animations will transition automatically according to the default settings in the Animator. You can fine-tune the speed and conditions for transitions.
## How to Play:
1. Press Play in Unity to start the demo.
2.  Watch the X-Bot smoothly transition between idle, walking, and running animations based on the Animator setup.


