# 📊 Data Analyst Agent

An innovative AI-powered assistant that simplifies data analysis and interpretation. Upload files (CSV, Excel, TXT, PDF, DOCX, or images), get instant summaries, and ask questions—all powered by Together.ai’s Llama-4 model, presented via an interactive Gradio UI.

---

## 🚀 Features

✅ **File Upload & Parsing**
Supports:

* Tabular data: `.csv`, `.xlsx`, `.xls`
* Text files: `.txt`, `.pdf`, `.docx`
* Images: `.png`, `.jpg`, `.jpeg`

✅ **Summarization**
Get concise, insightful summaries for:

* Text documents
* Table data
* Images (via base64)

✅ **Question Answering**
Ask any question related to the uploaded content and receive clear, concise answers.

✅ **Interactive UI**
Gradio-powered web interface for easy file uploads, summaries, and Q\&A.

---

## 🔧 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/data-analyst-agent.git
   cd data-analyst-agent
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly gradio requests pillow PyPDF2 python-docx
   ```

   *(Some packages like PyPDF2 and python-docx are optional but recommended.)*

3. Replace the `TOGETHER_API_KEY` in the code with your actual Together.ai API key.

---

## 📝 Usage

1. Launch the app:

   ```bash
   python app.py
   ```
2. In the Gradio interface:

   * **Upload** a file.
   * **Click** "Summarize Content" to get a summary.
   * **Ask** questions using the textbox, and click "Get Answer" or press Enter.

---

## 💡 Example

Upload a `.csv` file and get a summary:

```
✅ File loaded successfully.
📝 Summary:
- Data contains X rows and Y columns.
- Key insights: ...
```

Ask a question:

```
Question: "What is the trend in sales?"
Answer: "The data shows a consistent upward trend in sales from 2020 to 2024."
```

---

## 🤖 Powered By

* Together.ai’s Llama-4-Maverick-17B model
* Gradio for UI
* Python’s pandas, matplotlib, seaborn, and plotly for data handling & visualization.

---

## 📌 Notes

* Ensure your Together.ai API key is valid.
* For PDF and DOCX files, install `PyPDF2` and `python-docx`.
* The agent currently supports basic file path loading; file-like objects or streaming are not yet implemented.

---

## 🤝 Contributing

Pull requests are welcome! Please ensure your changes align with the project’s innovative spirit and forward-thinking tone.

---

## 📄 License

This project is licensed under the MIT License.
