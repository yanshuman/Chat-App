# 💬 Chat App

A simple browser-based chat application built using **HTML, CSS, and JavaScript**. This application enables real-time communication between browser tabs using the **BroadcastChannel API** and stores messages locally using **IndexedDB**, requiring no backend server.

## 🚀 Features

- User login with custom username
- Real-time messaging between browser tabs
- Local message storage using IndexedDB
- Persistent chat history after page refresh
- Modern and responsive user interface
- Message timestamps
- Change user functionality
- No external libraries or frameworks required
- Secure message rendering to prevent HTML injection

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- IndexedDB
- BroadcastChannel API
- LocalStorage

---

## 📋 How It Works

### User Login
- Users enter a username before joining the chat.
- Username is saved in LocalStorage.
- Returning users are automatically logged in.

### Message Storage
- Messages are stored locally in IndexedDB.
- Chat history persists even after refreshing the page.
- Messages are loaded in chronological order.

### Real-Time Communication
- BroadcastChannel API allows instant communication between browser tabs.
- No server or internet connection is required.

---

## 📂 Project Structure

```text
chat-app/
│
├── index.html
├── README.md
│
├── HTML Structure
├── CSS Styling
└── JavaScript Logic
    ├── User Authentication
    ├── IndexedDB Storage
    ├── BroadcastChannel Messaging
    ├── Message Rendering
    └── Event Handling
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/chat-app.git
```

2. Navigate to the project directory:

```bash
cd chat-app
```

3. Open `index.html` in your browser.

No build tools or dependencies are required.

---

## 🎯 Usage

1. Open the application in your browser.
2. Enter a username and click **Join**.
3. Open the same page in another tab.
4. Enter a different username.
5. Start chatting in real time.

---

## 📊 Message Object Structure

```javascript
{
  id: "unique-id",
  sender: "John",
  text: "Hello World!",
  timestamp: 1710000000000
}
```

---

## 🔒 Security

The application sanitizes all user input before displaying messages.

```javascript
function escapeHtml(text) {
  const div = document.createElement('div');
  div.textContent = text;
  return div.innerHTML;
}
```

This helps prevent Cross-Site Scripting (XSS) attacks.

---

## 🌐 Browser Support

Supported browsers:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Opera

Required browser features:

- IndexedDB
- BroadcastChannel API
- LocalStorage

---

## ⚠️ Limitations

- Works only between tabs/windows of the same browser and origin.
- No backend server.
- No user authentication system.
- No online status indicator.
- No file sharing.
- Chat history is stored only on the local device.

---

## 🔮 Future Enhancements

- Dark mode
- Emoji support
- Private messaging
- Online user list
- Message editing and deletion
- File and image sharing
- WebSocket backend integration
- User accounts and authentication

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed as a lightweight chat application demonstrating the use of IndexedDB and BroadcastChannel APIs in modern web browsers.
