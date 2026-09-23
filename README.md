# JARVIS-X

### AI-Powered Desktop Voice Assistant

JARVIS-X is a Python-based desktop AI assistant developed as a college mini project.

It combines an AI API, voice input, voice output, wake-word detection, memory, basic computer controls, and a desktop graphical interface into one assistant.

---

## 🚀 Project Overview

JARVIS-X is designed to provide a simple AI assistant experience on a Windows desktop.

The assistant can:

- Answer questions using an AI API
- Accept typed questions
- Accept voice commands
- Respond using voice
- Detect the wake word "Hey JARVIS"
- Remember user-provided information
- Open supported websites
- Open basic Windows applications
- Perform basic PC controls
- Provide a graphical desktop interface
- Communicate with a FastAPI backend

---

## ✨ Features

### 1. AI Chat

Users can type questions into the JARVIS-X desktop interface.

The request is sent to the backend API and the AI-generated response is returned to the desktop application.

---

### 2. Voice Input

JARVIS-X supports voice input.

The user can speak a command through the microphone and the system converts the speech into text before sending it to the AI backend.

---

### 3. Voice Output

JARVIS-X can speak its responses using Windows text-to-speech.

This allows the assistant to respond both visually and audibly.

---

### 4. Wake Word

JARVIS-X includes a wake-word system.

The user can say:

> Hey JARVIS

After detecting the wake word, JARVIS-X listens for the user's command.

---

### 5. Memory System

JARVIS-X includes a local memory system.

The assistant can store user-provided information and use saved information in later conversations.

Example:

```text
Remember that my favorite programming language is Python.
