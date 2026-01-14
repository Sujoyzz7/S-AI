# S-AI
S AI – An intelligent AI chatbot for smart conversations 🤖
S Ai is a modern, premium AI-powered chatbot application designed with a sleek, ChatGPT-inspired user interface. It offers a seamless and responsive experience across all devices, integrated with Firebase for secure authentication, subscription management, and user data synchronization.

## 🚀 Key Features

- **ChatGPT-Style UI**: A professional, clean, and interactive chat interface with a collapsible sidebar and centered message threading.
- **Cross-Platform Optimization**: Fully responsive design optimized for Mobile (iOS/Android), Mac, Windows, and Tablets.
- **Secure Authentication**: 
  - Email & Password sign-up/login.
  - One-tap **Google Login** integration.
- **Subscription Tiers**: Managed via Firestore, supporting Free, Pro ($19/month), and Enterprise ($49/month) plans.
- **User Profile Management**: Users can update their display names and view their account details from a secure settings modal within the sidebar.
- **Smart Theme Support**: Seamless Dark and Light mode switching with system preference detection.
- **Access Control**: Feature-gating based on user plans (e.g., Image Generation restricted to Pro users).

## 🛠️ Technology Stack

- **Frontend**: HTML5, Vanilla CSS3 (Custom styling), JavaScript (ES6+ Mobile-first approach).
- **Backend/Database**: [Firebase](https://firebase.google.com/)
  - **Firebase Auth**: User session management and social logins.
  - **Firestore**: Real-time user profiles, subscription status, and data storage.
- **Icons**: [Material Icons](https://fonts.google.com/icons)
- **Typography**: [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts.

## 📦 Setup & Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/ai-chatbot.git
   cd ai-chatbot
   ```

2. **Configure Firebase**:
   - Create a new project in the [Firebase Console](https://console.firebase.google.com/).
   - Enable **Authentication** (Email/Password and Google).
   - Enable **Firestore Database**.
   - Copy your Web Configuration into the `firebaseConfig` object in `index.html`, `login.html`, `signup.html`, and `pricing.html`.

3. **Run Locally**:
   - Simply open `index.html` in any modern web browser or use a "Live Server" extension in your IDE.

## 🎨 UI & UX Philosophy

This project prioritizes **Visual Excellence**. It features:
- Glassmorphism overlays on mobile.
- Custom refined scrollbars.
- Smooth CSS transitions and micro-animations.
- Intuitive layouts that feel premium and accessible.

## 📄 License

This project is open-source and available under the **MIT License**.

---
*Developed with focus on performance, security, and aesthetics.*
