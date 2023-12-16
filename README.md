# Neural Style Transfer

For our CIS 5810 final project, we implemented the classic Neural Style Transfer algorithm outlined by Gatys et al. in their 2015 paper and 2016 IEEE CVPR presentation [1][2], as well as a Fast NST approach based on the paper "Perceptual Losses for Real-Time Style Transfer and Super-Resolution" [3] by Johnson et al. to allow style transfer for video clips and other applications that require a faster implementation.

## Installation

Since our implementation uses Google Colab, no installation is required.   

To run the code, create a new Google Colab notebook and clone this repository.  
```
! git clone https://github.com/teriyake/Fast-NST.git
```
Optional: insert a cell with the following if you would like to save the results to Google Drive.
```
from google.colab import drive
drive.mount(‘/content/MyDrive’) 
```

## Contributors

Ria Subramanian  
[Teri Ke](https://github.com/teriyake)

## References
[1] Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge. “A Neural Algorithm of Artistic Style”. In: (2015). arXiv: 1508.06576 [cs.CV].  

[2] Leon A. Getsy, Alexander S. Ecker, and Matthias. Bethge. “Image Style Transfer Using Convolutional Neural Networks”. In: Presented at the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016.  

[3] Justin Johnson, Alexandre Alahi, and Li Fei-Fei. “Perceptual Losses for Real-Time Style Transfer and Super-Resolution”. In: (2016). arXiv: 1603.08155 [cs.CV].  
