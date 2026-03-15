# Plant-Species-Image-Classification-Using-Teachable-Machine
# Plant Species Image Classification
## Laboratory Work 2-A Activity

### A. Project Overview
This project focuses on the development of a machine learning model designed to classify 20 different variants of Ornamental Plants. 

### Purpose: 
The goal is to evaluate how effectively an Image Classification model (trained via Teachable Machine) can distinguish between closely related cultivars that share similar leaf shapes but differ in color distribution and spotting patterns.

### B. Plant Species Section

### C. Model Training Details
The model was trained using the Standard Image Model architecture.

Epochs: 110
- I selected 110 epochs to give the model sufficient training cycles to learn patterns from the dataset and enhance its accuracy. This number allows the model to update its weights multiple times while maintaining a reasonable training time. Additionally, it is commonly used as an initial value in many machine learning experiments.

Batch Size: 16

Learning Rate: 0.001

Images per Class: 250 and 250+

### Screenshot of the training settings
<img width="1522" height="815" alt="image" src="./training-settings.png" />

### D. Model Evaluation
The following metrics were captured from the "Under the Hood" section of Teachable Machine.

#### Confusion Matrix
<img width="382" height="756" alt="image" src="./confusion-matrix.png" />

#### Accuracy per Class
<img width="377" height="786" alt="image" src="./accuracy-per-class.png" />

#### Accuracy per Epoch
<img width="368" height="602" alt="image" src="./accuracy-per-epoch.png" />
