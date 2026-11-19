# 🌿 MindCare – AI Personal Wellness Assistant

MindCare is an AI-powered personal wellness assistant built using Python and Streamlit. It provides a supportive conversational experience where users can discuss everyday stress, study pressure, personal concerns, and healthy habits.

The application uses Google's Gemini API to generate responses and supports optional PDF uploads for document-based conversations.

## ✨ Features

- **AI Chat Assistant:** Chat with an AI-powered wellness assistant.
- **PDF Support:** Upload PDF documents and ask questions based on their content.
- **Multiple Conversations:** Create and manage multiple chat sessions.
- **Chat History:** Save conversations using SQLite.
- **Automatic Chat Titles:** Generate titles from the first user message.
- **Rename Chats:** Edit saved conversation titles.
- **Delete Chats:** Remove unwanted conversations.
- **Loading Indicator:** Display a loading message while AI generates responses.
- **Error Handling:** Handle API errors with user-friendly messages.
- **Responsive Interface:** Simple and clean interface built with Streamlit.

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- Google Gen AI SDK
- SQLite
- PyPDF
- Python-dotenv

## 📁 Project Structure

```text
MindCare/
│
├── app.py
├── mindcare.db
├── api_key.env
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/pushpakumawat695-web/MindCare-AI-Wellness-Assistant.git
```

### 2. Open the project folder

```bash
cd MindCare
```

### 3. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure your API key

Create a file named `api_key.env` in the project folder.

Add your Google Gemini API key:

```env
GOOGLE_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your own API key.

### 6. Run the application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🗄️ Database

MindCare uses SQLite to store:

- Chat details
- Conversation titles
- User messages
- AI-generated responses
- Message timestamps

## 🔐 Privacy and Safety

- API keys should be kept private.
- The application provides general wellness support and does not diagnose medical conditions.
- It does not prescribe medication or replace professional mental health support.
- Local SQLite conversation data is not encrypted in the current implementation.

## 🚀 Future Enhancements

- Mood tracking and journaling.
- Improved conversation management.
- Chat export functionality.
- Enhanced privacy and data protection.
- Deployment to a cloud hosting platform.

## 👩‍💻 Author

**Pushpa Kumawat**

Project: MindCare – AI Personal Wellness Assistant

## 📌 Project Status

Core application features implemented and tested locally.