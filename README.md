# DeepShield - DeepFake Detection

DeepFake Detection Web-App 🖥 using Deep Learning (ResNext and LSTM), Flask, and ReactJs where you can predict whether a video is FAKE or REAL along with the confidence ratio.

## Explanation of the Project

* Designed a DeepFake Detection system to identify DeepFake videos using Deep Learning techniques like ResNext and LSTM. Integrated the trained model with a ReactJS Frontend and Flask Backend.
* The dataset used to train the model is available [here](https://github.com/yuezunli/celeb-deepfakeforensics).
* Trained model files can be found [here](https://drive.google.com/drive/folders/1-zErGZ9T89TplQs3ws4QVRFlqE-ljW6l?usp=sharing).
* Model training reference taken from [this resource](https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning/tree/master/Model%20Creation).

### Project Structure

```
DeepShield
    |
    |--- DeepFake_Detection
    |--- Implementation Video
    |--- Project-Setup.txt
    |--- Requirements.txt
```

1. **DeepFake\_Detection** - Root folder of the project.
2. **Implementation Video** - Shows complete working of the project.
3. **Project-Setup.txt** - Contains all steps to set up and run the project.
4. **Requirements.txt** - Python libraries needed for this project.

## Project Set-up Guidelines

Setup instructions are listed [here](https://github.com/Ajad-cpu/DeepShield/blob/main/Project-Setup.txt).

## Notes

1. In the root folder (`DeepFake_Detection`), create a folder called `Uploaded_Files`.
2. In the root folder (`DeepFake_Detection`), create a folder called `model` and add the [model file](https://drive.google.com/drive/folders/1-zErGZ9T89TplQs3ws4QVRFlqE-ljW6l?usp=sharing) in it.

*(Paths are already set in `server.py`, so this avoids errors.)*

## Results

1. **Accuracy of the Model**

   <img width="250" height="50" alt="Model Accuracy" src="https://user-images.githubusercontent.com/58872872/133935912-1def7615-6538-4c88-9134-8f94a9367965.png">

2. **Training and Validation Accuracy Graph**

   <img width="378" alt="Accuracy Graph" src="https://user-images.githubusercontent.com/58872872/133936040-4bfa44a7-45c5-499b-8a10-f253cbcab56c.png">

3. **Training and Validation Loss Graph**

   <img width="381" alt="Loss Graph" src="https://user-images.githubusercontent.com/58872872/133935983-b4d9275f-e841-4b69-86cd-79c770ea2aa1.png">

4. **Confusion Matrix**

   <img width="402" alt="Confusion Matrix" src="https://user-images.githubusercontent.com/58872872/133936080-d2b39804-4a99-47b8-8be4-87ba77161961.png">

* To see the working of the project, click [here](https://github.com/Ajad-cpu/DeepShield/blob/main/Implementation%20Video.mp4).

## Developer

* [Ajad](https://github.com/Ajad-cpu)
