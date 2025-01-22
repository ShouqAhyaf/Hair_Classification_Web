# HairClassifier: Hair Type Classification Using AI

## Table of Contents:
1. Introduction
2. Technologies
3. Components Required
4. Usage Instructions
5. Model
6. Code

---

## Introduction
This project demonstrates the classification of hair types using an AI-powered image recognition model. The trained model categorizes images into four distinct hair types:

- Straight
- Wavy
- Curly
- Kinky

---

## Technologies
- **HTML, CSS, JavaScript**: For creating the front-end interface.
- **TensorFlow.js**: For running the AI model in the browser.
- **Teachable Machine**: For creating and exporting the pre-trained model.

---

## Components Required
- **Pre-trained TensorFlow.js Model**: Accessible from Teachable Machine.
- **Browser**: Chrome, Firefox, or any modern browser that supports TensorFlow.js.
- **Camera**: For real-time classification or pre-uploaded images.

---

## Usage Instructions

### Setup
1. Clone the project or copy the files.
2. Ensure the following files are present:
   - `model.json`: The TensorFlow.js model file.
   - `metadata.json`: Metadata for the model.
   - Supporting files for the model.

3. Open the HTML file in a browser.

### Running the Classifier
1. **Real-Time Classification**:
   - Allow the browser to access your camera.
   - Press "Capture Hair Type" to classify the hair in the video feed.

2. **Image Upload**:
   - Use the "Upload Image" button to select an image.
   - The classifier will predict the hair type of the uploaded image.

3. **Reset**:
   - Use the "Reset" button to clear the current results and start over.

---

## Model
- **Labels**:
  The hair types are classified into the following categories:
  - 0: Straight
  - 1: Wavy
  - 2: Curly
  - 3: Kinky

- **Classification Results**:
  The output includes:
  - The predicted hair type.
  - A confidence score for each classification.

---

## Code
The complete implementation is available in the provided HTML and JavaScript files. The core functionality involves:

1. Loading the TensorFlow.js model.
2. Using the browser's `getUserMedia` API for camera access.
3. Predicting hair types for real-time video or uploaded images.

For detailed code and explanations, refer to the main `index.html` file.

