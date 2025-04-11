
# 🧠 Object Recognition using ResNet50 on CIFAR-10

This project utilizes the **ResNet50** architecture with **transfer learning** to classify images from the **CIFAR-10** dataset. CIFAR-10 contains 60,000 color images across 10 object categories such as airplanes, cats, dogs, ships, etc.

## 🔍 Key Features

- Transfer learning using **ResNet50** (pretrained on ImageNet)  
- Fine-tuned on **CIFAR-10** dataset for multi-class classification  
- Preprocessing, training, and evaluation handled via Keras  
- Model achieves strong accuracy on validation/test sets  
- Visualizes predictions and training history

## 📁 Dataset: CIFAR-10

- **Classes**: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck  
- **Image Shape**: 32×32 pixels, 3 color channels  
- **Source**: Available via `keras.datasets.cifar10`

```python
from tensorflow.keras.datasets import cifar10
```

## 🧠 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab  

## ⚙️ Installation

```bash
git clone https://github.com/vir123-devf/object-recognition-resnet50.git
cd object-recognition-resnet50
jupyter notebook Object_Recogition_using_Resnet50.ipynb
```

## 🧪 Model Info

- **Base Model**: ResNet50 (pretrained on ImageNet, fine-tuned on CIFAR-10)  
- **Final Layers**: Dense + Softmax (10 output units for 10 classes)  
- **Loss Function**: Categorical Crossentropy  
- **Optimizer**: optimiziers

## 📄 License

Licensed under the **MIT License**

## 🤝 Contributing

Pull requests and contributions are welcome!

---
