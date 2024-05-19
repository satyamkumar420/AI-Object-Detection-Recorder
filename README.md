# 🎥 AI Object Detection Recorder

AI Object Detection Recorder is a web application that uses TensorFlow's COCO-SSD model to detect objects in real-time through your webcam feed. The application allows you to take snapshots, record videos manually, and enable automatic recording when any object is detected.

## 🚀 Features

- 🌗 **Dark Mode/System Theme Toggle**: Switch between dark mode and system theme.
- ↔️ **Horizontal Flip**: Adjust the horizontal orientation of the webcam feed.
- 📸 **Take Pictures**: Capture snapshots from the video feed at any moment.
- 📽️ **Manual Video Recording**: Manually record video clips as needed.
- 🚫 **Auto Record**: Enable or disable automatic video recording when an object is detected.
- 🔊 **Volume Control**: Adjust the volume level of the notification sounds.
- 🎨 **Camera Feed Highlighting**: Highlights detected persons in red and other objects in green.

## 🛠️ Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- Node.js (version 18 or higher)
- npm (version 9 or higher)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ai-object-detection-recorder.git
   cd ai-object-detection-recorder
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser**:
   Navigate to `http://localhost:3000` to see the application in action.

## 📂 Project Structure

- `components/`: Contains UI components such as buttons, toggles, and sliders.
- `utils/`: Utility functions for sound, drawing, and other operations.
- `pages/`: The main page of the application.
- `public/`: Static assets like images.
- `styles/`: CSS styles for the application.

## 🎨 UI Components

- **ModeToggle**: Toggle between dark mode and system theme.
- **Button**: Customizable buttons for various actions.
- **Popover**: Popover components for volume control.
- **Slider**: Volume control slider.

## 🔧 Utility Functions

- `beep()`: Function to play notification sounds.
- `drawOnCanvas()`: Function to draw detected objects on the canvas.
- `resizeCanvas()`: Adjusts the canvas size based on the webcam feed.
- `base64toBlob()`: Converts a base64 image to a Blob for downloading.

## 🧠 Model Integration

This application uses the COCO-SSD model from TensorFlow for real-time object detection.

## 📸 Taking Snapshots

To take a snapshot, click the camera icon. The snapshot will be downloaded as a PNG file.

## 📽️ Manual Recording

To start/stop manual recording, click the video icon. The recording will be saved as a WebM file.

## 🚫 Auto Record

Toggle the auto-record button to enable or disable automatic recording. When enabled, the application will start recording automatically when any object is detected.

## 🔄 Horizontal Flip

Click the flip icon to toggle the horizontal orientation of the webcam feed.

## 🔊 Volume Control

Click the volume icon to adjust the notification sound volume using the slider.

## 🙌 Acknowledgments

- TensorFlow.js
- COCO-SSD Model
- React
- Next.js

---

Enjoy using the AI Object Detection Recorder! 🎉

If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Happy coding! 😊

---
