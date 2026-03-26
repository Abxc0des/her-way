# SafeNav (Her-Way)

SafeNav is an AI-powered personal safety co-pilot designed to provide intelligent routing, proactive alerts, and an instant connection to help when users need it most.

## 🚀 Getting Started

To link this project to your GitHub repository, run the following command in your local terminal:

```bash
git remote add myfork https://github.com/Abxc0des/Her-way.git
```

## ✨ Core Features

- **Intelligent Safety Routing**: Calculates the safest path to a destination by analyzing real-time data and avoiding "Red Zones."
- **Guardian Network**: Allows users to assign trusted contacts who receive live location and status updates during emergencies.
- **SOS Mode & Live Feed**: A dedicated emergency interface that shares live video, audio, and location data with guardians.
- **Hands-Free Distress Detection**: AI-powered analysis of microphone and motion sensor data to detect potential emergencies automatically.
- **Safety Check-in**: A timed check-in system that escalates to SOS mode if the user does not confirm their safety.
- **Community Safety Feed**: A real-time feed for users to share and view localized safety updates (e.g., poor lighting, road closures).

## 🛠️ Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS & ShadCN UI
- **AI Engine**: Google Gemini (via Genkit)
- **Backend**: Firebase (Authentication & Firestore)
- **Icons**: Lucide React

## 🛡️ Guardian Portal

Guardians have a dedicated entry point at `/login/guardian` to monitor their connections' safety status and respond to active SOS events.
