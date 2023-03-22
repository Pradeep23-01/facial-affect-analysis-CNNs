# Facial Emotion Identification with CNN architectures
## FER2013 dataset - https://www.kaggle.com/nicolejyt/facialexpressionrecognition (.csv file)

Deep Convolutional Neural Networks (DCNNs) and Convolutional Neural Networks (CNNs) have been successfully used for facial emotion recognition (FER) tasks.

## Task:
Facial emotion recognition is a challenging task that involves detecting and recognizing emotions from facial expressions. The process involves detecting key facial landmarks and extracting features from them, and then using a classifier to predict the emotion category.


## Implementation & Solution:
One popular CNN architecture used for FER is the **VGG16** model. Researchers have fine-tuned VGG16 for FER by retraining the model on a large dataset of facial images labeled with emotion categories. This fine-tuning process involves freezing the first few layers of the model, which are responsible for detecting low-level features like edges and textures, and retraining the later layers to learn high-level features that are specific to the FER task.

Another popular CNN architecture for FER is the **Inception-V3** model, which has been shown to outperform VGG16 on some FER benchmarks. Inception-V3 uses a more complex architecture that incorporates multiple scales of convolutional filters to capture features at different levels of abstraction.

DCNNs, which are simply CNNs with more layers, have also been used for FER tasks. For example, the DeepEmotion model is a **DCNN** architecture that has been designed specifically for FER. It uses a combination of convolutional, pooling, and fully connected layers to extract features from facial images, and achieves state-of-the-art performance on some FER benchmarks.

In summary, DCNNs and CNNs have been successfully used for FER tasks, and architectures like VGG16 and Inception-V3 have been fine-tuned for this specific application. The choice of model architecture depends on the specific FER task and the available dataset.
