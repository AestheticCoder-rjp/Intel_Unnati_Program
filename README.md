# PDF Genie

PDF Genie is a Streamlit application that allows users to interact with PDF documents through a conversational interface. Users can upload a PDF document, and the application processes the document to enable text-based queries.

## Features

- Upload and process PDF documents.
- Ask questions and get responses based on the PDF content.
- View chat history and processing times.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Streamlit
- PyPDF2
- LangChain
- FAISS
- OllamaEmbeddings
- dotenv

### Installation

1. Clone the repository:
    ```bash
    https://github.com/AestheticCoder-rjp/Intel_Unnati_Program
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root directory and add your GROQ API key:
    ```env
    GROQ_API_KEY=your_groq_api_key
    ```

### Running the Application

To start the Streamlit application, run:
```bash
streamlit run app.py
```

## Usage

1. **Upload a PDF**: Use the sidebar to upload your PDF document and click "Process".
2. **Ask Questions**: Enter your questions in the input box and receive responses based on the PDF content.
3. **View Processing Time**: The application displays the processing time for each query.
