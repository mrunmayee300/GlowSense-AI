# GlowSense-AI
A next-gen AI-powered skincare diagnostic system that combines real-time computer vision, deep learning, and LLM-powered intelligence to give users accurate, actionable skin health analysis — beautifully and instantly.
##  Project Architecture: *"Skinsights, Structured"*

## ✨ What GlowSense-AI Does
Upload a selfie or skin image  
CV models detect **acne**, **wrinkles**, **dark circles**, **pigmentation**, etc.  
Computes a custom **Skin Health Index (SHI)** out of 100
LLM gives **personalized care advice & product suggestions**  
Instant results in a clean, beautiful UI

## 🧬 Skin Features Detected

| Feature         | Model Used           | Description                            |
|----------------|----------------------|----------------------------------------|
| Acne            |                     | Object detection on acne regions       |
| Pigmentation    |                     | Dark patch segmentation/classification |
| Wrinkles        |                     | Texture/ridge detection                |
| Skin Tone       |                     | Color deviation analysis               |
| Dark Circles    |                     | Under-eye brightness classification    |
| Skin Type       |                     | Oily, Dry, Combo categories            |

## LLM-Powered Skincare Insights
Using LangChain + GPT-4, the LLM interprets the SHI breakdown and provides:
 Scientific interpretation of skin health
 Personalized care routines (AM/PM)
 Product suggestions based on skin type
 Tips to improve SHI score over tim

 ## Tech Stack
Layer	Tools Used
CV Models	YOLOv8, MobileNet, UNet
Preprocessing	OpenCV, LabelImg, Roboflow
LLM Engine	LangChain, OpenAI GPT-4
Frontend	Streamlit, Matplotlib, Plotly
Backend (opt)	FastAPI or Flask (optional)
Data Tools	Pandas, NumPy, JSON, YAML

## 🧑‍💻 Team Credits
|Name	               | Role                                                 |
|--------------------|------------------------------------------------------|
|Sumanth Kotikalapudi|	LLM Engine, SHI Logic, Architecture, README         |
|Mrunmayee Sangode   |	CV Model Training, UI/UX, Preprocessing Pipelines   |

## Future Features
 AR-based skin overlays (via face mesh) , 
 Multi-day skin progress tracker , 
 Community feedback & sharing , 
 Product marketplace integration

## MADE WITH PURE PASSION 
*Sumanth & Mrunmayee*
