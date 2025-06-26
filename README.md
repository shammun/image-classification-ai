# 🛰️ Real AI Image Classification - Satellite Image Classifier

A complete AI-powered web application that runs satellite image classification directly in the browser using ONNX.js and a trained ResNet-34 model.

## 🎯 What This Does

- **Real AI Classification**: Uses our trained 89.6% accurate ResNet-34 model
- **Browser-Based**: No servers needed - AI runs completely in user's browser
- **Privacy-First**: Images never leave the user's device
- **Global Access**: Anyone can use it from anywhere in the world
- **Mobile Friendly**: Works on phones, tablets, and computers

## 🚀 Live Demo

🌐 **Visit the live demo:** [https://shammun.github.io/image-classification-ai](https://shammun.github.io/image-classification-ai)

## 📊 Model Performance

- **Accuracy**: 89.6%
- **F1-Score**: 89.6%
- **Architecture**: ResNet-34
- **Training**: FastAI with transfer learning
- **Dataset**: EuroSAT RGB (27,000 satellite images)
- **Classes**: 10 land use categories


## 🏗️ Technical Architecture

```
Frontend (Browser)
├── HTML5 + CSS3 (Modern UI)
├── JavaScript (ONNX.js integration)
├── ONNX Model (Your trained ResNet-34)
└── Real-time inference (No server calls)
```

## 📁 Project Structure

```
├── docs/                          # GitHub Pages website
│   ├── index.html                 # Main application (FIXED)
│   ├── css/style.css             # Enhanced styling
│   ├── js/app.js                 # Real AI integration (FIXED)
│   └── models/
│       ├── crop_model_web.onnx   # Your AI model
│       └── model_config.json     # Model configuration
├── model_export_deployment.py    # This deployment script
├── crop_monitoring_model.pkl     # Original FastAI model
└── README.md                     # This file
```

## 🎯 Land Use Categories

Your AI can classify these satellite image types:

1. **AnnualCrop** - Farmland with annual crops
2. **Forest** - Forested areas and woodlands  
3. **HerbaceousVegetation** - Grasslands and meadows
4. **Highway** - Roads and transportation infrastructure
5. **Industrial** - Industrial zones and facilities
6. **Pasture** - Grazing land for livestock
7. **PermanentCrop** - Orchards and vineyards
8. **Residential** - Housing and urban areas
9. **River** - Rivers and waterways
10. **SeaLake** - Seas, lakes, and large water bodies

## 🛠️ How It Works

1. **User uploads satellite image** → Single click to upload
2. **Image preprocessing** → Resize to 224x224, apply ImageNet normalization
3. **AI inference** → ONNX.js runs on the fine-tuned ResNet-34 model in browser
4. **Results display** → Shows confidence scores for all 10 classes
5. **No data transmission** → Everything happens locally in user's browser

## 🔬 Technical Features

- **Real ONNX.js Integration**: Actual AI model running in browser
- **Graceful Fallbacks**: Demo mode if model fails to load
- **Performance Optimized**: Fast inference with progress indicators
- **Error Handling**: Comprehensive error management
- **Responsive Design**: Works on all screen sizes
- **Accessibility**: Screen reader friendly with semantic HTML

## 🌟 User Experience

- **Professional Interface**: Modern, clean design
- **Single-Click Upload**: Fixed upload button behavior
- **Instant Feedback**: Real-time status updates
- **Sample Images**: Built-in test images for demonstration
- **Detailed Results**: Confidence scores for all classifications
- **Processing Time**: Shows actual inference speed
- **Mobile Optimized**: Touch-friendly on mobile devices


## 📝 License

MIT License - Free to use, modify, and distribute.

## 🙏 Acknowledgments

- **EuroSAT Dataset**: European Space Agency satellite imagery
- **FastAI**: Accessible deep learning framework
- **PyTorch**: Underlying deep learning engine
- **ONNX.js**: Browser-based AI inference
- **GitHub Pages**: Free web hosting
