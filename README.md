
# Title: Real-time-machine-learning-based-driver-monitoring-and-safety-system

## 📃 Description
This project addresses driver safety by using deep learning to detect drowsiness. It uses a custom dataset of eyes, faces, and airbags to monitor three aspects: driver's eye status, airbag status, and yawning behavior. It employs MobileNet with transfer learning for accuracy. Task 1 monitors the driver's eye status, alerting for closed eyes. Task 2 continuously checks airbag status, notifying others in case of an accident. Task 3 detects yawning, signaling when the driver is fatigued. The system runs all three tasks simultaneously in real-time using one camera.

## 💾 Dataset 

- Download the custom Dataset for training the model from given drive link below
If you want to train your own model or improve the existing one, download the dataset. But, if you just want to run the project locally no need to download the dataset, you can simply download the trained model and configure it and run it

- **Eyes Dataset** [Click here Download](https://drive.google.com/drive/folders/15mozP6NZxFSSSgO83QmTkhYAKTX6vOJP?usp=drive_link)

- **AirBags Dataset** [Click here to Download](https://drive.google.com/drive/folders/1iSBYJlMU0f97S1tR2WaE01sgIm0KLu96?usp=sharing)
## 📝 Documentation

- Download the Full Detailed Project Documentation from below link:

   [📖 Project Documentation](https://docs.google.com/document/d/1SeK7tihYwkUC1ifVm5u0VT3iYCmQBAJx/edit?usp=sharing&ouid=110092910534116920006&rtpof=true&sd=true)    
## 💻 Software

### 🛠️ Requirements

- Software Language: Python 3.9+
- Development Environment: Jupyter lab
- Operating System: Windows 11/10

#### Libraries and Tools used

    1. TensorFlow and Keras 
    2. Matplotlib 
    3. OpenCV 
    4. Dlib 
    5. Pygame 
    6. Pushbullet
    7. Haarcascade classifier
    8. Facial landmarks
    9. Standard Python Modules, NumPy, Math, pandas etc.

## ⬇️ Download Trained Models

To run the project directly download the trained models and configure their path in the code

- AirBag Model = [Click here to download](https://drive.google.com/file/d/1PHxW0aaCsjn40RQw9U6ZJDX04hiwoz-U/view?usp=drive_link)
- Eyes Model = [Click here to download](https://drive.google.com/file/d/1bZy9uS0h1h-guoBb4VxqEfSO8soZmReP/view?usp=drive_link)
- Facial Landmark file = [click here to download](https://drive.google.com/file/d/1sI953kULpH75BVh3_KQ-TfSQJ-8YJCE3/view?usp=drive_link)


## ⚙️ Installation and Setup

- Clone the project

```bash
git clone https://link-to-project
```

Go to the project directory

```bash
cd my-project
```

install all required packages and dependencies

```
pip install -r requirements.txt
```


## 🚀 Run Locally


- Load the trained model vor specific task

```bash
model = tf.keras.models.load_model(r'downloaded model path here')
```

- Load the Facial Landmarks for task 3
```
predictor_path = r"shape_predictor_68_face_landmarks.dat"

```

- Load the music from Audio Folder

```
alert_sound = pygame.mixer.Sound(r'yawn_alert.mp3')

song = r"alert.wav"

```
#### 🔥You are Good to go now🔥
