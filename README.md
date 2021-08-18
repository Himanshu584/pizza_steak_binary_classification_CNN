# pizza_steak_binary_classification_CNN

This dataset is present in preprocessed form arranged in the following file structure:


           ` pizza_steak <- top level folder
            └───train <- training images
            │   └───pizza
            │   │   │   1008104.jpg
            │   │   │   1638227.jpg
            │   │   │   ...      
            │   └───steak
            │       │   1000205.jpg
            │       │   1647351.jpg
            │       │   ...
            │   
            └───test <- testing images
            │   └───pizza
            │   │   │   1001116.jpg
            │   │   │   1507019.jpg
            │   │   │   ...      
            │   └───steak
            │       │   100274.jpg
            │       │   1653815.jpg
            │       │   ...`



you can doenload the dataset directly into your notebook using the following command : 
            `!wget https://storage.googleapis.com/ztm_tf_course/food_vision/pizza_steak.zip`
            
This image classification model predicts weither a given image is of a pizza or a steak .

image to be predicted should be converted to tensor of shape (224,224,3) and an extra dimention needs to be added in 0th axis. it can be done by using expanddims in tensorflow .

overall model_1 performs great with accuracy of appx 89%. 
