# Gender-Detection-with-Inception-V3  

## Dataset
In this project, i will use the CelebA dataset 

## Overall  
The dataset contains:  

   202,599 number of face images of various celebrities  
   10,177 unique identities, but names of identities are not given  
   40 binary attribute annotations per image  
   5 landmark locations  
   

## Modelling and structure
Using Inception V3 model
I am using a pretrained Inception V3 model for which I will retrain some layers and fix the first layers. I will also attach new output layers to perform the new classification task.

## Target variable
As my target variable, I only use the gender feature available in the dataset and detect if the image shows a man or a woman.

## Strategy:

*Importing libraries and reading Data*    
*Data Visualization*  
*Separating Training, Testing and Validation Data*  
*Data Augmentation*  
*Importing Inception V3 model*  
*Adding Custom Layers*  
*Create and compile final model*  
*Plotting loss functiona and accuracy through epochs*  
*Prediction on Testing Data to check accuracy*  
*Generating new predictions*  
