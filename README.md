## Disclaimer

**This project is created strictly for learning and practice purposes. It is an educational experiment and is not production-ready or intended for real-world commercial use.**

---

# Fashion-MNIST Classification using VGG16

A PyTorch deep learning project implementing **Transfer Learning with pretrained VGG16** to classify Fashion-MNIST images into 10 clothing categories.

## Tech Stack
- Python
- PyTorch & Torchvision
- Pandas & NumPy
- Scikit-learn
- Matplotlib

## Model Architecture
- Pretrained VGG16 (ImageNet weights)
- Frozen feature extraction layers
- Custom fully connected classification head
- ReLU and Dropout layers
- 10 output classes

## Training Configuration

| Parameter | Value |
|---|---|
| Optimizer | Adam |
| Loss Function | CrossEntropyLoss |
| Learning Rate | 0.0001 |
| Batch Size | 32 |
| Epochs | 20 |
| Train-Test Split | 80:20 |

## Dataset

Fashion-MNIST containing 10 clothing categories, including T-shirts, trousers, dresses, sneakers and bags.

## Learning Objectives
- Practising PyTorch and CNNs.
- Understanding Transfer Learning.
- Building custom Dataset and DataLoader classes.
- Implementing image preprocessing.
- Training and evaluating deep learning models.

---

Built with Python and PyTorch.
