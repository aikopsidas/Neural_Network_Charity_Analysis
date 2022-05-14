# NNCA(Alphabet Soup)

## Overview:
 With our knowledge of machine learning and neural networks we used features in the CSV that hold the over 34,000 organizations that have received funding form Alphabet Soup over the years and created a binary classifier that will predicted if applicants will be successful if funded by Alphabet Soup. 

## Results:
### Data Preprocessing
- Target 
  - Selected target was if the business was considered successful or not (IS_SUCCESSFUL column).
 
 - Features
   - Some features of our dataset were the Application Type, Classification, and Affiliation. Below is an image of all the data. 

 ![](https://github.com/aikopsidas/Pewlett-Hackard-Analysis/blob/283fab3fbf227aa4384010980f0d4fec71b2ccaa/Data/total_set_to_retire.PNG)
 
 - Removed Data
   - The EIN and Names were removed as these columns would hold no value as it pertains to if the business was successful or not.   

 ![](https://github.com/aikopsidas/Pewlett-Hackard-Analysis/blob/283fab3fbf227aa4384010980f0d4fec71b2ccaa/Data/total_set_to_retire.PNG)
 
 ### Compiling, Training, and Evaluating the Model
 
 - We used 3 and 4 layers (the 4 layer model got us the closest) along with a combination of relu and sigmoid activations. 


 - Our goal was 75%, which we were not able to attain, but did come very close. 
 
  ![](https://github.com/aikopsidas/Pewlett-Hackard-Analysis/blob/283fab3fbf227aa4384010980f0d4fec71b2ccaa/Data/total_set_to_retire.PNG)
 
 -  For the most successful model had 4 layers; in which we increased the number of each by 30 from the previous attempt. As seen above we were able to reach an accuracy of 72%

 ![](https://github.com/aikopsidas/Pewlett-Hackard-Analysis/blob/283fab3fbf227aa4384010980f0d4fec71b2ccaa/Data/total_set_to_retire.PNG)
 
 
 ## Summary
 We were close and could get even closer if we ran a few more models I believe by possibly increasing the neurons add adding another layer. I would recommend a bit more education on Neural Network and Machine Learning as well.

