# 📄 AI Job Listing Summarizer

A Python script to summarize job listings from a `.docx` file using either a local Ollama server or the Google Gemini API. The summary is saved to a new `.docx` file.

Sample (AI generated) and Output (example with use of gemini-1.5-flash model) files provided.

---

## 🚀 How It Works

1. **Read:** The script reads all text from `ofertyPracy.docx`.
2. **Summarize:** It sends the text to your chosen AI model (Ollama or Gemini).
3. **Save:** The summary is saved to `summary.docx`.

---

## 🛠️ Setup

### Local Ollama API

1. **Install Ollama:**  
   Download and install Ollama from [ollama.com](https://ollama.com/).

2. **Get the Model:**  
   Pull the model using:

   ```bash
   ollama pull llama3.2:1b
   ```

3. **Install Python Libraries:**  

   ```bash
   pip install python-docx ollama
   ```

4. **Run the Script:**  

   ```bash
   python summarizer_local.py
   ```

---

### Cloud Gemini API

1. **Obtain API Key:**  
   Get your Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

2. **Create `.env` File:**  
   In your project root, create a `.env` file and add:

   ```env
   GEMINI_API_KEY=YOUR_API_KEY_HERE
   ```

3. **Install Python Libraries:**  

   ```bash
   pip install python-docx google-generativeai python-dotenv
   ```

4. **Run the Script:**  

   ```bash
   python summarizer_cloud.py
   ```

---

## ⚠️ Security Note

- **Never share your `.env` file or API keys publicly.**
- Add `.env` to your `.gitignore` file.

---

## ✨ License

MIT License
