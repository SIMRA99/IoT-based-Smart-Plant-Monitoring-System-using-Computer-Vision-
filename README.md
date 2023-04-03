# IoT-based-Smart-Plant-Monitoring-System-using-Computer-Vision-

The responsibility of controlling and managing the plant growth from early stage to mature stage involves monitoring and identification of plant diseases, controlled irrigation and controlled use of fertilizers and pesticides. The proposed project explores the technology of wireless sensors for remote real time monitoring of vital gardening parameters like humidity, environmental temperature and moisture content of the soil. It employs the technique of image processing for vision based automatic disease detection on plant leaves. Image processing is a method used to enhance and extract information from an image. It has been used for various application and shows great result. Convolutional neural network is a brain of deep learning which is used for visual imagery. The combination of image processing in Convolutional neural network helps in enhancing the existing system of image processing and classification. This project aims at using CNN in image processing to classify plant disease and how it can help recognize these diseases more accurately. The system measures the moisture of the soil, temperature and humidity, sends data to the raspberry pi and waters the plant  automatically based on the amount of water required for the plant. The system then uses a raspberry pi cam to capture images of plants, use the webapp CNN model to detect the disease and then spray required pesticide on the plant to stop the spread of the disease to other plants. The system informs the user all the changes and updates on the webapp/mobile app. The system is an overall monitoring system for the garden. 
Steps
Detect moisture content , humidity and temperature
Update on the app
Water plants according to the need of the plant
Cam captures images and sends to the app to detect the disease using the model
The detected disease is informed on the app 
The required pesticide is sprayed on the plant




The project uses  PlantVillage Disease dataset. 
The dataset has labelled plants images which are diseased and healthy along with their labels. It has 38 classes of dataset which is used to train the model. Around 80 percent of the images are used for training and 20 percent for testing the system. The plant folders are:
Pepper bell  Bacterial spot
Pepper  bell healthy
Potato Early blight
Potato Late blight
Potato healthy
Tomato Bacterial spot
Tomato Early blight
Tomato_Late_blight
Tomato_Leaf_Mold
Tomato_Septoria_leaf_spot
Tomato_Spider_mites_Two_spotted_spider_mite
Tomato__Target_Spot
Tomato__Tomato_YellowLeaf__Curl_Virus
Tomato__Tomato_mosaic_virus 
Tomato_healthy


The goal of this part is to recognize the disease in a plant and inform the gardener through  a webapp using Raspberry Pi NoIR Camera Board v2 for taking photos.

![image](https://user-images.githubusercontent.com/57862480/229548738-9c9cdf01-4853-4dec-9a92-5ef2b41a2ce6.png)

![image](https://user-images.githubusercontent.com/57862480/229548862-61905dfd-af36-415a-97b1-c50770d37a61.png)

![image](https://user-images.githubusercontent.com/57862480/229548967-e8f4df0e-7803-4f99-bb0b-2ea36744f1ed.png)



system disgram:
![image](https://user-images.githubusercontent.com/57862480/229559795-419b5133-82fd-486e-bafb-ab6ba00943c2.png)

