
Overview
This project aims to detect diseases in potato leaves using computer vision and deep learning techniques. The system uses a convolutional neural network (CNN) model built with TensorFlow to classify images of potato leaves into different categories: healthy or infected with specific diseases. The web application is built using Streamlit, and it utilizes OpenCV for image preprocessing and manipulation.

Technologies Used
Streamlit: For creating the web-based user interface.
Jupyter Notebook: For developing, training, and testing the model.
TensorFlow: For building and training the deep learning model.
OpenCV: For preprocessing images before feeding them into the model.
Python: For overall scripting and integration of all components.
Project Structure
streamlit_app.py: The main Streamlit application file for the web interface.
model.ipynb: The Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
trained_model.h5: The trained model saved as a .h5 file.
data/: Folder containing datasets for training and testing the model.
images/: Folder for storing the input images for detection.
requirements.txt: List of required Python packages.
Setup Instructions
1. Install Dependencies
Make sure you have Python 3.x installed. Then, install the required libraries using pip:

bash
Copy
Edit
pip install -r requirements.txt
This will install the necessary dependencies such as TensorFlow, OpenCV, Streamlit, etc.

2. Train the Model (Optional)
If you want to retrain the model with your own dataset, you can run the Jupyter notebook (model.ipynb). This notebook includes the code for loading and preprocessing the potato leaf dataset, building the CNN model, and training it.

3. Run the Streamlit App
Once the dependencies are installed and the model is trained, you can run the Streamlit app:


streamlit run streamlit_app.py
This will launch the web app where you can upload an image of a potato leaf and get real-time predictions about whether the leaf is healthy or infected with a specific disease.

Features
Upload an image of a potato leaf for disease detection.
Real-time feedback on the health status of the leaf.
Use of deep learning models for accurate classification.
Usage Example
Once the application is running, you can interact with it via the web interface:

Upload an image of a potato leaf.
The system will process the image and predict whether the leaf is healthy or affected by a disease like late blight, early blight, or others.
Model Performance
The deep learning model used in this project is a CNN trained on a dataset of potato leaf images. It is evaluated using accuracy, precision, recall, and F1-score metrics, with the goal of providing reliable disease detection.

Contributing
Feel free to fork the repository, submit pull requests, or report issues. Contributions to improving the model's performance or enhancing the web app are always welcome.
