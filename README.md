<div align="center">

# TRI-STAGE OCCLUSION HANDLING NORMAL MAP ESTIMATION ALGORITHM (TSOHNMEA)

**_SAMSUNG PRISM PROGRAM_**

![architecture](https://user-images.githubusercontent.com/61982600/198841785-56d72a24-a215-488f-b208-017add1480dd.PNG)

</div>

---

> This repository is the official implementation of the TSOHNMEA. The project report can be viewed using this [link](https://drive.google.com/file/d/1FKWe7SpYEyDQn0eXGucMvCyW7rve7kDI/view?usp=share_link). Complete end-to-end pipeline code is not included yet.

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```
## Output

As the end-to-end pipeline code is not included, users must manually take the output from each .ipynb section. The order to extracts and input the outputs is  
* background_occlusion_handler.ipynb (not included yet, so we suggest to use an image without any background to test the rest of the pipeline)
* Real_ESRGAN_blur_occlusion.ipynb 
* PiFUHD_normal_map_estimation.ipynb

## Results

* ORDINARY NORMAL MAP ESTIMATION USING PIFU-HD MODEL:

https://user-images.githubusercontent.com/61982600/198841624-401f64ed-0bea-4c2f-9664-1ec43f2b82b1.mp4

* OUR TRI-STAGE OCCLUSION HANDLING NORMAL MAP ESTIMATION PIPELINE:

Background, Shadow and Blur occlusion of the original input image is handled and the
preprocessed input image is sent to the normal map estimation model

https://user-images.githubusercontent.com/61982600/198841628-c79d56c3-103b-4078-99aa-8b19621eb040.mp4

## TODO

  * [ ] Upload complete end-to-end pipeline code (not included right now because further improvements are being made).
  * [ ] Include background occlusion handler code (not included right now because more advanced and better architectures are being explored).
  * [ ] Handle object occlusion.

## References

https://github.com/tensorflow/models/tree/master/research/deeplab \
https://github.com/xinntao/Real-ESRGAN \
https://github.com/facebookresearch/pifuhd 

## Contact
For any queries, feel free to contact at vignesh.nitt10@gmail.com.
