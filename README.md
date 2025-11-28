**🚦 Intelligent Traffic Sign Recognition Project** 
This project focuses on building an intelligent traffic sign recognition system using deep learning. The main goal of this system is to automatically identify different traffic signs from images and assist in improving road safety. The model is trained using a labeled dataset and tested for accuracy under different lighting and traffic conditions. This project demonstrates the real-world application of artificial intelligence in transportation systems.

 Project Overview
This project is designed to develop a computer vision system that can automatically identify different traffic signs from road images. The system is built using deep learning techniques and is focused on improving driver awareness and traffic safety. This project also explores how artificial intelligence can be applied in real-world transportation systems

🌟 Key Features
Automatic traffic sign identification from images
Image preprocessing and noise reduction
Deep learning-based classification
Confidence score for predictions
Real-time image testing option
User-friendly interface for predictions
Performance evaluation using accuracy metric

Model Architecture
The deep learning model is developed using multiple convolution layers to extract visual features from traffic sign images. Pooling layers are used to reduce dimensional complexity. The extracted features are converted into numerical form using a flatten layer and passed through fully connected dense layers for final classification. Dropout layers are added to prevent overfitting and improve generalization.

**Training Details**
Epochs: 15
Optimizer: Adam
Loss Function: SparseCategoricalCrossentropy
Metrics: Accuracy
Test Accuracy: 53.68%

Hyperparameter Tuning
Hyperparameter tuning was performed using RandomSearch to maximize validation accuracy.

Best Hyperparameters Found:
Parameter	Value
Filters	32, 96, 192
Kernel Size	5, 3
Dropout Rate	0.4
Dense Units	256
Learning Rate	0.001
Epochs	30 (with early stopping)
Insight: The tuned model achieved 14% Test Accuracy, indicating a need for more data or further optimization.
Streamlit Application
The Road Sign Prediction App allows users to:

Select any road sign image from the TEST folder.
Automatically detect the class ID from the folder name.
Display the class name and optional confidence score using the trained model.

Future Enhancements
Further model tuning to improve accuracy.
Multilingual voice predictions for traffic signs.
Real-time video detection for autonomous vehicles.

🔗 Technologies Used
Python
OpenCV
TensorFlow
Keras
Streamlit
NumPy
Matplotlib


Conclusion
This project successfully demonstrates the application of deep learning for traffic sign recognition. The system helps in understanding real-time AI applications in transportation. Future improvements can include larger datasets and advanced neural network architecture
