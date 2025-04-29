# Yuvraj_Saini_FSD1_MentalAwarenessChatbot
# 🌱 GlowMinds – A Mental Awareness Chatbot

## 👥 Team Members
- Yuvraj (Developer, Designer) [2401350008]
- Rashi (Front end Developer)  [2401350003]
- Sanjeev (Database and Backend) [2401350006]
- Abhay (research , resources) [2401350005]

## 🧠 Project Description
GlowMinds is a mental awareness chatbot that offers real-time emotional support and helpful mental health resources. Designed with empathy and simplicity in mind, it allows users to engage in conversation around their feelings—whether they’re dealing with stress, anxiety, burnout, or simply looking for wellness tips.

The chatbot integrates a custom-trained Dialogflow agent to respond meaningfully to user input, offering both general mental health advice and India-specific resources, including hotline numbers.

> 🎥 **Video Explanation:** [https://drive.google.com/file/d/1Eaxv76b_vpVcdSGO8Jnuh_lHvJDUHTMz/view?usp=drivesdk]

---

## 🛠️ Technologies Used

### 💻 Frontend
- HTML5
- CSS3 (custom styles for chat layout and responsiveness)
- JavaScript
- Socket.io (Client-side)

### 🌐 Backend
- Node.js
- Express.js
- Socket.io (Server-side)
- Dialogflow API (Google Cloud)
- Git & GitHub (Version control)

---

## 🚀 How to Run the Project Locally

### 1. Clone the repository
```bash
git clone https://github.com/Yuvraj22-game/glowminds-yuvraj.git
cd glowminds-yuvraj
Install dependencies
```
### 2.Install dependencies

```bash

npm install
```
### 3.Add your Dialogflow Service Account Key
```
Create a file named .env in the root directory.

Add your credentials securely:

GOOGLE_APPLICATION_CREDENTIALS=glowmindsagent-xxxx.json
🔒 Make sure this file is included in your .gitignore.
```
### 4.Start the server
```
node server.js
```
### 5.Visit in browser
```
Open http://localhost:3000 in your browser.

