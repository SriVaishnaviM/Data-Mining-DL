# Crop Disease Prediction 

The major agricultural products in India are rice, wheat, pulses, and spices. As our population is increasing rapidly the demand for agriculture products also increasing alarmingly. A huge amount of data is incremented from various field of agriculture. Analysis of this data helps in predicting the crop yield, analyzing soil quality, predicting disease in a plant, and how meteorological factor affects crop productivity. 

Crop protection plays a vital role in maintaining agriculture product. Pathogen, pest, weed, and animals are responsible for the productivity loss in agriculture product. Machine learning techniques like Random Forest, Bayesian Network, Decision Tree, Support Vector Machine etc, help in automatic detection of plant disease from visual symptoms in the plant. A survey of different existing machine learning techniques used for plant disease prediction was presented in this project. Automatic detection of disease in plant helps in early diagnosis and prevention of disease which leads to an increase in agriculture productivity.

## Steps to run the project:

1. To run project double click on ‘run.bat’ file.

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/3872a67e-fd27-4811-b4de-69124f339a90)

  In above screen click on ‘Upload Crop Disease Dataset’ button to upload dataset images

  Select and upload ‘CropDiseaseDataset’ folder and then click on ‘SelectFolder’ button to load dataset and to get below screen


2. In the screen dataset is loaded and now click on ‘Image Processing & Normalization’ button to read all images and then process images to normalize by converting each image pixel value between 0 and 1 and for that normalization we will divide image pixels with 255 and then get value as 0 or 1 as all images pixel value will be between 0 to 255.

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/c20772b9-3f21-4adc-b49c-6c6dac5f6f9a)

3. In the screen below after applying normalization we are just displaying one random image from dataset to check whether images loaded and process properly or not and now you close above image to get below screen

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/15878a4a-4bc4-459b-a62d-c4c77b7294e2)

4. All images process successfully and now dataset images are ready and now click on ‘Build Crop Disease Recognition Model’ button to build CNN model

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/ca49ce84-841e-41dd-9d80-00ba8e3fc423)

5. The result below shows the CNN model built and accuracy is displayed.

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/787258ea-768f-4f5e-96bc-b64323848f4b)

6. We have used CONV2D, MAXPOOLING, FLATTEN and DENSE layer to build crop disease recognition model and RELU details you can see in code. Now model is ready and now click on ‘Upload Test Image & Predict Disease’ button to upload any test image and then application will predict disease or healthy from that image

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/53149436-e6eb-4a3f-9509-93ef261f02f4)

7. Select and upload an image file and then click on ‘Open’ button to get below prediction result. In the example below, image "1.jpg" is selected and potato leaf predicted as healthy.

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/1283b0ad-316d-43d7-9ab4-91e76ed960eb)

8. In the graph x-axis represents epoch/iterations and y-axis represents accuracy/loss and green line represents accuracy and blue line represents loss and from above graph we can see with each increasing iteration accuracy is getting better and better and loss getting decrease

![image](https://github.com/SriVaishnaviM/Data-Mining-DL/assets/145308407/5ba1fb99-b215-4050-86f1-0bac70b8013e)





   








