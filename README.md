# Prodigy InfoTech Internship – Generative AI  
## 🧠 Image Generation using Stable Diffusion

This repository contains the completed internship task under the **"Generative AI Internship Program"** by **Prodigy InfoTech**.

### 🎯 Task Objective:
Use a pre-trained generative AI model (Stable Diffusion) to generate high-quality images from creative text prompts.

---

### 🛠️ Tools & Technologies Used:
- 💡 **Stable Diffusion v1.4** (via Hugging Face Diffusers)
- 🚀 Google Colab with GPU Runtime
- 🧠 Transformers, Diffusers, Accelerate, Torch
- 🖼️ Python for inference and prompt engineering

---

### ✨ Generated Prompts:
1. **Realistic Indian City**
2. **Celestial Sanctuary**
3. **Digital Brain**
4. **AI Core Room**
5. **Futuristic Minimalism**
6. **Monk Floating Sphere**
7. **Temple in Clouds**
8. **Futuristic Cityscape**

Each prompt was designed to create visually engaging and meaningful images using AI.

---

### 📁 Folder Structure:
```
PRODIGY_IMAGE_GEN/
│
├── generate_images.py            # Python script to generate images from prompts
├── prompts/                      # Contains 8 text prompt files
│   ├── realistic_indian_city.txt
│   ├── celestial_sanctuary.txt
│   ├── digital_brain.txt
│   ├── ai_core_room.txt
│   ├── futuristic_minimalism.txt
│   ├── monk_floating_sphere.txt
│   ├── temple_in_clouds.txt
│   └── futuristic_cityscape.txt
│
├── generated_images/             # Folder for sample generated outputs (optional)
│   ├── image1.png
│   └── ...
│
└── README.md                     # This documentation file
```

---

### ▶️ How to Run:

1. Clone this repository  
2. Install required packages:

```bash
pip install diffusers transformers accelerate torch safetensors
```

3. Run the script:

```bash
python generate_images.py
```

Images will be saved in the `generated_images/` folder.

---

### 🙌 Author:
**Dharmit Shah**  
GitHub: [@dkshah25](https://github.com/dkshah25)  
Tech Enthusiast | Exploring AI, ML, and Creative Tech  
