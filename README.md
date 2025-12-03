Project Title

AI Image Classifier 🖼️

Description

AI Image Classifier is a simple web application built with Streamlit and TensorFlow’s MobileNetV2 model. Users can upload images (JPG, JPEG, PNG), and the AI model predicts the top 3 possible classes with confidence scores. This project demonstrates the power of deep learning for image recognition in an easy-to-use interactive interface.

Features

Upload images in JPG, JPEG, or PNG format.

Preprocesses images for MobileNetV2 model automatically.

Predicts top 3 image classes with confidence percentages.

User-friendly interface built with Streamlit.

Fast and efficient due to model caching.

Technologies Used

Python 3.x

TensorFlow 2.x

Keras (via TensorFlow)

Streamlit

OpenCV

Pillow (PIL)

Installation

Clone the repository:

git clone https://github.com/yourusername/ai-image-classifier.git
cd ai-image-classifier


Create a virtual environment (optional but recommended):

python -m venv venv


Activate the virtual environment:

Windows:

venv\Scripts\activate


Linux/Mac:

source venv/bin/activate


Install dependencies:

pip install -r requirements.txt

Usage

Run the Streamlit app:

streamlit run main.py


Open the app in your browser (usually at http://localhost:8501).

Upload an image and click “Classify Image” to see predictions.

Screenshots

(Optional: Add screenshots of your app running here to make your repo attractive.)

Project Structure
ai-image-classifier/
│
├─ main.py              # Streamlit app code
├─ requirements.txt     # Project dependencies
└─ README.md            # Project documentation

Contributing

Contributions are welcome! If you want to add new features, improve the interface, or enhance model performance, feel free to fork the repo and create a pull request.
