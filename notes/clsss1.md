# Class 1: Project Setup and API Configuration

To build professional Gen AI applications, it is crucial to have a standardized project structure and access to various LLM (Large Language Model) providers. This guide covers the initial setup using Python and VS Code.

---

## 1. Project Directory Structure
A clean structure helps separate the learning phase from the production phase. The recommended setup includes:

* **`notebooks/`**: A folder dedicated to Jupyter Notebooks. Used for the learning phase where you can run code line-by-line.
* **`apps/`**: A folder for end-to-end projects. Once a concept is mastered, the final application is stored here.
* **`requirements.txt`**: A file to list all dependencies. Ensures the project is reproducible without versioning conflicts.
* **`.env`**: A critical file for security. It stores sensitive information like API keys so they are not hardcoded into your scripts.

---

## 2. Environment Setup
To keep the project isolated and avoid library conflicts, we use a **Virtual Environment (Venv)**.

1.  **Create Venv:** Run `python -m venv venv` in your terminal.
2.  **Activate Venv:**
    * **Mac/Linux:** `source venv/bin/activate`
    * **Windows:** `.\venv\Scripts\activate`

---

## 3. API Key Integration
Generative AI development relies on connecting to powerful models via APIs. For this series, we utilize five major providers:

| Provider | Purpose | Key Note |
| :--- | :--- | :--- |
| **OpenAI** | Access to GPT models. | Copy the key immediately; it cannot be viewed again once the window is closed. |
| **Google Gemini** | Access via Google AI Studio. | High-performance models like Gemini 1.5 Pro/Flash. |
| **Anthropic** | Access to Claude models. | Highly regarded for advanced coding and logic generation. |
| **Groq** | Hardware/Inference Platform. | Uses LPUs (Language Processing Units) to run models at ultra-fast speeds. |
| **HuggingFace** | Model Hub. | Requires an Access Token (Read permission) to use open-source models. |

---

## 4. Credits and Billing
While some tiers are free, professional-grade models from OpenAI and Anthropic require a small initial investment to function via API.

* A minimum of **$5** is typically required for both OpenAI and Anthropic to enable API access.
* This total investment of approximately **$10 (roughly ₹900)** is a necessary "learning investment" to build real-world applications throughout this series.

---

### 💡 Analogy for Understanding Setup
Setting up your Gen AI environment is like **organizing a professional kitchen**:

* **The `.env` file** is your locked pantry where you keep expensive, secret ingredients (API keys).
* **The `notebooks/` folder** is your scratchpad for testing individual recipes.
* **The `apps/` folder** is the dining room where the final, complete meals are served to guests.
* **Your Virtual Environment** is the clean workstation that ensures flavors from one dish don't accidentally mix with another.