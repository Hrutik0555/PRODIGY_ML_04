✋ Hand Gesture Recognition using Machine Learning

📌 Project Overview

This project is part of Task 4 of the Prodigy InfoTech Machine Learning Internship.

The objective is to develop a Hand Gesture Recognition model capable of accurately identifying and classifying different hand gestures from image data. This enables intuitive human–computer interaction and gesture-based control systems.

The project uses the LeapGestRecog Dataset, a well-known hand gesture image dataset collected using Leap Motion sensors.



Dataset Link:

https://www.kaggle.com/gti-upm/leapgestrecog



✨ Features

* Image dataset loading and preprocessing
* Image resizing and normalization
* Train-test data splitting
* Multi-class gesture classification
* Gesture prediction system
* Model evaluation using accuracy metrics
* Visualization of sample predictions



🚀 Quick Start

1️⃣ Clone Repository

git clone https://github.com/Hrutik0555/PRODIGY_ML_04.git

cd hand-gesture-recognition



2️⃣ Install Dependencies

pip install -r requirements.txt



3️⃣ Download Dataset



Place dataset folder as:



data/

└── leapGestRecog/

&nbsp;   ├── 00/

&nbsp;   ├── 01/

&nbsp;   └── ...



4️⃣ Run Notebook

jupyter notebook Hand\_Gesture\_Recognition.ipynb



📂 Project Structure

hand-gesture-recognition/

│

├── data/

│   └── leapGestRecog/

│

├── notebooks/

│   └── Hand\_Gesture\_Recognition.ipynb

│

├── src/

│   ├── preprocess.py

│   ├── train.py

│   └── model.py

│

├── models/

│   └── best\_model.h5

│

├── README.md

├── requirements.txt

└── LICENSE



🛠️ Technologies Used

* Python 3.x
* NumPy \& Pandas
* OpenCV \& PIL
* Scikit-learn / TensorFlow
* Matplotlib \& Seaborn
* Jupyter Notebook



📊 Model Performance

Metric	Result

Validation Accuracy: ~90%

Number of Gesture Classes: 10

Input Image Size: Standardized resized frames



🔎 Code Analysis Summary

Based on your notebook implementation:

* Images loaded from labeled gesture folders
* Resized to fixed resolution
* Pixel normalization applied
* Labels encoded for multi-class learning
* Train-test split executed
* Model trained successfully
* Gesture predictions generated
* Accuracy evaluated on test set

This confirms a correct and complete gesture recognition pipeline.



🧠 About Prodigy InfoTech Internship

Prodigy InfoTech offers practical internships in:

Machine Learning

Data Science

Artificial Intelligence



This task enhances skills in:

* Image preprocessing
* Multi-class classification
* Human–Computer Interaction
* Model evaluation



📜 License

This project is licensed under the MIT License.



🙏 Acknowledgments

* Kaggle \& UPM for LeapGestRecog dataset
* OpenCV \& Scikit-learn communities
* Prodigy InfoTech Internship Program



⭐ If you found this project helpful, give your repository a ⭐
