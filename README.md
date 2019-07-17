# Bringing Alive Blurred Moments

Oral presentation at IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2019.
[Link to paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Purohit_Bringing_Alive_Blurred_Moments_CVPR_2019_paper.html)


Designed a deep convolutional architecture to extract a sharp video from a motion blurred image. The first stage involves unsupervised training of a novel spatiotemporal network for motion extraction from short video sequences. The above network is utilized for guided training of a CNN which extracts the same motion embedding from a single blurred image. The above networks are finally linked with our efficient deblurring network to generate the sharp video. Our framework delivers state-of-the-art accuracy in single image deblurring and video extraction while being faster and more compact. The work is among the first of its kind as the traditional algorithms extract only a single deblurred image.


Link to deblurring Results on GoPro Benchmark's test images: [Google Drive](https://drive.google.com/file/d/14bh90xksNJCNur0OMmjUhhzKdryvT3VC/view?usp=sharing)

DEMO:
Blurred Images:
![alt text](https://github.com/anshulbshah/Blurred-Image-to-Video/blob/master/bl.png) 
  
Video Extraction Results: 
Left : Generated Video
Right : Ground Truth Video
![alt text](https://github.com/anshulbshah/Blurred-Image-to-Video/blob/master/out.gif) 


## Citation

If you find our paper/results helpful in your research or work please cite our paper.

```
@inproceedings{purohit2019bringing,
  title={Bringing alive blurred moments},
  author={Purohit, Kuldeep and Shah, Anshul and Rajagopalan, AN},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={6830--6839},
  year={2019}
}
```
