# Image Manipulation (Forgery) Detection System

In today’s technical world, the digital image is a vital part of many application domains.
Image forgery refers to the manipulation of digital images to hide important information
or output false information. Due to the introduction of modern image processing tools,
digital image forgery is at its peak.

Copy-move forgery is one of the most commonly used techniques to perform image forgery.
The aim of the proposed system is to detect and highlight the malpractices performed on
modern-day digital images.

---

## Image Forgery Detection Tool

The forgery detection tool contained in this repository currently features forensic
methods to detect the following:

- Double JPEG compression  
- Copy-move forgeries  
- Metadata Analysis  
- CFA artifacts  
- Noise variance inconsistencies  
- Error Level Analysis  
- Image Extraction  
- String Extraction  

For more detail:  
[Research Paper](https://journals.grdpublications.com/index.php/ijprse/article/view/537/507)

---

## To Run

Navigate to the **Project** directory:
```bash
cd Image_Manipulation_Detection_System
```

Next, run the **detect.py** script, providing the image you wish to evaluate:
```
$ python GUI.py
```

Once finished, details on the image will be reported in the terminal. Supplemental images generated during copy-move forgery detection can be found in the output directory.

##  IMAGES
<img src="Screenshot/1.jpg">
<img src="Screenshot/2.jpg">

