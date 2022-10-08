# Traffic Sign Recognition
<b>Codebase For Team CSPDarknet53's Interpretation Of The `AI In Geoservices` Challenge From The Artificial Intelligence International Junior Contest</b>

<br>

## Contents
- ### Code
- ### Website Demo
- ### Details

<br>

## Code

### [Model Pipeline & Training:](https://github.com/Ansh3101/AIIJC/tree/main/Code)

- **EfficientNetB2.ipynb : Notebook To Bring Together The Pipeline**

- #### Pipeline :
  - **constants.py : Some Constant Values**
  - **dataset.py : Data Preprocessing / Loading**
  - **generate_submission.py : Generates Submissions For The Contest**
  - **models.py : Model Dictionary & Class**
  - **train.py : Model Training Module**
  - **utils.py : Helper Functions**
 

### [Website :](https://github.com/Ansh3101/AIIJC/tree/main/Website)

- **inference.py : Helper Function For Flask App**
- **main.py : Flask App Backend**

- **App :** 
  - **Test Images (From WikiPedia)**
  - **Class2Label Dictionary**
  - **English Conversion For Classes**
  - **Russian Conversion For Classes**


- **Frontend Code :**
  - **index.html : FrontEnd For Website HomePage**
  - **result.html : FrontEnd For Predictions**

- **Styling :**
  - **Images For Website**
  - **Styles For Website**

<br>

## Website Demo

https://user-images.githubusercontent.com/105856839/194222215-367939ee-b055-4c08-b87e-325a6f6197d1.mp4

<br>

## Details

### Model

<b>Pre-Trained Model : EfficientNetB0 With Custom Head</b>

<b>Image Size: (224, 224)</b>

<b>Image Preprocessing:  `pseudo-labelling`, `albumentations`</b>

<b>Training Time: 14 hours</b>

<b>Training Accuracy: 99.86%</b>

<b>Validation Accuracy: 99.72%</b>

<b>Testing Accuracy: 99.2%</b>
