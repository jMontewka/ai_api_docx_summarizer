## 📄 AI Job Listing Summarizer

A simple Python script to summarize job listings from a `.docx` file using a local Ollama server with the summary then saved to a new `.docx` file. Tested with `llama3.2:1b` model.

---

### 🚀 Setup & How It Works

1.  **Setup:**
    * **Install Ollama:** Download and install Ollama from [ollama.com](https://ollama.com/).
    * **Get the Model:** Run `ollama pull llama3.2:1b` in your terminal to download the AI model.
    * **Install Libraries:** Use pip to install the necessary Python libraries: `pip install python-docx ollama`.

2.  **How It Works:**
    * **Read:** The script reads all text from `ofertyPracy.docx`.
    * **Summarize:** It sends the text to your local Ollama API via a Python library.
    * **Save:** The AI's summary is saved into a new file, `summary.docx`.

---

### 📝 Professional Annotation

> ### 📝 Professional Annotation
> 
> The code for this project was entirely generated using a **single prompt** for **Gemini 2.5 Flash** large language model. This demonstrates the efficiency of using advanced LLMs to quickly create functional scripts from precise plain-language requests.
> 
> **Prompt Used:**
> ```
> We will be making an API learning project.
> The project :
> I have multiple jobs listings in .docx file called "ofertyPracy.docx". I want them all sumarised by a local ollama llm with llama3.2:1b model (don't worry about  prompt limit right now) . Then I want the result saved in .docx file called "summary.docx".
> I want this done in Python with use of local ollama API .
> Make it easy and straightforward .
> ```