 📬 Email Reply Generator Assistant

A Chrome extension integrated with a Spring Boot backend to generate **smart email replies** directly within **Mail.com**.

This project runs **locally** and demonstrates the integration between frontend browser technologies and Java-based backend services.

---

## 🚀 Features

- ✅ Chrome Extension UI with easy Mail.com integration  
- ✅ Spring Boot backend serving smart auto-replies via REST API  
- ✅ Content script injection into Mail.com for enhanced automation  
- ✅ Locally hosted and fully functional without deployment  

---

## 🗂️ Project Structure

email-reply-generator-assistant/
│
├── chrome-extension/ # Chrome Extension files (manifest, scripts, popup, etc.)
│ ├── manifest.json
│ ├── popup.html
│ ├── popup.js
│ └── ...
│
├── spring-boot-backend/ # Java Spring Boot REST API
│ ├── src/
│ ├── pom.xml
│ └── ...
│
└── README.md # You're reading it!


## 💻 How to Run This Project Locally

### 🔹 1. Run the Spring Boot Backend

This backend provides the API that generates smart email replies.

#### Steps:
```bash
cd spring-boot-backend
./mvnw spring-boot:run
The API will run locally at: http://localhost:8080
```
🔹 2. Load the Chrome Extension in Developer Mode
This extension integrates with your Mail.com inbox and uses the backend API.

Steps:
Open Chrome and go to: chrome://extensions/

Enable Developer Mode (toggle in top-right corner)

Click Load unpacked

Select the chrome-extension/ folder inside the project

Visit your Mail.com inbox — the extension should activate (via popup or UI injection)

💡 Make sure the extension has permission to run on https://mail.com/* in manifest.json.

🧪 Demo
🎥 A demo video of this project is available in my LinkedIn post:
👉 Watch the Demo on LinkedIn

🔗 GitHub Repository
👉 https://github.com/santhosh-l-code/email-reply-generator-assistant

🙋 Author
Santhosh L
📧 Open to feedback and collaborations!
🖇️ LinkedIn
