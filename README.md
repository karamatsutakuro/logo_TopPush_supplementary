# supplementary
TopPush experiment using feature space different from bitmap.  
The industry folder summarizes the rankings of each type of business.  
The lambda folder summarizes the rankings of all industries of a particular lambda.

1. RGB_histogram  
Classify each pixel according to the intensity of RGB value and treat its histogram as feature vectors.  
1000 dimensional vector.

2. gray_scale_HOG  
Make favicon grayscale and treat its HOG features as feature vectors.  
144 dimensional vector.

3. RGB_channel_HOG  
Take HOG feature value with each value of RGB and treat it as feature vectors.  
432 dimensional vector.

4. average_color  
Calculate the RGB average color of favicon and treat it as a feature vectors.  
3 dimensional vector.
