# ML-image-classification
This project uses a custom-trained YOLOv8 model to detect Indian cricket players, specifically Virat Kohli and Rohit Sharma, in real-world images. Built on Google Colab using the Ultralytics YOLO library, the goal was to explore image classification techniques by working with images of favorite cricketers.

<h2> Annotations and Dataset Preparation</h2>
Images were annotated using <a href="https://roboflow.com/" target="_blank">Roboflow</a>, a web-based annotation tool.

Then the dataset was exported in the YOLO format, which includes:
A text file for each image containing bounding box coordinates and class IDs.
A data.yaml file specifying the class names and paths for training.

After export, the dataset was uploaded to Google Colab for training the YOLOv8 model.<br><br>

<h2> Dependencies</h2>
Make sure the following are installed in your environment:<br>

<ul> <li><code>ultralytics</code></li> <li><code>torch</code></li> <li><code>opencv-python</code> (optional, for extra processing)</li> </ul><br>
Install using:<br>
<code>pip install ultralytics</code><br><br>

<h2>🚀 Running the Model</h2>
Load the model and run prediction on an image<br>
