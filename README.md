# 🌌 Nebula Nexus - AI Trivia

![Status](https://img.shields.io/badge/Status-Active-cyan?style=for-the-badge)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

**Nebula Nexus** is a futuristic, sci-fi-themed trivia application powered by **Google Gemini AI**. Unlike traditional trivia games with static databases, Nebula Nexus generates unique questions on the fly based on *any* topic the user inputs.

> "Your neural network performance has been analyzed."

---

## 📸 Interface

| Start Screen | Quiz Interface |
|:---:|:---:|
| <img src="./Screenshot%202025-11-30%20194121.jpg" width="100%" alt="Start Screen"> | <img src="./Screenshot%202025-11-30%20194155.png" width="100%" alt="Quiz Interface"> |

---

## ✨ Key Features

* **🤖 Infinite AI Generation:** Utilizes Google's Gemini 2.5 Flash model to generate 15 unique, multiple-choice questions on any topic provided (e.g., "Space", "History", "Fortnite").
* **🎨 Sci-Fi Aesthetic:** Innovative "Glassmorphism" UI, neon glowing effects, and a responsive layout.
* **🌌 Animated Background:** Features a custom HTML5 Canvas starfield animation with depth and parallax effects.
* **⚡ Fallback System:** Includes a built-in offline mode with fallback questions if the API fails or is unreachable.
* **💾 Local Storage:** Users can securely save their personal API keys in the browser's local storage.
* **📱 Fully Responsive:** Optimized for desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

* **Language:** HTML5, JavaScript (ES6+)
* **Styling:** Tailwind CSS (CDN)
* **AI Integration:** Google Gemini API (REST)
* **Icons:** FontAwesome

---

## 🚀 Getting Started

Since Nebula Nexus is built with vanilla HTML and JS, it is incredibly easy to run.

### Prerequisites

* A modern web browser (Chrome, Firefox, Edge, Safari).
* (Optional) A Google Gemini API Key for custom topic generation.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Anirudh-bit-21/1st-sem-project.git](https://github.com/Anirudh-bit-21/1st-sem-project.git)
    ```
2.  **Navigate to the folder:**
    ```bash
    cd 1st-sem-project
    ```
3.  **Run the App:**
    Simply double-click `index.html` to open it in your browser.

---

## 🔑 Configuration (API Key)

To use the AI generation features, the app requires a Google Gemini API key.

1.  Get a free API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  Open **Nebula Nexus** in your browser.
3.  Click the **Settings Gear (⚙️)** in the top right corner.
4.  Paste your API Key and click **Save**.
    * *Note: The key is stored locally in your browser (localStorage) and is never sent to any server other than Google's API.*

---

## 🧠 How It Works

1.  **Input:** The user enters a topic (e.g., "Quantum Physics").
2.  **Prompt Engineering:** The app constructs a specific prompt asking Gemini to return a strict JSON array containing questions, options, and the correct answer index.
3.  **Parsing:** The response is parsed using JavaScript, and if valid, the game begins.
4.  **Error Handling:** If the AI is hallucinating non-JSON text or the network fails, the app seamlessly switches to a hardcoded fallback set of questions.

---

## 📄 License

This project is open source.

---

*Built with 💻 and ☕ by Anirudh*
