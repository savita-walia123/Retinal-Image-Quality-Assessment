# Retinal-Image-Quality-Assessment
Texture based feature extraction for fundus image quality assessment to categorize images into Good and Poor classes 



FEATURES USED: 
32 (30 GLCM Texture features, Shannon Entropy and Sharpness)
Gray Level Co-occurrence Matrix (GLCM) Texture Features: The Gray Level Co-occurrence Matrix1 (GLCM) and associated texture feature calculations are image analysis techniques. Given an image composed of pixels each with an intensity (a specific gray level), the GLCM is a tabulation of how often different combinations of gray levels co-occur in an image or image section. Texture feature calculations use the contents of the GLCM to give a measure of the variation in intensity (a.k.a. image texture) at the pixel of interest. Firstly, normalized GLCM of an image is calculated, then following 5 features are calculated by varying two parameters i.e. distance and angle. Features computed from GLCM Matrix are : Energy, Correlation, Dissimilarity, Homogeneity and Contrast. 
•	5 features calculated from GLCM Matrix 1 at distance = 1, angle = 0 
•	5 features calculated from GLCM Matrix 1 at distance = 1, angle = 45
•	5 features calculated from GLCM Matrix 1 at distance = 1, angle = 90
•	5 features calculated from GLCM Matrix 1 at distance = 1, angle = 135
•	5 features calculated from GLCM Matrix 1 at distance = 3, angle = 0 
•	Total = 30 features 
Sharpness: for computing sharpness of the image, Laplacian variable is used.
Shannon Entropy: Shannon entropy is a function of the logarithm of the number of states of a system; this logarithm is equal to the number of bits required to uniquely identify the state of the system
