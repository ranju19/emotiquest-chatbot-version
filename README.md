# emotiquest-chatbot-version
EmotiQuest is a mood-based AI character generator that creates fantasy RPG profiles and portraits using NLP and diffusion models.
Thanks for waiting! Based on the notebook content, here's a **detailed description** of the **EmotiQuest** project:

---

### 🌟 **Project Title**: EmotiQuest – Emotion-Driven Fantasy Chatbot

### 🧠 **What It Is**
EmotiQuest is an interactive, emotion-driven **chatbot-based game** that combines **natural language processing** and **image generation** to create personalized fantasy characters and immersive narratives based on users' emotional input. It aims to promote emotional self-awareness and creative engagement through gamified storytelling.

---

### ⚙️ **How It Works**
1. **User Input:**  
   The player begins by entering a *mood or emotional state* (e.g., "happy", "angry", "mysterious").

2. **Character Generation:**  
   The chatbot:
   - Generates a fantasy-style name based on the user's mood.
   - Builds a complete fantasy character sheet, including:
     - Race (e.g., Elf, Dwarf)
     - Class (e.g., Mage, Warrior)
     - Personality traits
     - Favorite weapon, armor, mount
     - Special traits and alignment
     - Dungeons & Dragons-like stats (e.g., Strength, Dexterity)

3. **Image Creation (via Stable Diffusion):**  
   Using the character name and mood, a **fantasy portrait** is generated to visually represent the character.

4. **Response Output:**  
   The chatbot returns:
   - A **textual bio** of the character
   - A **portrait image** created from the user's mood

5. **User Interface (Gradio):**  
   The app uses **Gradio's ChatInterface**, which provides:
   - Example prompts
   - Text + image interaction
   - Instant feedback in a simple web UI

---

### ✨ **Key Features**
- **Mood-Based Interaction:** Characters and their story traits change depending on user emotion.
- **NLP + Diffusion Model Combo:** Seamlessly integrates text and image generation.
- **Fully Generated Fantasy Characters:** Includes detailed bios, equipment, and magical flair.
- **Creative Engagement:** Encourages storytelling and roleplaying through emotional cues.
- **No Backend Dependency:** Runs via Gradio with Hugging Face Transformers and Diffusers.
- **Gamified Self-Reflection:** Offers a playful way for users to explore emotions through fantasy.

---

### 🧰 **Tech Stack**
- **Python**
- **Gradio** – UI for the chatbot
- **Transformers (Hugging Face)** – GPT-2 for text generation
- **Diffusers (Stable Diffusion)** – Image generation
- **Torch** – For model handling
- **PIL** – For image manipulation
- **Regex, UUID, OS** – Supporting logic

---

### 🎯 **Use Cases**
- Emotional wellness tools with a fantasy twist
- Creative writing inspiration
- Personalized gaming avatars
- Icebreakers in social settings or therapy
- Mood-based digital journaling

---
### **Future Ideas**
- Add quest-based decision trees
- Emotional journey tracking over time
- Expand to multiplayer co-op or storytelling mode
- Store past characters for reflection
  
---
