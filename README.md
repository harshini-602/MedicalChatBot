# 🌟 Medical Advisor Chatbot 🤖💬  

The **Medical Advisor Chatbot** is an AI-powered healthcare assistant that provides users with instant medical information and guidance based on their queries. Built using **Streamlit, Ollama, and MedLLaMA 2**, this chatbot leverages **Natural Language Processing (NLP)** to offer symptom-based insights, health advice, and general medical knowledge.  

## 🚀 Features  
✅ **Real-Time Medical Advice** – Ask health-related questions and receive AI-generated responses.  
✅ **Conversational AI** – Engages in a seamless chat-like experience.  
✅ **Streamlit Web Interface** – Simple and interactive UI for user-friendly interactions.  
✅ **Integration with MedLLaMA 2** – Utilizes a specialized medical language model for better accuracy.  
✅ **Session Management** – Maintains chat history until reset.  
✅ **Reset Conversation** – Easily start a new session with the "Start Over" button.  

## 🛠️ Technologies Used  
- **Python** for backend logic  
- **Streamlit** for the web-based user interface  
- **Ollama** as the local AI inference engine  
- **MedLLaMA 2** for medical language understanding  
- **Requests** for API interactions  

## ⚙️ Installation & Setup  

### 1️⃣ Prerequisites  
Make sure you have the following installed:  
- Python (>= 3.8)  
- Ollama (running locally)  
- Streamlit  

### 2️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/medical-advisor-chatbot.git
cd medical-advisor-chatbot
```
### 3️⃣ Install Dependencies
Run the following command to install all required dependencies: 
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Chatbot
Make sure Ollama is running in the background, then start the Streamlit app:
```bash
streamlit run app.py
```

### 📝 How It Works
1️⃣ Users input health-related queries in the chat interface.
2️⃣ The chatbot processes the query using MedLLaMA 2 via Ollama.
3️⃣ The response is generated and displayed in the chat format.
4️⃣ Users can reset the conversation anytime with the "Start Over" button.

### ⚠️ Disclaimer
This chatbot is not a substitute for professional medical diagnosis or treatment. Always consult a certified healthcare provider for medical concerns.

