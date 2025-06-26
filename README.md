# 🛰️ Real AI Crop Monitoring - Satellite Image Classifier

A complete AI-powered web application that runs satellite image classification directly in the browser using ONNX.js and a trained ResNet-34 model.

## 🎯 What This Does

- **Real AI Classification**: Uses your trained 89.6% accurate ResNet-34 model
- **Browser-Based**: No servers needed - AI runs completely in user's browser
- **Privacy-First**: Images never leave the user's device
- **Global Access**: Anyone can use it from anywhere in the world
- **Mobile Friendly**: Works on phones, tablets, and computers
- **Fixed UI**: Single-click upload with no double-click issues

## 🚀 Live Demo

Your app will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## 📊 Model Performance

- **Accuracy**: 89.6%
- **F1-Score**: 89.6%
- **Architecture**: ResNet-34
- **Training**: FastAI with transfer learning
- **Dataset**: EuroSAT RGB (27,000 satellite images)
- **Classes**: 10 land use categories

## 🔧 Fixed Issues

✅ **Single-Click Upload**: No more double-click requirement  
✅ **Proper Event Handling**: Clean JavaScript event management  
✅ **Sample Image Fix**: Sample buttons work with single click  
✅ **Drag & Drop**: Smooth drag and drop functionality  
✅ **Mobile Optimized**: Touch-friendly interface  

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
3. **AI inference** → ONNX.js runs your ResNet-34 model in browser
4. **Results display** → Shows confidence scores for all 10 classes
5. **No data transmission** → Everything happens locally in user's browser

## 🔬 Technical Features

- **Real ONNX.js Integration**: Actual AI model running in browser
- **Fixed Event Handling**: No double-click issues
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

## 🚀 Deployment Status

- ✅ **AI Model**: Web-compatible ONNX format
- ✅ **Frontend**: Modern HTML5/CSS3/JavaScript (FIXED)
- ✅ **Real Integration**: ONNX.js with actual inference
- ✅ **UI Fixed**: Single-click upload, no double-click issues
- ✅ **Fallback System**: Demo mode for compatibility
- ✅ **GitHub Pages**: Ready for deployment
- ✅ **Documentation**: Complete setup instructions

## 🎉 Success Metrics

Once deployed, your app provides:

- **Global Accessibility**: Anyone can use your AI model
- **Zero Server Costs**: Completely client-side application
- **Educational Impact**: Demonstrates real AI deployment
- **Portfolio Value**: Professional-grade ML engineering project
- **Privacy Compliance**: No data collection or transmission
- **Professional UX**: Smooth, single-click interface

## 📝 License

MIT License - Free to use, modify, and distribute.

## 🙏 Acknowledgments

- **EuroSAT Dataset**: European Space Agency satellite imagery
- **FastAI**: Accessible deep learning framework
- **PyTorch**: Underlying deep learning engine
- **ONNX.js**: Browser-based AI inference
- **GitHub Pages**: Free web hosting
