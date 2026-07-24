# N.Y.R.O. (Robust Operating Cognitive Knowledge Yield)

A custom-built, multi-agent AI assistant designed to manage content creation, system hardware, and productivity workflows.

## About
N.Y.R.O. is a locally-hosted AI agent that acts as a personal chief of staff for creators. It integrates UI, hardware control, and LLM reasoning into one seamless dashboard.

## Tech Stack
* **Language:** Python
* **GUI Framework:** PyQt6
* **AI Engine:** Google Gemini (via AI Studio API)
* **Audio Processing:** edge-tts, PyAudio
* **Hardware Integration:** pycaw (volume), screen-brightness-control

# Multi-Agent Design N.Y.R.O. 
operates as a suite of specialized agents:
* *UI Agent*: Manages the graphical window, user events, and visual feedback.
 * *Action Agents*: Modular scripts in actions/ that handle hardware-level     tasks (e.g., volume, brightness, AC control). 
 * *Brain Agent*: The LLM orchestrator that processes intent via Function Calling to route tasks to the correct Action Agent.  

## Installation
1. Clone the repository:
   ```bash
   https://github.com/snhyt/N.Y.R.O..git


2. Install dependencies:
**pip install -r requirements.txt**

3. Configure Environment:
Create an API key from Google AI Studio and add it to your local environment configura

4. Run the system:
**python main.py**



🌟 Mind-Blowing Features
*** Proactive System Manager**: N.Y.R.O. doesn't just wait for orders; it understands your workflow and can manage hardware like brightness and volume automatically based on your activity.  
***Persistent "Brain"**: Unlike standard chatbots that forget everything, N.Y.R.O. builds a long-term memory of your projects, technical preferences, and architecture choices, so you never have to repeat yourself. 
***True Agentic Autonomy**: It doesn't just suggest actions—it executes them. Whether it's organizing your files, adjusting your room's smart devices, or syncing across your phone and TV, N.Y.R.O. does the heavy lifting for you.  
***Cross-Device Harmony**: N.Y.R.O. acts as a central hub, connecting your phone, TV, and PC into one unified ecosystem that you control with your voice or simple commands.  
*** Developer-Grade Privacy**: Your credentials and sensitive API keys are handled in an isolated environment, ensuring your data stays secure while you maintain full control over your digital stack.

