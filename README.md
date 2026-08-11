# Pet-Dog-Cat-Semantic-Segmentation
A semantic segmentation project using U-Net architecture with a pretrained ResNet34 encoder to segment cats and dogs from background.
In the future, I will also upload notebooks of models such as from scratch U-Net encoder-decoder, DeepLabV3+, and SegFormer on this dataset.

## 🧠 Model

- **Architecture:** U-Net
- **Encoder:** ResNet34 (pretrained on ImageNet)
- **Task:** Binary semantic segmentation
- **Input Size:** 256×256
- **Loss:** Dice Loss + Cross-Entropy
- **Optimizer:** Adam
- **Learning Rate:** 1e-4 , 1e-5 , 1e-6
- **Epochs:** 40
- **Data Augmentation:** Yes

## 📊 Results

- **Validation Dice Score:** ~94%
- **Validation Loss:** ~0.17

- **Test Dice Score:** ~94%
- **Test IoU:** ~89%

