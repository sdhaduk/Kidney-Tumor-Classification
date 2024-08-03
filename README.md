# Kidney Tumor Classification

## Description
This project utilizes Tensorflow, Keras, MLFlow, and DVC to create an end to end deep learning project that can classify pictures of kidneys as either being healthy (Normal) or having a tumor (Tumor). 

### Full Dataset
https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone

### Test with these images
https://drive.google.com/file/d/1vlhZ5c7abUKF8xXERIw6m9Te8fW7ohw3/view?usp=sharing

### Hosted At
http://54.209.136.228:8080/

### Demo:
In this demo you can see that I upload multiple images of a ct scan of kidneys. These images are then compressed to the target size of 224x224, turned into a tensor, and are finally fed into the model. The prediction is returned and sent to the user.

https://github.com/user-attachments/assets/9570cd10-97ac-49fb-b158-82a5fc9dabee

# How to run locally

### STEPS:
Clone the repository

```bash
https://github.com/sdhaduk/Kidney-Tumor-Classification.git
```

### STEP 01 - Create a virutal or conda environment in Python 3.8
```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```

### STEP 02 - Install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```
