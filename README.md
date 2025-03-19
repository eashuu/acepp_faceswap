### **Ace++ Face Swapping with ComfyUI**  
🚀 **Seamless & High-Quality Face Swapping Using ACE++ & TeaCache**  

![Project Banner](your-image-url-here)  

## **📌 Overview**  
This repository contains a **ComfyUI workflow** designed for **high-quality face swapping** using:  
- **ACE++ Model** for preserving facial identity & realism.  
- **Flux 1 Fill FP8** for precise inpainting.  
- **Turbo LoRA** for efficient image generation.  
- **TeaCache** to speed up inference without sacrificing detail.  

The workflow ensures **consistent character appearance** across generations **without extra training**, making it ideal for **AI-powered face swaps**.  

---

## **🛠️ Models Used**  
### **1️⃣ ACE++ Model (Hugging Face)**  
🔹 **Type:** LoRA Model (Low-Rank Adaptation)  
🔹 **Purpose:** Enhances **portrait quality, facial details, and lighting** for realistic face swaps.  
🔹 **File:** `comfyui_portrait_lora64.safetensors`  

### **2️⃣ Flux Fill FP8 (CivitAI)**  
🔹 **Type:** Diffusion Model  
🔹 **Purpose:** **Inpainting model** for refining swapped faces with smooth blending.  
🔹 **File:** `fluxFillFP8_v10.safetensors`  

### **3️⃣ Flux1 Turbo Alpha LoRA (CivitAI)**  
🔹 **Type:** LoRA Model  
🔹 **Purpose:** **Boosts generation speed** while maintaining high-quality output.  
🔹 **File:** `FLUX.1-Turbo-Alpha.safetensors`  

### **4️⃣ TeaCache - Timestep Embedding Aware Cache**  
🔹 **Type:** Training-Free Caching Mechanism  
🔹 **Purpose:** **Speeds up inference** by optimizing model fluctuations across timesteps.  

---

## **⚡ Features**  
✔️ **Retains original face details** while swapping.  
✔️ **No need for extra training**—consistent results every time.  
✔️ **Works out-of-the-box** with minimal setup.  
✔️ **Faster inference with TeaCache**.  
✔️ **Smooth blending & natural-looking swaps**.  

---

## **📂 Installation & Setup**  

### **🔹 Step 1: Clone the Repository**  
```bash
git clone https://github.com/yourusername/AcePlusPlus-FaceSwap.git
cd AcePlusPlus-FaceSwap
```

### **🔹 Step 2: Install Dependencies**  
Make sure you have **ComfyUI** installed. Then, download the required models:  
- **[ACE++ Model](your-download-link-here)**  
- **[Flux Fill FP8](your-download-link-here)**  
- **[Flux1 Turbo Alpha LoRA](your-download-link-here)**  
- **[TeaCache Integration](your-download-link-here)**  

Place them in the `models/` directory inside **ComfyUI**.  

### **🔹 Step 3: Run ComfyUI**  
```bash
python main.py
```

---

## **📜 How It Works**  
1️⃣ Load your **input image** in ComfyUI.  
2️⃣ The **TeaCache system** caches and processes timestep fluctuations.  
3️⃣ The **ACE++ model** swaps and blends faces while keeping identity intact.  
4️⃣ **Flux Fill FP8** ensures smooth **face replacement**.  
5️⃣ **Turbo LoRA** speeds up the inference process.  
6️⃣ The final **high-quality swapped image** is generated! 🎭  

---

## **📢 Contribute**  
Feel free to fork this repository, submit pull requests, or open issues if you have suggestions or improvements! 🚀  

---

## **📩 Contact**  
📧 **Your Email**: your.email@example.com  
🔗 **LinkedIn**: [Your Profile](your-linkedin-url)  
🐦 **Twitter/X**: [@YourHandle](your-twitter-url)  

---

## **📜 License**  
This project is licensed under the **MIT License**.  

---
