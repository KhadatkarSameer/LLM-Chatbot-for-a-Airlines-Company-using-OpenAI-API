# 🛫 Airlines Chatbot with Audio, Text & Visual Output

An intelligent, multimodal airline assistant that responds to user queries via **voice, text, and visual content**. This chatbot uses **OpenAI's GPT model with tool/function calling**, supports **audio and text inputs**, speaks responses back to the user, and even generates **AI pop-art style images** of cities and tourist attractions.

Built with Python, Gradio, OpenAI APIs, and speech/text processing tools — all in a single seamless interface.

---

## 🚀 Features

### ✅ Dual Input Modes
- 🎙️ **Audio Input**: Speak to the chatbot using your microphone.
- ⌨️ **Text Input**: Type your query into the chat window.

### 🤖 GPT-Powered Chatbot with Tool Calling
- Uses **OpenAI's function calling** capabilities.
- Responds intelligently to airline-related queries.
- Routes specific tasks (like price lookups or image generation) to tools.

### 🧰 Custom Tools Included
- `get_ticket_price(city)`: Simulates ticket price retrieval.
- `artistic(city)`: Creates a **vibrant pop-art style image** of the requested city.
- Easily extendable with more tools.

### 🗣️ Text-to-Speech Output
- Responds not just in text but also **reads replies aloud**.
- Powered by `pyttsx3`, an offline text-to-speech engine.

### 🌍 Pop-Art Style City Images
- When a user asks about a city, the chatbot generates a **colorful AI image** featuring:
  - Tourist attractions
  - Cultural highlights
  - Local vibes
- Style: Bright, abstract **pop-art aesthetic**.

### 🌐 Gradio Web Interface
- Clean and responsive interface using **Gradio**.
- Displays:
  - User inputs
  - Text responses
  - Audio playback
  - Generated city images

---

## 🧩 Tech Stack

| Feature               | Tool/Library             |
|-----------------------|--------------------------|
| Voice Input           | `openai` (whisper-1 model) |
| Text Input/Output     | `gradio`                 |
| LLM + Tool Use        | `openai` (gpt-4o-mini, with function calling) |
| Text-to-Speech        | `openai` (tts-1 model)   |
| AI Image Generation   | `openai` (dall-e-3 model) |
| Web Interface         | `gradio`                 |

---

## 🛠️ Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/KhadatkarSameer/LLM-Chatbot-for-a-Airlines-Company-using-OpenAI-API.git
   cd LLM-Chatbot-for-a-Airlines-Company-using-OpenAI-API

---

## 🔮 Possible Enhancements

This project is designed with modularity and extensibility in mind. Below are several **potential enhancements** that can significantly expand its capabilities:

- **Flight Booking Integration**  
  Extend the chatbot to support booking tickets by collecting travel details (destination, date, number of passengers) and interfacing with external flight APIs.

- **Complaint Handling**  
  Allow users to raise service complaints through a conversational form, with complaint tracking and ticket generation.

- **Live Flight Schedules and Status**  
  Integrate real-time flight schedule lookups and status updates from public or private airline APIs.

- **Baggage & Visa Information**  
  Provide destination-specific travel requirements such as visa policies, baggage limits, customs regulations, etc.

- **Multilingual Support**  
  Enhance accessibility by translating chatbot responses into the user’s preferred language or auto-detecting language based on input.

- **Itinerary Sharing via Email**  
  Enable the chatbot to email users a summary of their planned itinerary, booking confirmations, or generated city visuals.

> These enhancements can be powered by extending **OpenAI’s function-calling interface**, allowing seamless communication between the LLM and external tools or APIs.
