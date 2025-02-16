# **🎭 AI Meme Generator using Stability AI by Nebius**  

## **📌 Overview**  
The **AI Meme Generator** is a web app that allows users to generate **hilarious AI-powered memes** using **Stability AI by Nebius**. Just enter a **meme prompt**, let AI generate an image, and instantly **share it on social media** or **copy the shareable link**.  

🚀 **Features:**  
✅ **Generate memes using Stability AI by Nebius**  
✅ **Instantly share memes on Facebook, Twitter, WhatsApp, and LinkedIn**  
✅ **Download memes to your device**  
✅ **Clickable shareable link with a copy-to-clipboard feature**  
✅ **Fast, simple, and fun user experience**  

---

## **📸 Demo**  
![AI Meme Generator](./data/this_cat_wearing_this_hat_and_winks_seed1619780705.mp4)  
> _Example meme generated by AI_

---

## **🛠 Tech Stack**  
- **Frontend:** React, Chakra UI, Axios, react-share  
- **Backend:** FastAPI, Stability AI / Nebius API  
- **Hosting:** Can be deployed on **Vercel, Netlify, Heroku, or AWS**  

---

## **🚀 Getting Started**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/ai-meme-generator.git
cd ai-meme-generator
```

### **2️⃣ Backend Setup (FastAPI)**  

#### **📌 Install Dependencies**
```bash
pip install fastapi uvicorn requests pydantic
```

#### **📌 Start the FastAPI Server**
```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

✅ The backend should now be running at **http://localhost:8000**  

---

### **3️⃣ Frontend Setup (React)**  

#### **📌 Install Dependencies**
```bash
cd frontend
npm install
npm install react-share
```

#### **📌 Start the React App**
```bash
npm start
```

✅ The frontend should now be running at **http://localhost:3000**  

---

## **🖼 How It Works**  

### **Step 1: Enter a Meme Prompt**  
Type in a funny text description for your meme, e.g.,  
> `"A cat wearing sunglasses and drinking coffee"`  

### **Step 2: Generate Meme**  
Click **"Generate Meme"**, and the AI will create an image based on your prompt.  

### **Step 3: Share & Download**  
- **Click the shareable link** to open the meme  
- **Copy the link** to share manually  
- **Use the social media buttons** to share on Facebook, Twitter, WhatsApp, and LinkedIn  
- **Download** the meme to your device  

---

## **🌐 API Endpoints (FastAPI Backend)**  

### **🔹 `POST /generate_image`**
**Request:**  
```json
{
  "prompt": "A cat with sunglasses",
  "width": 1024,
  "height": 1024,
  "num_inference_steps": 50,
  "negative_prompt": "",
  "seed": 42
}
```

**Response:**  
```json
{
  "image_url": "https://ai-generated-memes.com/generated-cat.png"
}
```

---

## **📌 Example `.env` File (Backend API Key)**
```env
API_KEY=your-stability-ai-api-key
```

---

## **🛠 Deployment Guide**  

### **1️⃣ Deploy Backend (FastAPI) on Heroku**  
```bash
heroku create ai-meme-generator-backend
git push heroku main
```

### **2️⃣ Deploy Frontend (React) on Vercel**  
```bash
npm install -g vercel
vercel --prod
```

---

## **📢 Future Enhancements**  
🔹 Add AI-powered text overlay for memes  
🔹 Enable meme history & favorites  
🔹 Support video meme generation  

---

## **👨‍💻 Contributing**  
1. **Fork** the repository  
2. **Create a new branch** (`git checkout -b feature-name`)  
3. **Commit changes** (`git commit -m "Added feature"`)  
4. **Push** to GitHub (`git push origin feature-name`)  
5. **Submit a PR** 🎉  

---

## **📜 License**  
MIT License © 2024 AI Meme Generator  

---

## **💬 Contact**  
📧 **Email:** cats@cats.com
🐱 **GitHub:** [Sako M](https://github.com/sakomws)  
🌐 **Website:** [morecats.](https://cats.ai)  

🎨🔥 _Have fun generating AI-powered memes!_ 🚀😺  
