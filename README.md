# **ChestX-ray14 연동 흉부질환 국내의학 백과사전 데이터베이스**

## Data descriptions
### There are eight classes for 880 subjects

* Atelectasis
* Cardiomegaly
* Effusion
* Infiltrate
* Mass
* Nodule
* Pneumonia
* Pneumothorax

### Image

```
├── X-ray image 512×512×3 
```

### Annotation
```
├── filename
├── observed
│   ├── class
│   ├── bndbox
│   └── description
|       ├── cause
|       ├── symptom
|       └── diagnosis and treatment
```

## **Examples**

### image

<img src="./figure_01.jpg" width="500" height="270">

### Annotation

<img src="./xml.JPG" width="583" height="427"> 

## **License**
[MIT License](./LICENSE.md)

## **Reference**
* https://www.kaggle.com/nih-chest-xrays/data?select=BBox_List_2017.csv
* NIH News release: NIH Clinical Center provides one of the largest publicly available chest x-ray datasets to scientific community
* Original source files and documents: https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345
### **Download Link**
> https://drive.google.com/file/d/1SLQBrafbDi7W3G75bw_tKaV25C3HAk6N/view?usp=sharing
