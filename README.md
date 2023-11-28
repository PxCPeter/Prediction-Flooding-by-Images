# Prediction-Flooding-by-Images
Task Description
The goal of this task is to retrieve all images which show direct evidence of a flooding event from social media streams, independently of a particular event. The objective is to design a system/algorithm that given any collection of multimedia images and their metadata (e.g., YFCC100M, Twitter, Wikipedia, news articles) is able to identify those images that are related to a flooding event. Please note, that only those images which convey an evidence of a flooding event will be considered as True Positives. Specifically, we define images showing unexpected high water levels in industrial, residential, commercial and agricultural areas“ as images providing evidence of a flooding event. The main challenges of this task are the proper discrimination of the water level in different areas (e.g., images showing a lake vs. showing high water at a street) as well as the consideration of different types of flooding events (e.g., coastal flooding, river flooding, pluvial flooding).
![image](https://github.com/PxCPeter/Prediction-Flooding-by-Images/assets/109299973/efd33616-9821-4ee1-958b-cbca85badf5b)


We thank
MediaEval 2017 and Pham Quang Nhat Minh

What data is provided?
The images and corresponding metadata for this task have been extracted from YFCC100M-Dataset. These images are shared under Creative Commons licenses that allow their redistribution. All images are sampled in a way such that there is only one image per user in the dataset. Images will be labeled with the two classes (1) Showing evidence of a flooding event and (2) Showing no evidence of a flooding event. In addition to the images, we will also supply participants with additional metadata information. We will release a development set of 5280 images. Precomputed features will be provided along with the dataset to help teams from different communities to participate to the task.

Building Model Required:

Text -> Accept

Text + Image -> Accept

Image only -> Not Accept
