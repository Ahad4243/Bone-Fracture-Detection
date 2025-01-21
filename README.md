# Bone-Fracture-Detection
This project employs convolutional neural networks (CNNs) to classify fractures in the elbow, hand, and shoulder using the MURA dataset. By automating fracture detection with high accuracy, it streamlines musculoskeletal radiograph analysis, supporting efficient and reliable medical diagnosis.
Table of Contents
Features
Technologies Used
Installation
Usage
Dataset
Results
Contribution
License
Features
Automated detection of bone fractures.
Classification of fractures across multiple bone types: elbow, hand, and shoulder.
Visualizes model performance metrics for deeper insights.
Technologies Used
Python: Core programming language.
TensorFlow/Keras: For deep learning and model development.
OpenCV: For image preprocessing and manipulation.
Matplotlib & Seaborn: For data visualization and performance metrics.
Installation
Clone the repository:
bash
Copy
Edit
git clone https://github.com/Bilal976r/bone-fracture-detection.git  
cd bone-fracture-detection  
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt  
Usage
Prepare the dataset:
Place the MURA dataset in the directory specified in the code.

Train the model:
Run the training scripts to start training:

bash
Copy
Edit
python training_parts.py  
python training_fracture.py  
Evaluate the model:
Assess the model’s accuracy with:

bash
Copy
Edit
python prediction_test.py  
python predictions.py  
Launch the application:
Start the GUI for fracture detection:

bash
Copy
Edit
python mainGUI.py  
Dataset
This project uses the MURA dataset, a comprehensive collection of musculoskeletal radiographs. It must be downloaded separately from Stanford ML Group's website.

Results
Performance metrics such as accuracy and confusion matrices are generated post-training.
Visualizations can be customized using provided scripts for detailed analysis.
Contribution
Contributions are highly encouraged!

Open issues for bugs or suggestions.
Submit feature requests or make pull requests to enhance the project.
License
This project is open-source and distributed under the MIT License.
