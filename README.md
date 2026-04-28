# OC_P8_Cloud_computing
Develop scripts in PySpark and use the AWS cloud to take advantage of a Big Data architecture (EMR, S3, IAM)
Your company, a very young startup, aims to provide innovative solutions for fruit harvesting by enabling species-specific treatments through the development of intelligent harvesting robots. For the data scientist, that means to establish an initial version of the fruit image classification engine and enable the construction of an initial version of the necessary Big Data architecture.

Your task is therefore to complete the processing pipeline. There is no need to train a model at this stage. The key is to lay the groundwork for the processing steps that will be needed when we scale up in terms of data volume.

You must take into account in your development that the volume of data will increase very rapidly after the delivery of this project. You will therefore continue to develop scripts in PySpark and use the AWS cloud to take advantage of a Big Data architecture (EMR, S3, IAM).
You must demonstrate the setup of a working EMR instance and provide a step-by-step explanation of the PySpark script. 
You have to complete it with a process for broadcasting TensorFlow model weights across clusters. You may refer to the article “Distributed model inference using TensorFlow Keras” available in the resources.
You must demonstrate PCA-type dimension reduction step in PySpark 
You must comply with GDPR requirements: in this context, ensure your setup uses servers located within the European Union 
Your critical feedback on this solution will also be valuable before deciding to roll it out.

Implementing an EMR-type Big Data architecture will incur costs. You should therefore ensure that the EMR instance remains operational only for testing and demos. This cost, which should remain below 10 euros with reasonable use, is your responsibility. Using a local server to update the PySpark script, while limiting the use of the EMR server to implementation and testing, can significantly reduce this cost.

Identify the cloud tools needed to set up a Big Data environment that complies with current GDPR regulations. 
Upload the source files and the transformed files to a cloud storage space that complies with GDPR regulations.
Execute the scripts using machines in the cloud.
Create a script that allows program outputs to be written directly to the cloud storage space.

Identify the critical processing steps during a scale-up in terms of data volume.
Ensure that data processing complies with the GDPR. As part of this project: data is stored, and processing is performed, on servers located within the European Union
Develop scripts based on Spark.
Ensure that the entire processing chain is executed in the cloud.

Data is taken from the public set https://www.kaggle.com/datasets/moltean/fruits.
