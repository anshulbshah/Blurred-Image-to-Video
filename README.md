# Bringing Alive Blurred Moments

Designed a deep convolutional architecture to extract a sharp video from a motion blurred image. The first stage involves unsupervised training of a novel spatiotemporal network for motion extraction from short video sequences. The above network is utilized for guided training of a CNN which extracts the same motion embedding from a single blurred image. The above networks are finally linked with our efficient deblurring network to generate the sharp video. Our framework delivers state-of-the-art accuracy in single image deblurring and video extraction while being faster and more compact. The work is among the first of its kind as the traditional algorithms extract only a single deblurred image.

Will be presented at IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2019.

Deblurring and Video Extraction Results on GoPro Benchmark and Blur Detection Dataset coming soon!

DEMO:
Blurred Images:
![alt text](https://github.com/anshulbshah/Blurred-Image-to-Video/blob/master/bl.png) 
  
Video Extraction Results: 
Left : Generated Video
Right : Ground Truth Video
![alt text](https://github.com/anshulbshah/Blurred-Image-to-Video/blob/master/out.gif) 
