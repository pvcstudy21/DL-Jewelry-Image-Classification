# DL-Jewelry-Image-Classification

Project Description: In this project, I developed a deep learning solution to classify images of various types of jewelry, utilizing two distinct models. The primary focus was on creating a custom Convolutional Neural Network (CNN) model, while the second approach involved leveraging the pre-trained VGG16 model to explore transfer learning for jewelry classification.

Model 1: Custom CNN Model
The first model is a custom-built CNN designed to capture and learn the unique visual features of different types of jewelry. It consists of multiple convolutional and pooling layers, followed by dense (fully connected) layers. The model was compiled with the Adam optimizer, sparse categorical cross-entropy (SCCE) as the loss function, and accuracy as the primary performance metric. After training, this model predicts the class of a given sample image and provides the corresponding accuracy.

Model 2: VGG16 Transfer Learning Model
The second model utilizes VGG16, a well-known pre-trained CNN architecture, applied through transfer learning. By fine-tuning VGG16 on the jewelry dataset, this model leverages pre-existing knowledge from large-scale image datasets, which enables more efficient training and improved accuracy for jewelry classification. VGG16’s deeper architecture allows it to capture more intricate details and features from jewelry images, making it well-suited for this classification task.

Training and Evaluation:
After training both models, their performances were evaluated based on accuracy. The models were tested on sample jewelry images to showcase their ability to accurately classify various jewelry types. The project highlights the effectiveness of both a custom CNN and a transfer learning approach, comparing their strengths in distinguishing between jewelry classes.
