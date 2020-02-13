### Kannada MNIST Classification with Deep Learning (Custom Convolutional Neural Network) 
<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network
Application        : Image Recognition, Image Classification
</pre>

### Description
<pre>
Kannada is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers and is written using the Kannada script.
1. Detected 10 Kannada (Kannada is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers) digits from images with Custom Convolutional Neural Network.
2. Built a simple custom convolutional neural network with few 2D convolutional, Maxpool and 1 dense layer with around 888K trainable params.
3. After 27 training iterations, attained testing accuracy of 97.70% and loss 0.03 on 60K (12MB+) OCR image dataset.
</pre>

#### Code
<pre>
GitHub Link      : <a href=https://github.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning>Kannada MNIST Classification with Deep Learning (GitHub)</a>
GitLab Link      : <a href=https://gitlab.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning>Kannada MNIST Classification with Deep Learning (GitLab)</a>
Kaggle Notebook  : <a href=https://www.kaggle.com/anjanatiha/kannada-mnist-classification-with-deep-learning>Kannada MNIST Classification with Deep Learning</a>
Portfolio        : <a href=https://anjanatiha.wixsite.com/website>Anjana Tiha's Portfolio</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Kannada MNIST
Dataset Link     : <a href=https://www.kaggle.com/c/Kannada-MNIST>Kannada-MNIST (Kaggle)</a>
                 : <a href=https://github.com/vinayprabhu/Kannada_MNIST (GitHub Original Dataset)</a>
                 
Original Paper   : <a href=https://arxiv.org/abs/1908.01242>Kannada-MNIST: A new handwritten digits dataset for the Kannada language</a> 
                   Authors: Vinay Uday Prabhu 
</pre>

### Dataset Details
<pre>
Dataset Name            : Kannada MNIST
Number of Class         : 10
</pre>

| Dataset Subtype | Number of Image | Size of Images (GB/Gigabyte) |
| :-------------- | --------------: | ---------------------------: |
| **Total**       | 40,000          | 12 MB                        |
| **Training**    | 34,000          | 10.2 MB                      |
| **Validation**  | 6,000           | 1.8 MB                       |
| **Testing**     | 44,004          |                       |


### Model and Training Prameters
| Current Parameters   | Value                                                       |
| :------------------- | ----------------------------------------------------------: |
| **Base Model**       | Custom CNN                                                  |
| **Optimizers**       | Adam                                                        |
| **Loss Function**    | Categorical Crossentropy                                    |
| **Learning Rate**    | 0.0001                                                      |
| **Batch Size**       | 128                                                         |                                     
| **Number of Epochs** | 27                                                          |
| **Training Time**    | 9 min                                                       |


### Model Performance Metrics (Prediction/ Recognition / Classification)
| Dataset              | Training       | Validation    | Test      |                                 
| :------------------- | -------------: | ------------: | --------: |
| **Accuracy**         | 99.71%         | 98.74%        | 93.72%    |
| **Loss**             | 0.0234         | 0.0219        | ---       |
| **Precision**        | ---            | ---           | ---       |
| **Recall**           | ---            | ---           | ---       |
| **Roc-Auc**          | ---            | ---           | ---       |


### Other Experimented Model and Training Prameters
| Parameters (Experimented) | Value                                                  |
| :------------------------ | -----------------------------------------------------: |
| **Base Models**           | Custom Convolutional Neural Network wwith 888K params  |
| **Optimizers**            | Adam                                                   |
| **Loss Function**         | Categorical Crossentropy                               |
| **Learning Rate**         | 0.01, 0.001, 0.0001                                    |
| **Batch Size**            | 32, 64, 96, 128, 256                                   |                                     
| **Number of Epochs**      | 27 - 100                                               |
| **Training Time**         | 9min                                                   |


### Hardware
| Parameters (Experimented) | Value                                                  |
| :------------------------ | -----------------------------------------------------: |
| **Platform**              | Cloud/Online                                           |
| **Platform Name**         | Kaggle Notebook                                        |
| **GPU Brand**             | NVidea                                                 |
| **Model Name**            | Tesla P100-PCIE-16GB                                   |
| **Memory**                | 16 GB                                                  |
| **Number of Core**        | 2                                                      |


### Visualization
#### Class Distribution: 
<kbd>
<img src=https://github.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning/blob/master/demo/images/class-dist.png>
</kbd>

#### Model Performance: 
<kbd>
<img src=https://github.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning/blob/master/demo/report/hist.png>
</kbd>

<!--
##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/images/result.png>See More Images</a>
</kbd>

##### Confusion Matrix: 
<kbd>
<img src=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/report/CM.png alt="Confusion Matrix" width=800px height=600px>
</kbd>
-->

#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Kaggle
Libraries               : Keras
</pre>

#### Dates
<pre>
Duration                : February 2020 
Current Version         : v1.0.0.10
Last Update             : 02.12.2020
</pre>
