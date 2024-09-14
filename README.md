# Plant Disease Classfication

The system is designed to identify diseases in various plants through an end-to-end process. It accepts images of plant leaves as input, either uploaded or captured in real-time using the device's camera. The system then classifies the leaf based on potential diseases it may have. It can identify 15 different classes across three types of plants: potato, tomato, and bell pepper. Additionally, the system provides a confidence score for each prediction, indicating the likelihood of each diagnosis.

# Dataset 
The dataset is taken from kaggle - PlantVillage data set 

# About the Model
## CNN Architecture
![model](https://user-images.githubusercontent.com/66490787/219868725-9701133d-2f97-4fac-8f8b-c6108811dbdf.jpg)



## ScreenShots
### Home 
![home](https://github.com/user-attachments/assets/b1134920-806d-4fa0-9ffc-ad41354f3c87)

![upload](https://github.com/user-attachments/assets/fb7cbaa0-cb69-4d6e-ad2f-60910de41d0f)
![camera](https://github.com/user-attachments/assets/ed89f002-7ae3-4b0b-8d03-62d9d6846ab3)

### predictor
![predicted](https://github.com/user-attachments/assets/100dde2d-c782-4652-93ec-4c0d68de8cb5)



## Run Locally

Clone the project

```bash
  https://github.com/aryan098-max/Plant_Disease_Detection.git
```

Go to the project directory

```bash
  cd Potato_Disease_Classifier
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  streamlit run main.py
```


## Authors

- [Aryan Gupta](https://www.linkedin.com/in/aryan-gupta02/)




## Lessons Learned

- Working of API and API keys
- Integrating API's to a system.
- Creating and Deploying web apps.

## Support

For support, email aryangupta4279@gmail.com


