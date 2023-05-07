# Detection-of-COVID-19-Infection-using-Chest-X-Ray-Image-Through-Transfer-Learning-and-DCNN
## Description of the project

An intriguing illness called Covid-19 first surfaced in the Covid family in December 2019, as a result of a recently identified virus. It is an unstoppable illness that mostly affects the human body’s lung region and has symptoms similar to those of typical flu, which makes it challenging to recognize. It quickly spread over the world, which has brought up dangerous challenges ever since it started. Such test arrangements should not only be technically solid but also realistic and user-friendly as governments seek to expand testing. Recent X-rays and CT scans have revealed noteworthy highlights that emphasize the severity of Covid in the lungs. Since radiographs like X-rays and CT scans are practical and frequently available at general medical offices, trauma centres, and even in rural hospitals, they could be used for quick identification of potential lung infections brought on by COVID-19. Advanced artificial intelligence (AI) in sending a profound learning-based clinical area is staying fantastic to deal with a huge amount of data with accurate and rapid results in the clinical image to assess illnesses even more precisely and effectively with extra support in far-off places

The proposed model is to use a combination of Deep Learning Models and other classifiers to improve the accuracy of the prediction. The dataset is analyzed and the features are extracted using transfer learning. Sub-dataset is created and the dataset is trained using the different classifiers. It is then tested using a different part of the dataset. Finally, the model can differentiate between covid-19 affected images and healthy images.

Download the Dataset from this link : http://medicalsegmentation.com/covid19/ 

In this regard, our contributions in this paper are: 

• Developed some models that uses a dense convolutional neural network with ImageNet as the local feature extraction and DenseNet, ResNet, VGG16 and InceptionV3 as the classifier along with the transfer learning method. 

  – Processed a dataset that manages to contain more than 15000 images and minimize the training time of these images.     
  – Intensity Normalization and Data Augmentation techniques such as rescaling, shifts, rotations shears, and zooms are used to avoid overfitting problems. 
  
• Improve the performance through enhancing the accuracy and minimizing the loss of our models. This is achieved by reducing the pooling layers and simplifying the ReLu activation function.

