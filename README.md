<h1> Hand Gesture Volume Control System </h1>

<h2>Overview</h2>
  <p>This Python script utilizes computer vision techniques to track hand gestures in real-time from a webcam feed. It detects specific hand gestures and maps them to control volume adjustments on the system.</p>

  <h2>Features</h2>
  <ul>
      <li>Detects hand gestures using the MediaPipe library.</li>
      <li>Tracks the movement of thumb and index fingers to calculate the distance between them.</li>
      <li>Adjusts system volume based on the distance between fingers.</li>
      <li>Provides visual feedback by drawing landmarks and lines on the webcam feed.</li>
      <li>Can be easily customized and integrated into existing applications.</li>
  </ul>

  <h2>Dependencies</h2>
  <ul>
      <li>OpenCV (cv2): A popular library for computer vision tasks.</li>
      <li>MediaPipe (mediapipe): A framework by Google for building multimodal machine learning pipelines.</li>
      <li>PyAutoGUI (pyautogui): A library for programmatically controlling the mouse and keyboard.</li>
  </ul>

  <h2>Usage</h2>
  <ol>
      <li>Install the required dependencies using pip:</li>
      <code>pip install opencv-python mediapipe pyautogui</code>
      <li>Run the Python script <code>hand_volume_control.py</code>.</li>
      <li>Position your hand in front of the webcam, making sure it's well-lit and visible.</li>
      <li>Perform the following hand gestures:
          <ul>
              <li>Place your thumb and index finger closer together to decrease volume.</li>
              <li>Spread your thumb and index finger farther apart to increase volume.</li>
          </ul>
      </li>
      <li>The system volume will be adjusted accordingly based on the detected hand gestures.</li>
  </ol>

  <h2>Acknowledgments</h2>
  <p>This project is inspired by college professor Kannan S.</p>
