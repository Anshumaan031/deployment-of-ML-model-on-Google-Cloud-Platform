# deployment-of-ML-model-on-Google-Cloud-Platform
In this example a XGBoost model is implemented and deployed on the Google Cloud Platform</br >
To start a Jupyter Notebook Instance: </br >
1. In the Cloud Console, go to Navigation menu > AI Platform > Notebooks </br >
2. On the Notebook instances page, click NEW INSTANCE. </br >
3. In the Customize instance menu, select TensorFlow Enterprise and choose the version of TensorFlow Enterprise 2.3 (with LTS) > Without GPUs. </br >
4. In the New notebook instance dialog, for Region, select us-central1, for Zone, select a zone within the selected region, leave all other fields with their default options, and click CREATE. </br >
5. To install XGBoost on out TF instance, type in the following command in terminal, and press Enter. </br >
pip3 install xgboost --user </br >
6.To clone the training-data-analyst repo, type in the following command, and press Enter.</br >
git clone https://github.com/GoogleCloudPlatform/training-data-analyst</br >
![Capture2](https://user-images.githubusercontent.com/67821036/137092263-750b94ef-bb74-41dc-9d1c-4b6ed29fa4cc.PNG)
![Capture3](https://user-images.githubusercontent.com/67821036/137092282-896bf603-33a5-4bb6-9c27-33c6d4d59b09.PNG)
![Capture4](https://user-images.githubusercontent.com/67821036/137092293-6555b5d7-6bae-41a5-98fc-27c0c96ddec4.PNG)
