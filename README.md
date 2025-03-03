<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Age & Gender Detection</h1>

<h2>📌 Overview</h2>
<p>
The Age & Gender Detection application is a deep learning-based tool that predicts a person's age range and gender using image or live webcam input. The model utilizes OpenCV's Deep Neural Network (DNN) module for accurate face analysis.
</p>

<h2>🏗 Features</h2>
<ul>
    <li><b>Face Detection:</b> Uses OpenCV's deep learning model to detect faces in an image or video.</li>
    <li><b>Age Prediction:</b> Predicts the age range of the detected face.</li>
    <li><b>Gender Classification:</b> Identifies whether the detected face is <b>Male</b> or <b>Female</b>.</li>
    <li><b>Real-time Processing:</b> Works with both static images and live webcam feed.</li>
    <li><b>No-Face Detection Handling:</b> Displays a message if no face is detected.</li>
</ul>

<h2>🛠 Technologies Used</h2>
<ul>
    <li><img src="https://img.shields.io/badge/-Python-333333?style=flat&logo=python" alt="Python"> Python (Programming Language)</li>
    <li><img src="https://img.shields.io/badge/-OpenCV-333333?style=flat&logo=opencv" alt="OpenCV"> OpenCV (For image processing and face detection)</li>
    <li><img src="https://img.shields.io/badge/-Deep%20Learning-333333?style=flat" alt="Deep Learning"> OpenCV DNN (For face, age, and gender detection)</li>
</ul>

<h2>📊 Model Details</h2>
<ul>
    <li><b>Face Detection Model:</b> Uses OpenCV’s pre-trained deep learning model (<code>opencv_face_detector.pbtxt</code> & <code>opencv_face_detector_uint8.pb</code>).</li>
    <li><b>Age Classification Model:</b> Uses <code>age_net.caffemodel</code> trained on facial datasets to predict age groups.</li>
    <li><b>Gender Classification Model:</b> Uses <code>gender_net.caffemodel</code> to classify gender as <b>Male</b> or <b>Female</b>.</li>
</ul>

<h2>🚀 Installation & Usage</h2>

<h3>🔹 Prerequisites</h3>
<p>Ensure you have Python 3.x installed and install the required dependencies using:</p>
<pre><code>pip install opencv-python argparse</code></pre>

<h3>🔹 Running the Application</h3>
<ul>
    <li><b>For Image Input:</b></li>
    <pre><code>python age_gender_detection.py --image path/to/image.jpg</code></pre>
    <li><b>For Live Camera Feed:</b></li>
    <pre><code>python age_gender_detection.py</code></pre>
</ul>

<h2>📸 Screenshots</h2>
<p> <img width="1440" alt="Screenshot Homepage" src="Screenshot%202024-06-17%20182036.png"></p>

<h2>🤝 Contributors</h2>
<ul>
    <li><b>Mr. Ajay Kumar Soma</b> - Developer</li>
</ul>

<h2>📜 License</h2>
<p>
This project is open-source and available under the <b>MIT License</b>.
</p>

<h2>⚠️ Disclaimer</h2>
<p>
This application provides age and gender predictions based on deep learning models and may not always be 100% accurate. It is intended for experimental and research purposes only.
</p>

</body>
</html>
