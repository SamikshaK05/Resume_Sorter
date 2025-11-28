# Resume_Sorter
📄 Filter Resumes – AI-Powered Resume Screening App

An intelligent Resume Filtering Web App built with Streamlit and powered by Google Gemini AI.
Upload multiple resumes (PDF, DOCX, DOC, TXT), filter them using natural language, and export the results to Excel — all in a clean UI with light-mode enforced.

🚀 Features
✅ AI-Powered Resume Filtering

Use natural language queries like:

“React developers with 3+ years experience”

“Python + Django + SQL fresher resumes”

The app intelligently screens resumes using Google Gemini.

📂 Upload Multiple Resume Files

Supports the following formats:

PDF

DOC / DOCX

TXT

Drag & drop or click to upload.

📝 Built-in NLP Filtering

Smart filtering using Gemini:

Skills extraction

Experience level matching

Education detection

Custom natural language queries

Ranked results

💡 Additional Features

Load sample resumes (optional)

Export filtered results to Excel

Clean UI with forced light mode

Stylish modern design using custom CSS

Session-based processing (no re-upload required)

🏗️ Project Structure
📦 project-folder
│
├── app.py
├── requirements.txt
│
├── components/
│   ├── initialization.py
│   ├── processor.py
│   ├── results.py
│   ├── filter.py
│
├── utils/
│   ├── file_handler.py
│   ├── export.py
│
└── data/
    └── samples/   (optional sample resumes)

🛠️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Add Your Gemini API Key

Create a .streamlit/secrets.toml file:

[api_keys]
GEMINI_API_KEY = "your_api_key_here"

4️⃣ Run the Streamlit App
streamlit run app.py

💻 Usage Instructions
1. Upload Resumes

Upload multiple resumes in supported formats.

2. Apply Natural Language Filters

Example queries:

"Java developer 2+ years, Pune"

"MBA, management, good communication"

"Python fresher with internship experience"

3. View Results

Parsed data

Skills extracted

Experience detected

Relevance score

4. Export to Excel

Click “Export to Excel” to download the filtered results.

🧠 Tech Stack
Technology	Purpose
Python	Backend logic
Streamlit	Web UI
Google Gemini Pro	NLP + AI filtering
PyMuPDF, pdfplumber	PDF parsing
pytesseract	OCR for text extraction
python-docx	DOCX parsing
pandas	Data processing
openpyxl / xlsxwriter	Excel export
📦 Dependencies

All dependencies are listed in the requirements.txt, including:

streamlit

pandas

PyPDF2

pytesseract

pymupdf

pdfplumber

google-generativeai

openpyxl

plotly

scikit-learn

(Full list already included in your uploaded file.)

🛡️ Error Handling

The application handles:

Missing API key

Empty inputs

No matching resumes

Corrupt resume files

Unsupported file types

🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first.

📜 License

This project is licensed under the MIT License.
