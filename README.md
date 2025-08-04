# TestGenie

## Setup

1. Create and activate a virtual environment:
   ```
   python -m venv venv
   venv\Scripts\activate
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set your Azure OpenAI credentials in `.env`.

4. Run the app:
   ```
   python app.py
   ```

## Features
- Upload DOC, XLS/XLSX, TXT, CSV, JSON files
- Select testing type, level, and industry
- Preview upload status
- Generate AI test cases (Azure OpenAI integration)

