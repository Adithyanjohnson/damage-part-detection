# damage-part-detection
Vehicle Damage Detection using Deep Learning
Overview
This project focuses on detecting vehicle damage using deep learning techniques. Various convolutional neural network (CNN) architectures have been implemented to achieve high accuracy in damage classification. The dataset consists of labeled images of vehicles with and without damage.

Implemented Models
The following deep learning models have been implemented for vehicle damage detection:

Faster R-CNN with ResNet
Faster R-CNN with InceptionV3
Mask R-CNN
VGG-based Model
MobileNet-based Model
Dataset
The dataset includes images of vehicles categorized into:

Damaged Vehicles
Non-Damaged Vehicles
Each image is labeled for training and evaluation. The dataset is preprocessed to ensure quality and consistency.

Repository Structure
/Vehicle-Damage-Detection/
│── README.md                   # Project documentation
│── conformfeb24fasterrccnwithresnet.ipynb   # Faster R-CNN with ResNet
│── conformfeb24maskrccn.ipynb               # Mask R-CNN implementation
│── conformfebfasterrccnwithinceptionv3.ipynb # Faster R-CNN with InceptionV3
│── conformvgg19feb24.ipynb                  # VGG-based CNN model
│── mobilenettfinalfeb24.ipynb               # MobileNet-based model
│── requirements.txt              # Required dependencies
│── dataset/                      # https://github.com/Adithyanjohnson/damage-part-detection
│── results/                       # Model performance results 
Installation
To set up the project locally, follow these steps:

Clone the repository:

git clone https:
https://github.com/Adithyanjohnson/damage-part-detection
cd Vehicle-Damage-Detection
Install dependencies:

pip install -r requirements.txt
Run the Jupyter Notebooks to train and evaluate the models.

Usage
Open the .ipynb files in Google Colab or Jupyter Notebook.
Execute the cells to load the dataset, train models, and evaluate performance.
Modify hyperparameters in the notebook files as needed.
Results
Each model has been evaluated using:

Accuracy
Precision
Recall
F1-score
Performance comparisons and visualization results will be added to the results/ directory.

Future Work
Implement additional deep learning models for improved detection.
Optimize hyperparameters for better accuracy.
Integrate real-time damage detection using a web or mobile interface.
Contributors
Rohith Venugopalan
Adithyan Johnson
License
This project is licensed under the MIT License - see the LICENSE file for details.
