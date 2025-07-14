
# 🧠 Cataract Detection using Deep Learning

This project is focused on detecting cataract disease from ocular fundus images using a pre-trained **VGG19** model. It classifies images into two classes: **Cataract** and **Normal**.

## 📁 Dataset
The dataset includes left and right eye fundus images labeled by diagnostic keywords. The images are preprocessed and resized to 224x224.

## 🚀 Technologies Used
- Python, NumPy, Pandas, OpenCV
- TensorFlow, Keras (VGG19 model)
- Scikit-learn, Matplotlib, Seaborn
- scikit-plot (confusion matrix visualization)

## 🧪 Workflow
1. Load and preprocess image data
2. Extract cataract/normal images based on labels
3. Train/test split and data augmentation
4. Train CNN using VGG19 + custom classification head
5. Evaluate model performance (accuracy, loss, confusion matrix)

## 📦 How to Run
Make sure to place your data in `data/` and update the path in the code.

```bash
pip install -r requirements.txt
python src/cataract_detection.py
```

## 📈 Results
Model trained for 15 epochs using categorical cross-entropy and Adam optimizer. Accuracy and loss are visualized using seaborn.

## 📫 Author
[Muhammed Ramadan](https://github.com/Moramada)  
Email: mohamedgad8790@gmail.com
