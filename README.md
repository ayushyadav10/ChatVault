# ChatVault - AI-Powered Chat Application with Chat History

# Overview
**ChatVault** is an AI-powered chatbot application built using **Streamlit** and **Gemini 1.5 Pro**. This application allows users to ask questions and receive AI-generated responses in real time. Additionally, **ChatVault** stores previous chat history, enabling users to revisit past conversations seamlessly.

# Features
- **AI-Powered Chat**: Ask any question and get intelligent responses powered by **Gemini 1.5 Pro**.
- **Chat History Storage**: Automatically saves past conversations for easy reference.
- **User-Friendly Interface**: Built with **Streamlit** for a smooth user experience.
- **Fast & Efficient**: Uses **Gemini’s API** to deliver **quick and accurate** responses.

# Setup Instructions

## Prerequisites
Before setting up the project, ensure you have the following installed:
- Python 3.11.0 or later
- Pip (Python package manager)
- Virtual environment (recommended)

## Step 1: Clone the Repository
```bash
git clone https://github.com/ayushyadav10/ChatVault.git
cd ChatVault
```

## Step 2: Create a Virtual Environment
```bash
conda create -p venv python=3.11.0 -y
conda activate venv/
```

## Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

## Step 4: Set Up API Key
This project requires access to Google’s Gemini API.
1. Obtain an API key from [Google AI Studio](https://ai.google.dev/)
2. Create a `.env` file in the project root and add:
```ini
GEMINI_API_KEY=your_api_key_here
```

## Step 5: Run the Application
```bash
streamlit run app.py
```

# Usage
1. **Start a Conversation**: Enter a query in the chatbox and get instant AI responses.
2. **Access Chat History**: View and revisit previous conversations stored in the app.

# Folder Structure
```cmd
├── QAchat.py           # Main application script
├── requirements.txt    # Dependencies
├── .env                # API keys 
├── README.md           # Project documentation
```

# Technologies Used
- **Python**: Core programming language
- **Gemini 1.5 Pro**: AI model for text-based responses
- **Streamlit**: For interactive UI
- **Google AI API**: To integrate Gemini AI

## Contribution
Feel free to contribute! Follow these steps:
```bash
git fork
cd ChatVault
git checkout -b feature-xyz
git commit -m "Added new feature"
git push origin feature-xyz
```
Then create a **pull request**.

## License
This project is open-source and available under the **MIT License**.

## Contact
For questions or support, reach out via **aayusyadav1210@gmail.com** or open an issue in the repository.

---

🚀 **Happy Coding!** 🚀
