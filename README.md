# Generative-AI-with-Blockchain-Technology
Final year project
<br>
Group No.9

## 👥 Team

- **Tanay R. Tiwari** – Lead Developer & Research Author  
- **Shivam K. Yadao** – Second Developer (Core Functionality & Integration)  
- **Shubham B. Vaidya** – Testing & Optimization  
- **Pranjal R. Zode** – Documentation & PPT Module  
- **Sayyad Anasali** – UI/UX and Presentation  
- **Dr. Manisha Pise** – Project Guide, RCERT Chandrapur



🔐 Generative AI with Blockchain Integration
This project is a multi-modal Generative AI application that produces Text, Image, Speech, Video, and PPT outputs based on user prompts, with every generation securely logged using Blockchain. It offers a visual interface powered by Jupyter Widgets and utilizes state-of-the-art AI models like Gemini, Stable Diffusion, TTS, and ZeroScope.

🚀 Features
📝 Text Generation — via Google Gemini (Flash model)

🖼️ Image Generation — using Stable Diffusion v2

🔊 Speech Synthesis — via Coqui TTS and gTTS

🎬 Video Creation — powered by ZeroScope Diffusion

📊 PowerPoint Generation — using Wikipedia and python-pptx

🔗 Blockchain Logging — every user action is immutably recorded

📁 Excel Export — maintain blockchain records in an Excel sheet

🧠 Tech Stack
Module	Technology
Text Generation	google.generativeai (Gemini)
Image	diffusers, StableDiffusionPipeline
Audio	TTS, gTTS
Video	zeroscope_v2_576w
Blockchain	Custom Python Blockchain
UI	ipywidgets, IPython.display
Export	pandas, .xlsx

🖥️ Interface Preview
The app is entirely built using Jupyter Notebook UI and uses buttons and dropdowns to make selections for prompt input and content generation. Each generated output is saved locally and displayed inline.

📦 Installation
bash
Copy code
pip install torch diffusers transformers TTS gtts pandas pptx google-generativeai wikipedia ipywidgets
⚠️ Ensure you have GPU and CUDA support enabled (for Stable Diffusion and video generation).

🔑 API Key Required
To use Gemini, add your API key in this line:

python
Copy code
genai.configure(api_key="Enter your api key")
🧪 How It Works
User enters a prompt and selects a generation type.

Output is generated using the appropriate AI pipeline.

A record of the action (prompt, type, timestamp, filename) is added to a blockchain.

Blockchain can be exported to Excel and viewed interactively.

📤 Output Files
generated_text.txt, generated_image.png, generated_sound.wav, output.mp4, etc.

blockchain_records.xlsx: A persistent blockchain ledger of all generation actions.

