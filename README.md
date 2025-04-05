# Model-quantization-and-analysis
 Analysis of efficiency metrics of computer vision models before and after applying post-training quantization using TensorFlow.
1-Developed AlexNet and MobileNetV2 models for image classification using the Rock-Paper-Scissors dataset. 
2-Trained the AlexNet model from scratch, but fine-tune the MobileNetV2 model (using ImageNet weights) by training only the top 10 layers along with custom classifier layers corresponding to the number of classes in the given dataset. 
Followed standard deep learning model development practices such as image rescaling, train/validation/test set split ratios, number of epochs, optimizers, evaluation metrics, etc.
3-compare the following efficiency metrics for both models:
             Number of parameters 
                  # Model size
                  # Number of activations 
                  # Number of FLOPS 
                  # Inference time
                  # Accuracy
 4-Converted both models to TFLite format and compared the model sizes before and after conversion.
 5-Converted both models to TFLite format and compare the model sizes before and after conversion.
