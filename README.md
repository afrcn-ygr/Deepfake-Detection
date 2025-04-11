# Deepfake-Detection

Deepfakes, or AI-generated synthetic media, are digitally generated or altered images or videos created using deep learning techniques – a subset of machine learning techniques – particularly Generative Adversarial Networks (GANs). These manipulated media forms have rapidly advanced in quality and accessibility, making it increasingly sophisticated and difficult to distinguish authentic artifacts from synthetic forgeries. As a result, they have sparked growing concerns across multiple fields, from misinformation and political propaganda to identity theft, privacy violations, and the erosion of digital trust. The societal implications are profound, with potential threats to public safety, national security, and the credibility of media corporations. 

In response to these concerns, this research investigates the application of machine learning for deepfake detection, focusing on the use of transfer learning with pre-rained models. The experiment utilizes the **FaceForensics++** dataset, a widely adopted benchmark in the field, which contains real and manipulated face videos and images subjected to various levels of compression. From this dataset, preprocessed still frames were extracted and used to train a lightweight **MobileNetV2** model – a computationally efficient architecture suitable for low-resource environments. 

The model was trained and evaluated over multiple epochs, yielding moderate performance. Training accuracy gradually improved, but validation accuracy remained relatively low, revealing issues of overfitting and significant class imbalances. These limitations underscore the challenge of distinguishing between subtle deepfake creations and genuine features using image-based methods alone. Nevertheless, the findings highlight the viability of transfer learning as a foundational approach in this domain. They also pave the way for further research focused on improving generalization, bias mitigation, and enhancing adversarial robustness in the ongoing arms race between deepfake generators and detectors.
