<div align="center">

# TRI-STAGE OCCLUSION HANDLING NORMAL MAP ESTIMATION ALGORITHM (TSOHNMEA)

**_SAMSUNG PRISM PROGRAM_**

<img src="assets/architecture.png">

</div>

---

> This repository is the official implementation of the TSOHNMEA. The project report can be viewed using this [link](https://drive.google.com/file/d/1FKWe7SpYEyDQn0eXGucMvCyW7rve7kDI/view?usp=share_link).

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```

## Results

* ORDINARY NORMAL MAP ESTIMATION USING PIFU-HD MODEL:

https://user-images.githubusercontent.com/61982600/198841624-401f64ed-0bea-4c2f-9664-1ec43f2b82b1.mp4

* OUR TRI-STAGE OCCLUSION HANDLING NORMAL MAP ESTIMATION PIPELINE:

Background, Shadow and Blur occlusion of the original input image is handled and the
preprocessed input image is sent to the normal map estimation model

https://user-images.githubusercontent.com/61982600/198841628-c79d56c3-103b-4078-99aa-8b19621eb040.mp4


## Contact
For any queries, feel free to contact at vignesh.nitt10@gmail.com.

## References
https://github.com/facebookresearch/pifuhd
https://github.com/xinntao/Real-ESRGAN
