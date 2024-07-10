## Implementing Histogram Matching (Q4.ipynb)
In this method, we want to change the histogram of an image so that it matches a specified histogram.  
I used numpy library to implement histogram matching.  

## Implementing Adaptive Contrast Enhancement (ACE) methods (Q5.ipynb)
- Part a: This is global histogram equalization that does not use local information
- Part b: The first method of ACE in which the image is divided into smaller chunks and histogram equalization is applied on each chunk separately
- Part c: The second method of ACE also referred to as Adaptive Histogram Equalization (AHE) in which the value of each pixel is determined by nearby pixels, this method suffers from noise amplification in uniform areas 
- Part d: Contrast Limited AHE (CLAHE) which resolves the noises in AHE
