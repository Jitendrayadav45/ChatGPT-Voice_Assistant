# ChatGPT-Voice_Assistant
ChatGPT Voice Assistant is an AI-powered web application that combines voice recognition and OpenAI’s GPT-3.5-turbo model to deliver smart, real-time conversational experiences. This project enables users to interact with GPT using their voice, creating a seamless and natural user experience.


🛠️ Features
Voice Recognition: Transcribes user speech into text using the Web Speech API.
AI-Powered Responses: Generates intelligent, context-aware answers with OpenAI's GPT-3.5-turbo.
Modern UI/UX: Responsive and clean interface designed with Bootstrap 4.
Interactive Chat Logs: Displays questions and responses dynamically on the screen.
Real-Time Processing: Converts speech to text, processes it, and delivers AI responses instantly. 


🌐 Tech Stack
Frontend: HTML, CSS, Bootstrap
Backend: Node.js, Express.js
AI Integration: OpenAI API
Hosting: Deployed on Replit


🚀 How It Works
Start: Click the "Start" button to activate the voice recognition feature.
Speak: Ask a question or make a request using your voice.
Response: The system sends the transcribed text to GPT-3.5-turbo and displays the AI's response.


🧩 Dependencies
OpenAI API
Express.js
Web Speech API (Browser Support Required)
Bootstrap 4


🎯 Use Cases
Voice-activated personal assistants
Educational tools for interactive learning
Customer support systems


📦 Setup
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/chatgpt-voice-assistant.git  


Navigate to the project directory:
bash
Copy code
cd chatgpt-voice-assistant 


Install dependencies:
bash
Copy code
npm install  


Set up your OpenAI API key in the main.js file:
javascript
Copy code
const openai = new OpenAI({  
  apiKey: "your-openai-api-key",  
});  


Run the server:
bash
Copy code
node app.js  
Open localhost:3000 in your browser to access the application.


📜 License
This project is licensed under the MIT License.


