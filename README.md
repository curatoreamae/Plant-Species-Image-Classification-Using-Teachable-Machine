This project presents a collection of 20 different conifer plant species, identified and organized based on their common names, scientific names, and distinctive visual characteristics. The purpose of this compilation is to provide a clear and structured reference for recognizing various evergreen plants, particularly those commonly used in landscaping and ornamental gardening. Each plant entry is supported with representative images to enhance visual identification and understanding.

| #  | Common Name            | Scientific Name                | Distinctive Visual Description                                      | Image |
|----|------------------------|--------------------------------|---------------------------------------------------------------------|-------|
| 1  | Nordmann Fir           | *Abies nordmanniana*           | Dense dark green needles with soft texture and symmetrical shape.  | ![Abies](./image1.png) |
| 2  | Norfolk Island Pine    | *Araucaria heterophylla*       | Layered branches forming a symmetrical pyramid shape.              | ![Araucaria](./image2.png) |
| 3  | Arizona Cypress        | *Cupressus arizonica*          | Blue-gray foliage with a conical form and rough bark.              | ![Arizona Cypress](./image3.png) |
| 4  | White Cypress Pine     | *Callitris columellaris*       | Fine, needle-like leaves with a narrow upright growth habit.       | ![Callitris](./image4.png) |
| 5  | Lawson Cypress         | *Chamaecyparis lawsoniana*     | Soft scale-like foliage with feathery texture and elegant form.    | ![Lawson Cypress](./image5.png) |
| 6  | Sawara Cypress         | *Chamaecyparis pisifera*       | Delicate thread-like or feathery foliage, often bright green.      | ![Sawara Cypress](./images6.png) |
| 7  | Italian Cypress (Gold) | *Cupressus sempervirens*       | Tall narrow column shape with golden-green foliage.                | ![Gold Cypress](./image7.png) |
| 8  | Monterey Cypress       | *Cupressus macrocarpa*         | Broad spreading crown with dense dark green foliage.               | ![Monterey Cypress](./image8.png) |
| 9  | Himalayan Cypress      | *Cupressus torulosa*           | Graceful drooping branches with soft green foliage.                | ![Himalayan Cypress](./image9.png) |
| 10 | Chinese Juniper        | *Juniperus chinensis*          | Dense evergreen shrub/tree with scale-like green foliage.          | ![Juniperus chinensis](./image10.png) |
| 11 | Eastern Red Cedar      | *Juniperus virginiana*         | Compact conical tree with blue-green foliage and berry cones.      | ![Juniperus virginiana](./image11.png) |
| 12 | Leyland Cypress        | *Cupressus × leylandii*        | Fast-growing hybrid with dense feathery foliage.                   | ![Leyland Cypress](./image12.png) |
| 13 | Oriental Arborvitae    | *Platycladus orientalis*       | Upright branches with flattened sprays of bright green leaves.     | ![Arborvitae](images/13.png) |
| 14 | White Spruce           | *Picea glauca*                | Conical tree with short stiff needles and bluish-green color.      | ![White Spruce](./image14.png) |
| 15 | Stone Pine             | *Pinus pinea*                 | Umbrella-shaped canopy with long needles and thick trunk.          | ![Stone Pine](./image15.png) |
| 16 | Buddhist Pine          | *Podocarpus macrophyllus*     | Long narrow glossy leaves with a neat upright growth habit.        | ![Podocarpus](./image16.png) |
| 17 | Coast Redwood          | *Sequoia sempervirens*        | Very tall tree with reddish bark and soft flat needles.            | ![Redwood](./image17.png) |
| 18 | Bald Cypress           | *Taxodium distichum*          | Deciduous conifer with feathery leaves and buttressed trunk base.  | ![Bald Cypress](./image18.png) |
| 19 | English Yew            | *Taxus baccata*               | Dark green needle-like leaves with red berry-like arils.           | ![Yew](./image19.png) |
| 20 | American Arborvitae    | *Thuja occidentalis*          | Dense conical shrub/tree with scale-like bright green foliage.     | ![Thuja](./image20.png) |

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


### E. Model Testing

<img width="168" height="633" alt="Screenshot 2026-03-30 144628" src="https://github.com/user-attachments/assets/969d9415-4c95-4a04-95e0-3d746e1f7572" />
<img width="177" height="705" alt="Screenshot 2026-03-30 142137" src="https://github.com/user-attachments/assets/094fb0c0-0e3d-4475-96da-7a2c1f4f966d" />
<img width="171" height="639" alt="Screenshot 2026-03-30 144903" src="https://github.com/user-attachments/assets/ddf60e1a-68b5-4ede-b028-770e521f1a90" />
<img width="178" height="633" alt="Screenshot 2026-03-30 145310" src="https://github.com/user-attachments/assets/8be0dece-3d03-49ca-8982-89166ce40673" />
<img width="221" height="667" alt="Screenshot 2026-03-30 145818" src="https://github.com/user-attachments/assets/32088219-e8c6-4726-8a5d-ff7444a9c641" />
<img width="198" height="675" alt="Screenshot 2026-03-30 150254" src="https://github.com/user-attachments/assets/9487d4b4-6d3e-43ff-b025-c3a8c66426da" />
<img width="201" height="664" alt="Screenshot 2026-03-30 150422" src="https://github.com/user-attachments/assets/8d4e23e9-0c5e-4c4d-80c9-41a2237a6b01" />
<img width="194" height="676" alt="Screenshot 2026-03-30 151028" src="https://github.com/user-attachments/assets/d5d5da80-f78d-4689-85e6-57f867fc894b" />
<img width="209" height="672" alt="Screenshot 2026-03-30 151233" src="https://github.com/user-attachments/assets/2cde7fb6-6515-483d-8cb3-47b78b66601d" />
<img width="200" height="788" alt="Screenshot 2026-03-30 152226" src="https://github.com/user-attachments/assets/7bacadf1-882e-4eb0-aaae-ae2b3f93e71f" />

### F. Reflection


1. How did the number of images per class affect your model’s accuracy?
Having more images in each class made the model more accurate because it had more examples to learn from. This helped the model understand each plant better.

2. Which plant species were most commonly misclassified and why?
Plants that look very similar were often misclassified. This is because the model had a hard time telling them apart when their leaves or shapes looked almost the same.

3. How did changing the epochs, batch size, or learning rate affect the training results?
More epochs helped improve accuracy, but too many made the model overfit. The learning rate affected how fast the model learned—too fast caused mistakes, and too slow made training take longer. Batch size changed how smooth and fast the training was.

4. What challenges did you encounter during dataset collection and labeling?
It was hard to find enough clear and good-quality images. Avoiding duplicate images and making sure labels were correct was also difficult. Organizing the dataset took time.

5. If you were to improve your model, what specific changes would you make and why?
I would add more images and use better-quality ones. I would also adjust the training settings and maybe use a better model to improve accuracy.
