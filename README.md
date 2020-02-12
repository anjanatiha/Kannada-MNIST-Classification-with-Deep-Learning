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
GitHub Link      : <a href=https://github.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning(GitHub)</a>
GitLab Link      : <a href=https://gitlab.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning(GitLab)</a>
Kaggle Notebook  : <a href=https://www.kaggle.com/anjanatiha/kannada-mnist-classification-with-deep-learning</a>
Portfolio        : <a href=https://anjanatiha.wixsite.com/website>Anjana Tiha's Portfolio</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Kannada MNIST
Dataset Link     : <a href=https://www.kaggle.com/c/Kannada-MNIST>Kannada-MNIST (Kaggle)</a>
                 : <a href=https://github.com/vinayprabhu/Kannada_MNIST (GitHub Original Dataset)</a>
                 
Original Paper   : <a href=https://arxiv.org/abs/1908.01242>Kannada-MNIST: A new handwritten digits dataset for the Kannada language</a> 
                   Authors: Vinay Uday Prabhu 
                   JAMA (The Journal of the American Medical Association)
                   <cite>Ehteshami Bejnordi B, Veta M, Johannes van Diest P, et al. Diagnostic Assessment of Deep Learning Algorithms for Detection of Lymph Node Metastases in Women With Breast Cancer. JAMA. 2017;318(22):2199–2210. doi:10.1001/jama.2017.14585</cite>
</pre>

### Dataset Details
<pre>
Dataset Name            : Kannada MNIST
Number of Class         : 10
</pre>

| Dataset Subtype | Number of Image | Size of Images (GB/Gigabyte) |
| :-------------- | --------------: | ---------------------------: |
| **Total**       | 40,000          |                       |
| **Training**    | 34,000          |                       |
| **Validation**  | 6,000           |                       |
| **Testing**     | 44,004          |                       |


### Model and Training Prameters
| Current Parameters   | Value                                                       |
| :------------------- | ----------------------------------------------------------: |
| **Base Model**       | Custom CNN                                                |
| **Optimizers**       | Adam                                                        |
| **Loss Function**    | Categorical Crossentropy                                    |
| **Learning Rate**    | 0.0001                                                      |
| **Batch Size**       | 128                                                         |                                     
| **Number of Epochs** | 27                                                           |
| **Training Time**    | 4.5 hour (270 min)                                          |


### Model Performance Metrics (Prediction/ Recognition / Classification)
| Dataset              | Training       | Validation    | Test      |                                 
| :------------------- | -------------: | ------------: | --------: |
| **Accuracy**         | 99.71%         | 98.74%        | 93.72%    |
| **Loss**             | 0.0234         | 0.0219        | 0.30      |
| **Precision**        | ---            | ---           | 89.02%    |
| **Recall**           | ---            | ---           | 90.80%    |
| **Roc-Auc**          | ---            | ---           | 91.59%    |


### Other Experimented Model and Training Prameters
| Parameters (Experimented) | Value                                                  |
| :------------------------ | -----------------------------------------------------: |
| **Base Models**           | NashNet(NashNetLarge, NashNetMobile), InceptionV3      |
| **Optimizers**            | Adam, SGD                                              |
| **Loss Function**         | Categorical Crossentropy, Binary Crossentropy          |
| **Learning Rate**         | 0.0001, 0.00001, 0.000001, 0.0000001                   |
| **Batch Size**            | 16, 32, 64, 128, 256                                   |                                     
| **Number of Epochs**      | 2, 4, 6, 10, 30, 50, 100                               |
| **Training Time**         | 4.5 hour (270 min), 1 day (24 hours), 2 days (24 hours)|


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

#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Anaconda
Libraries               : Keras, TensorFlow, Inception, ImageNet
</pre>

#### Dates
<pre>
Duration                : November 2018 - Current
Current Version         : v1.0.0.3
Last Update             : 12.24.2018
</pre>
