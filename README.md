# CEDNet-MSI
Contextual Encoder-Decoder Network for Visual Saliency Prediction
Alexander Kroner
Mario Sendena, 
Kurt Driessen
Rainer Goebel

Abstract
Predicting salient regions in natural images requires the detection of objects that are present in a
scene. To develop robust representations for this challenging task, high-level visual features at
multiple spatial scales must be extracted and augmented with contextual information. However,
existing models aimed at explaining human fixation maps do not incorporate such a mechanism
explicitly. Here we propose an approach based on a convolutional neural network pre-trained on
a large-scale image classification task. The architecture forms an encoder-decoder structure and
includes a module with multiple convolutional layers at different dilation rates to capture multiscale features in parallel. Moreover, we combine the resulting representations with global scene
information for accurately predicting visual saliency. Our model achieves competitive results on
two public saliency benchmarks and we demonstrate the effectiveness of the suggested approach
on selected examples. The network is based on a lightweight image classification backbone and
hence presents a suitable choice for applications with limited computational resources to estimate
human fixations across complex natural scenes.
