# **Smart To-Do Manager**

A modern, AI-powered to-do list application that helps you organize your tasks efficiently. This web app is built with HTML, Tailwind CSS, and vanilla JavaScript, and it leverages Firebase for real-time data storage and the Gemini API for its intelligent features.

## **✨ Features**

* **Full CRUD Functionality:** Create, Read, Update (mark as complete), and Delete tasks.  
* **Real-time Database:** All tasks are saved instantly to a personal and secure Firestore database. Your tasks will be waiting for you when you return.  
* **Vibrant & Responsive UI:** A lively, energetic interface with animated gradients and a modern frosted-glass effect that looks great on all devices.  
* **AI-Powered Task Suggestions:** Describe a high-level goal (e.g., "Learn a new language"), and the AI will generate a list of actionable sub-tasks.  
* **AI Task Prioritization:** Automatically analyzes your pending tasks and assigns a "High," "Medium," or "Low" priority to each one.  
* **AI Daily Summary:** Get a concise, one-paragraph summary of all your pending tasks to plan your day.  
* **AI Task Breakdown:** Break down a large, complex task into smaller, more manageable steps with a single click.

## **🛠️ Tech Stack**

* **Frontend:** HTML, Tailwind CSS, Vanilla JavaScript  
* **Backend & Database:** Firebase (Firestore for database, Authentication for anonymous users)  
* **AI Model:** Google's Gemini API

## **🚀 Getting Started**

To run this project locally or deploy it yourself, follow these steps.

### **Prerequisites**

* A web browser  
* A code editor like VS Code  
* A Google account to create Firebase and Gemini API keys

### **Local Setup**

1. **Clone the repository:**  
   git clone \[https://github.com/YOUR\_USERNAME/smart-todo-manager.git\](https://github.com/YOUR\_USERNAME/smart-todo-manager.git)  
   cd smart-todo-manager

2. **Create your configuration file:**  
   * In the root of the project, create a new file named config.js.  
   * Copy the contents of config.example.js into your new config.js file.  
3. **Set up Firebase:**  
   * Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.  
   * Register a new web app (**\</\>**) and copy the firebaseConfig object.  
   * Enable **Anonymous Authentication** in the "Authentication" \> "Sign-in method" tab.  
   * Create a **Firestore Database** and start it in "test mode".  
   * Paste your firebaseConfig object into the firebaseConfig constant in config.js.  
4. **Set up Gemini API Key:**  
   * Go to [Google AI Studio](https://aistudio.google.com/) and create a new API key.  
   * Copy the key and paste it as the value for the GEMINI\_API\_KEY constant in config.js.  
5. **Run the application:**  
   * Open the todo\_app.html file in your browser. Using a live server extension in VS Code is recommended for the best experience.

### **Deployment**

This project can be easily deployed using services like GitHub Pages, Vercel, or Netlify. Since the config.js file (containing your API keys) is not committed to Git, you will need to configure your API keys as environment variables in your hosting provider's settings.

This project was built to demonstrate modern web development practices, including the integration of powerful AI features into a user-friendly application.