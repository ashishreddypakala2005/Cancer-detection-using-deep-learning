# Cancer-detection-using-deep-learning
Deep learning–based cancer detection uses neural networks to analyze medical images and identify early signs of tumors. It improves diagnostic accuracy, speeds up detection, and assists doctors in making timely, data-driven decisions for better patient outcomes.
🧠 Cancer Detection Using Deep Learning
📌 Project Overview
This project uses a Convolutional Neural Network (CNN) to detect the presence of cancer (tumor) from MRI images. The model classifies images into two categories: Tumor (Cancer) and Normal, and also provides a confidence score for prediction.

🎯 Objective

To build an AI model that can automatically detect cancer from medical images.
To assist in early diagnosis using deep learning techniques.

🧾 Dataset
Brain MRI Images Dataset

Contains two classes:

Yes → Tumor present
No → No tumor

⚙️ Technologies Used

Python
TensorFlow / Keras
OpenCV
NumPy
Matplotlib
Google Colab

🧠 Model Used

Convolutional Neural Network (CNN)
Multiple Conv2D and MaxPooling layers
Dense layers with sigmoid activation for binary classification

🔄 Workflow

Load dataset
Preprocess images (resize, normalize)
Split data (train/test)
Train CNN model
Evaluate accuracy
Predict on new images

📊 Output

Prediction: Cancer / Normal
Confidence Score: Percentage indicating model certainty

📸 Sample Output

Uploaded MRI image is displayed
Model predicts result
Confidence score is shown

📈 Results

Achieved good accuracy on test data
Successfully detects tumor presence in MRI images

🚀 Future Improvements

Use Transfer Learning (ResNet, MobileNet)
Improve accuracy with larger dataset
Build web app using Streamlit

👨‍💻 Author
Ashish Reddy
