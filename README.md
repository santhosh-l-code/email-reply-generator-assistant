
# 📬 Email Reply Generator Assistant

This is a local project combining a **Spring Boot backend** and a **Chrome extension** to generate smart AI-based email replies for Gmail.

---

## 🧩 How It Works

- Spring Boot project serves as a local API to generate smart replies.
- Chrome Extension interacts with Gmail and calls the local API to generate replies.
- Works entirely offline on your system. No deployment required.

---

## 🛠️ How to Run

### 1. Spring Boot Backend

1. Download or clone the repository.
2. Navigate to the `spring-boot-backend` folder.
3. Run the backend with:
   ```bash
   ./mvnw spring-boot:run
   ```
4. The API will run on `http://localhost:8080`.

### 2. Chrome Extension

1. Open Chrome and go to: `chrome://extensions/`
2. Enable **Developer Mode** (top-right).
3. Click **Load unpacked**.
4. Select the `chrome-extension` folder.
5. Open Gmail and use the extension to generate AI replies.

---

## ✅ Notes

- This project runs locally and does not require any server deployment.
- Works with Gmail website only.
- Requires Java + Maven installed on your system.

---

## 👨‍💻 Author

**Santhosh L**

📎 [LinkedIn](https://www.linkedin.com/in/your-profile)

---

## 🔗 GitHub

[https://github.com/santhosh-l-code/email-reply-generator-assistant](https://github.com/santhosh-l-code/email-reply-generator-assistant)
