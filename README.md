# 🌸 Lily – Your Notion Assistant Chatbot  
A Dialogflow-based AI chatbot that helps you manage your **tasks, deadlines, notes, reminders, and schedules** using natural conversation.  
Built as a personal Notion guide to stay organized and productive.  

---

## ✨ Features

- 📌 Add tasks with deadlines  
- ✏️ Update or delete existing tasks  
- 🗂 View daily, weekly, or project-based tasks  
- 🧠 Create notes instantly  
- ⏰ Set reminders  
- 📅 Get schedule summaries  
- 🤝 Friendly conversational responses  
- 💬 Built with Dialogflow (No-Code)

---

## 🧠 Intents Included

### 📝 Task Management  
- Add Task  
- Update Task  
- Delete Task  
- Mark as Completed  
- View Tasks  
- Weekly/Daily Schedule  

### 🔔 Reminders  
- Set Reminders by date/time  

### 🗒 Notes  
- Create Note  
- Store Quick Notes  

### 📚 Productivity Support  
- Ask Lily to organize your week  
- Get suggestions for planning  
- Ask general guidance  

---

## 🏗 Entities Used
- `@task_name` – Name of the task  
- `@sys.date` – Built-in date  
- `@sys.time` – Built-in time  
- `@sys.datetime` – Combined date/time  
- `@priority` – high / medium / low  
- `@project_name` – (optional) college, personal, internship  

---

## 📂 Project Structure

```
lily-notion-chatbot/
│
├── README.md
│
├── dialogflow-agent/
│   ├── agent.json
│   ├── intents/
│   └── entities/
│
└── demo/
    └── lily-demo.mp4
```

---

## 🚀 How to Use This Project

### **1. Import into Dialogflow**
1. Open Dialogflow  
2. Create new agent  
3. Go to **Settings → Export and Import**  
4. Click **Import from ZIP**  
5. Upload the provided agent folder  

---

## 🎥 Demo  
A short screen recording demonstrating the chatbot conversation is available in the `demo` folder:  
`demo/lily-demo.mp4`

---

## 🛠 Tools Used
- **Dialogflow ES**  


---

## 🤝 Future Improvements
- Full Notion API integration  
- Real-time reminders  
- Task sync across devices  
- Telegram/WhatsApp deployment  

---

## 💡 Author
Built by **Kavya**, a learner exploring AI, chatbot building, and productivity tools. And completing task 3 of the Future intern

