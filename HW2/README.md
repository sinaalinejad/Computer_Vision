## Sobel and Canny Edge Detection (Q1.ipynb)


## Saffrun Edge Detection using Fast Fourier Transform (FFT) and Canny algorithm (Other_Qs.ipynb)
- Taking the image to the frequency domain using FFT
- Applying Gaussian kernel on frequency domain to remove high frequencies, this is done to remove the noises so that edge detection works better
- Converting the image from frequency domain back to spacial domain
- Using Canny algorithm on denoised image to find edges



## Implementing different smoothing methods (Q6.ipynb)
- Part a: Implementing Average, Median and Gaussian Blurring
- Part b: Implementing Bilateral filtering which outperforms the methods in part a
- Part c: Previous parts were implemented using numpy library, in part c, above methods are applied on image using OpenCV library

