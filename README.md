# Crowd_Counting
Crowd counting is a technique to estimate or count the number of people present in an Image. 

## Methods used for crowd countin:-

1. Detection Based Methods:-  

A window like detector is used to faces in an Image and count them. This method is not much successful because it requires well trained classifiers which can detect low leve features as well in an Image.  

2. Regression based methods:-  

These methods extract patches from the Image and then for every individual patch, we try to extract low level features.  
This methods directly map from the image features to the number of people, without explicit object detection.  

3. CNN based methods:-  

The most reliable networks are CNN, In this I have used CSRNet to count the crowd in an Image.  

4. Density based methods:-  
The concept of an object density map, where the integral (sum) over any subregion equals the number of objects in that region. The density values are estimated from low-level features, thus sharing the advantages of general regression-based methods, while also maintaining location information. 


## Reference Paper:-

1. https://arxiv.org/pdf/1705.10118.pdf  
