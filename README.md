# **Smart To-Do Manager**

A modern, single-file, AI-powered to-do list application that helps you organize your tasks efficiently. This web app is built with HTML, Tailwind CSS, and vanilla JavaScript. It features a secure, interactive setup for API keys that keeps your secrets off of GitHub.

## **✨ Features**

* **Zero-Backend Setup:** The app uses Firebase and the Gemini API but requires no complex backend deployment. It runs entirely in the browser.  
* **Interactive API Key Setup:** On first launch, the app prompts you for your API keys and saves them securely to your browser's local storage, ensuring keys are never hardcoded or exposed.  
* **Full CRUD Functionality:** Create, Read, Update (mark as complete), and Delete tasks.  
* **AI-Powered Features:**  
  * **Suggest Tasks:** Describe a goal and get a list of actionable to-do items.  
  * **Prioritize Tasks:** Automatically assign "High," "Medium," or "Low" priority to your tasks.  
  * **Summarize Your Day:** Get a concise summary of all your pending tasks.  
  * **Break Down Tasks:** Turn a large task into smaller, manageable steps.  
* **Real-time & Persistent:** All tasks are saved instantly to your personal and secure Firestore database.

## **🛠️ Tech Stack**

* **Frontend:** HTML, Tailwind CSS, Vanilla JavaScript  
* **Backend & Database:** Firebase (Firestore for database, Authentication for anonymous users)  
* **AI Model:** Google's Gemini API

## **🚀 Getting Started**

This project is designed to be incredibly simple to set up and run.

### **Setup**

1. **Download the Code:** You only need the todo\_app.html file.  
2. **Open the File in Your Browser:** Simply double-click todo\_app.html or open it from your code editor (using a Live Server extension is recommended for the best experience).  
3. **Follow On-Screen Instructions:** A setup modal will appear automatically.  
   * Go to the [Firebase Console](https://console.firebase.google.com/) to get your firebaseConfig object.  
   * Go to [Google AI Studio](https://aistudio.google.com/) to get your Gemini API Key.  
   * Paste these keys into the setup form and click "Save".

The app will start immediately, and you won't need to enter the keys again on that browser. It's that simple\!

This project demonstrates a secure method for handling API keys in a client-side, single-file application, making it easy to share and demonstrate without compromising security.