
# 🧠 Object Recognition using ResNet50

This project leverages the powerful **ResNet50** deep learning architecture to recognize and classify objects in images. It uses **transfer learning** to apply a pre-trained model to new image inputs, enabling high-accuracy predictions with minimal training time.

## 🔍 Key Features

- Uses **ResNet50** (pre-trained on ImageNet) for object classification  
- Efficient **transfer learning** setup using TensorFlow/Keras  
- Input preprocessing and prediction with softmax output  
- Recognizes a wide variety of real-world objects from input images  
- Visual display of prediction confidence  

## 🧠 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib 
- Jupyter Notebook / Google Colab  

## 🖼️ How It Works

1. Load the **ResNet50** model with ImageNet weights  
2. Preprocess user-uploaded image(s)  
3. Run the image through the model  
4. Decode and display the **top predicted class and confidence score**  


```

📷 Sample output:
- Predicted: `golden retriever (n02099601)`  
- Confidence: `96.23%`

## ⚙️ Installation

```bash
git clone https://github.com/vir123-devf/object-recognition-resnet50.git
cd object-recognition-resnet50
jupyter notebook Object_Recogition_using_Resnet50.ipynb
```
## 📄 License

Licensed under the **MIT License**

## 🤝 Contributing

Contributions welcome! Submit a pull request or open an issue to improve the project.
---
