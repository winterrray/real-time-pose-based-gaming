# real-time-pose-based-gaming

## methodology
- define set of distinct poses that will correspond to respective keyboard moves 
  - pose-to-action mapping
- mediapipe
  - pose detection & tracking
- incorporate PyAutoGUI
  - Simulate user input that replicates action in the game
- Matplotlib
  - Visualise the gaming environment

## implementation
1. Setup and Installation:
   -  Matplotlib, PyAutoGUI, and MediaPipe.
   -  Python & vscode

2. Design the Game:
   - Plan the gameplay mechanics, objectives, and user interactions that will be influenced by pose detection.

3. Pose Detection Integration:
   - Use MediaPipe's pose estimation model to detect and track the user's pose in real-time.

4. Define Poses and Actions:
   - Map specific poses or movements to corresponding in-game actions. 

5. Implement Game Logic:
   - Write code that interprets the detected poses and triggers game actions based on the predefined mapping.
   - Use PyAutoGUI to simulate user input that initiate the desired in-game actions.

6. Game Visualization:
   - Utilize Matplotlib to create visualizations for the gaming environment.


Tools Used
- OpenCV
- cvzone
- MediaPipe
- PyAutoGUI
- matplotlib
