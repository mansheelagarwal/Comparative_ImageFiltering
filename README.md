# Comparative Image Filtering
![MnistExamplesModified](https://github.com/mansheelagarwal/Comparative_ImageFiltering/assets/76102724/38fafd7b-b625-4916-88ad-7ca5b17ae56f)
## Without Noise
This is a part of my minor project in which I applied the following filters to the MNIST dataset and analyzed their overall accuracies.
1. Mean Filtering
2. Median Filtering
3. Bilateral Filtering
4. Gaussian Filtering
5. Spatial Filtering
6. Temporal Filtering
7. Box Blur Filtering
8. Laplacian/Mexican Hat Filtering
9. Canny Edge Filtering
### Results
Mean filter performed the best with 99.2% accuracy whereas Laplacian filter performed the worst with an accuracy of almost 2%
## With Noise
To analyze the performance of the filters better and to introduce novelty into the work, I added the following types of noise and calculated the PSNR and NMSE scores for each filter:
1. Salt and Pepper
2. Gaussian
3. Poisson
4. Speckle
### Results
This gave us insight into the strengths and weaknesses of every filter and provided us with the clarity about which filters to use in what scenarios.




