🌱 Plant Pathogen Classification Using a Convolutional Neural Network

A deep learning image classification project using TensorFlow/Keras to identify plant pathogens across 7 classes from a dataset of approximately 40,000 images.

Developed as part of a research internship at the Miami Dade College School of Science, the project explored how convolutional neural networks can be applied to agricultural image classification and evaluated the model using accuracy, precision, recall, and a confusion matrix.

📌 Project Overview

Plant diseases can significantly affect crop health and agricultural productivity. Image classification provides a way to automatically recognize visual patterns associated with different plant conditions.

For this project, our team developed a Convolutional Neural Network (CNN) capable of learning visual features directly from plant images and classifying them into one of seven categories.

The project involved the complete machine-learning workflow:

Image Dataset → Preprocessing → Data Augmentation → CNN Training → Prediction → Model Evaluation

📊 Dataset

The model was trained using approximately:

40,000 plant images

7 classification categories

80% training / 20% validation split

The dataset contained labeled images that allowed the CNN to learn visual patterns associated with each class.

🧠 Why a Convolutional Neural Network?

CNNs are particularly effective for image classification because convolutional layers learn spatial features directly from images.

Instead of manually defining which visual characteristics indicate a particular plant condition, the network learns useful features during training.

Earlier layers can respond to simpler visual structures such as:

Edges

Colors

Textures

Shapes

Deeper layers can combine these learned features into more complex representations useful for distinguishing between classes.

⚙️ Machine Learning Pipeline

1. Image Preprocessing

Images were prepared before being passed into the neural network so that the model received data in a consistent format.

2. Data Augmentation

Image augmentation was used during training to introduce variation into the dataset.

This helps the network learn more general visual patterns rather than relying too heavily on the exact appearance of individual training images.

3. CNN Training

The processed images were passed through the convolutional neural network.

During training, the model iteratively adjusted its parameters to reduce classification error and improve its ability to correctly identify unseen images.

4. Validation

Approximately 20% of the dataset was reserved for validation.

This allowed us to evaluate how well the model generalized to images it had not directly trained on.

5. Model Evaluation

Model performance was evaluated using:

Accuracy

Precision

Recall

Confusion Matrix

The confusion matrix was especially useful for identifying which classes the network classified reliably and which classes it was more likely to confuse.

📈 Results

The CNN achieved approximately 90% validation accuracy after training.

Rather than relying only on overall accuracy, we also examined precision, recall, and the confusion matrix to better understand performance across the seven classes.

This helped reveal that a model's overall accuracy does not necessarily tell the complete story—individual classes may perform differently depending on the available training data and similarities between images.

🛠️ Technologies

Language: Python

Machine Learning

Libraries: TensorFlow, Keras, NumPy, Matplotlib, scikit-learn

Environment: Jupyter Notebook

📁 Repository Structure

Convolutional-Neural-Network/
│
├── final one.ipynb
│   └── CNN preprocessing, training, evaluation, and visualization
│
├── assessingslate_48x36.pdf
│   └── Research poster presenting the project and results
│
└── README.md
    └── Project documentation

🔬 Research Experience

This project was developed during a research internship at the Miami Dade College School of Science as part of a five-person team.

Beyond training the model, the project involved analyzing its performance and presenting the research findings at a symposium.

The experience provided hands-on exposure to:

Supervised machine learning

Computer vision

Neural network architecture

Image preprocessing

Data augmentation

Model training and validation

Classification metrics

Scientific communication

💡 What I Learned

This project was my introduction to applying machine learning to a large image dataset.

One of the biggest lessons was that building a useful ML model involves much more than obtaining a high accuracy score. Understanding the dataset, controlling overfitting, evaluating individual classes, and interpreting model errors are all important parts of determining whether a model is actually learning useful patterns.

The project also introduced me to how computer vision can be applied to scientific research and real world problems, which motivated me to continue studying machine learning and software engineering.

🚀 Future Improvements

Potential extensions of the project include:

Experimenting with deeper CNN architectures

Comparing the custom CNN with transfer-learning models

Improving regularization to reduce overfitting

Expanding the training dataset

Performing additional hyperparameter tuning

Evaluating performance on completely independent test images

Building an interface where users can upload an image and receive a model prediction

📄 Research Poster

The repository also includes the research poster used to present the project's methodology, evaluation, and results:

assessingslate_48x36.pdf

👨‍💻 Author

Carlos Lage

Computer Science — University of Florida

Interested in Software Engineering, Machine Learning, Computer Vision, and AI.
