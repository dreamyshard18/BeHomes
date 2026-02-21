# 🌸 BeyondHomes  
### Automate Your Home Business Marketing

BeyondHomes is an end-to-end marketing automation platform designed for **home-based businesses and micro-entrepreneurs**.

From uploading a simple product photo to automatically generating a branded catalogue and posting on social media — BeyondHomes handles everything for you.

---

## 💡 Problem Statement

Many home-based businesses and small sellers — selling:

- 🧵 Textiles  
- 🕯 Candles  
- 💍 Jewellery  
- 🍲 Homemade food  
- 🎨 Local handicrafts  
- 👗 Clothing  

Often struggle with:

- Managing digital inventory  
- Designing professional catalogues  
- Writing engaging social media captions  
- Posting consistently on Instagram & LinkedIn  
- Maintaining brand consistency  

BeyondHomes removes this digital friction.

---

## 🚀 How It Works

### 1️⃣ Upload Product Image  
The entrepreneur uploads a product image via a clean web interface.

### 2️⃣ AI Product Classification  
The image is sent into an automation workflow where:

- A **HuggingFace image classification model**:
  - Classifies the product into one of:
    - Food  
    - Jewellery  
    - Candles  
    - Handicrafts  
    - Clothes  
  - Extracts dominant colors from the image.

### 3️⃣ Smart Catalogue Generation  
Based on the detected category, a one-page product catalogue is auto-generated with a predefined aesthetic theme:

| Category      | Color Theme |
|--------------|------------|
| 🕯 Candles     | Beige tones |
| 🍲 Food        | Warm & colourful |
| 🎨 Handicrafts | Blue tones |
| 💍 Jewellery   | Pink & purple tones |
| 👗 Clothes     | Green tones |

The generated catalogue includes:
- Product image  
- Clean layout  
- Category-specific theme  
- Marketing-ready design  

### 4️⃣ Caption Generation  
Using **Gemini API**, captions are generated for:
- Instagram  
- LinkedIn  

Each caption includes:
- Engaging product description  
- Platform-appropriate tone  
- Relevant hashtags  

### 5️⃣ Automated Social Posting  
The system automatically posts:
- Product image  
- Generated catalogue  
- AI-generated caption  

To the user's:
- Instagram handle  
- LinkedIn profile  

All automated. All through a seamless workflow.

---

## 🔄 Complete Workflow Architecture

Landing Page (Image Upload)  
⬇  
n8n Automation Workflow  
⬇  
HuggingFace Model → Product Classification & Color Extraction  
⬇  
Theme Selection  
⬇  
Catalogue Generation (Canva / Placid)  
⬇  
Gemini Caption Generation  
⬇  
Auto Post to Instagram & LinkedIn  

---

## 🛠 Tech Stack

### Frontend
- HTML  
- CSS  
- JavaScript  

### AI & ML
- HuggingFace (Image Classification Model)
- Gemini API (Caption & Hashtag Generation)

### Automation
- n8n (Workflow Automation Engine)
- Placid Automation Toolkit
- Canva (Design Generation)

### Social Platforms
- Instagram API
- LinkedIn API

---

## ✨ Key Features

✔ One-click product upload  
✔ AI-based product categorization  
✔ Automatic brand-aligned catalogue creation  
✔ Smart caption generation with hashtags  
✔ Cross-platform auto-posting  
✔ Fully automated marketing workflow  

---

## 🎯 Target Users

- Home-based businesses  
- Micro-entrepreneurs  
- Handmade product sellers  
- Local artisans  
- Small-scale brands  
- Independent creators  

---

## 🔮 Future Roadmap

- Inventory management dashboard  
- Sales & engagement analytics  
- WhatsApp Business integration  
- Multi-language caption generation  
- Custom brand theme selection  
- Marketplace integration  

---

## 🏗 Project Vision

BeyondHomes aims to empower small and home-based businesses by:

- Reducing digital complexity  
- Saving time  
- Improving online visibility  
- Creating professional marketing assets automatically  

From local homes to global audiences —  
**BeyondHomes helps businesses go beyond.**

---

## 🤝 Contributing

We welcome contributions!

1. Fork the repository  
2. Create a feature branch  
3. Submit a pull request  

---

## 📄 License

This project is licensed under the MIT License.

---

## 💬 Tagline

**BeyondHomes — Turning Product Photos into Powerful Marketing.**