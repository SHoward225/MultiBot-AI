# 🤖 MultiBot-AI - Chatbot IA Multimodal Open-Source

### Un assistant IA local et multimodal 📄🎙️🖼️

[![LangChain](https://img.shields.io/badge/LangChain-%F0%9F%A4%96-blue)](https://github.com/hwchase17/langchain)
[![Streamlit](https://img.shields.io/badge/Streamlit-%E2%9C%A8-red)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen)](https://www.python.org/)
[![Open-Source](https://badgen.net/badge/Open%20Source/Yes/green)](https://github.com/TON-USERNAME/MultiBot-AI)

---

## 🎯 **Présentation**
**MultiBot-AI** est une application **open-source** qui permet d'exécuter un chatbot IA **localement**, sans dépendance aux services cloud. Il repose sur **LangChain, Streamlit et des modèles de langage open-source**, offrant des fonctionnalités avancées telles que :

✅ **Chat IA local** : conversation en langage naturel avec un modèle LLM open-source  
✅ **Analyse de fichiers PDF** : extraction et interrogation de contenu  
✅ **Reconnaissance de texte dans les images (OCR)** : lecture de texte à partir d'images  
✅ **Traitement audio** : reconnaissance et synthèse vocale avec Whisper & TTS  
✅ **Exécution locale** : confidentialité garantie sans dépendance cloud  

🔹 **Pourquoi MultiBot-AI ?**  
💡 Confidentialité garantie – aucune donnée envoyée à un serveur externe.  
🚀 IA Multimodale – Texte, PDF, images et audio dans une seule application.  
🛠️ Open-Source – Code libre et modifiable pour l'améliorer selon vos besoins.  

---

## 🛠 **Technologies Utilisées**
- **LangChain** - Orchestration de modèles de langage  
- **Streamlit** - Interface utilisateur interactive  
- **Transformers (Hugging Face)** - Modèles open-source  
- **PyPDFium2** - Extraction de texte à partir de PDF  
- **Tesseract OCR** - Reconnaissance de texte sur images  
- **Whisper / SpeechRecognition** - Traitement de la voix  

---

## 🚀 **Installation & Utilisation**

### 1️⃣ **Installation**
Assurez-vous d'avoir **Python 3.10+** installé.

```bash
# Cloner le projet
git clone https://github.com/SHoward225/MultiBot-AI.git
cd MultiBot-AI

# Créer et activer un environnement virtuel
python3 -m venv chat_venv
source chat_venv/bin/activate  # Sur Windows: chat_venv\Scripts\activate

# Installer les dépendances
pip install --upgrade pip
pip install -r requirements.txt
