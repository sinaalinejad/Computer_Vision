## Implementing Histogram Matching (Q4.ipynb)
In this method, we want to change the histogram of an image so that it matches a specified histogram.  
I used numpy library to implement histogram matching.  

## Implementing Adaptive Contrast Enhancement (ACE) methods
- Part a: This is global histogram equalization that does not use local information
- Part b: First method of ACE in which the image is divided to smaller chunks and histogram equalization is applied on each chunk seperately
- Part c: second method of ACE also refered as Adaptive Histogram Equalization (AHE) in which the value of each pixel is determined by nearby pixels, this method suffers from noise amplification in uniform areas 
- Part d: Contrast Limited AHE (CLAHE) which resolves the noises in AHE
