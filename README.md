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
- `generate_city_image(city)`: Creates a **vibrant pop-art style image** of the requested city.
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
| Voice Input           | `speech_recognition`     |
| Text Input/Output     | `gradio`                 |
| LLM + Tool Use        | `openai` (function calling) |
| Text-to-Speech        | `pyttsx3`                |
| AI Image Generation   | `openai.Image.create` or compatible function |
| Web Interface         | `gradio`                 |

---

## 🛠️ Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/your-username/airlines-chatbot.git
   cd airlines-chatbot
