LuminAI: Your Intelligent Research Companion

LuminAI is a powerful, AI-driven research assistant designed to help users interact with their documents seamlessly. Whether it's PDFs, DOCX files, PowerPoint presentations, or LaTeX files, LuminAI processes and retrieves information efficiently to provide accurate answers to your queries.

Features

Document Upload and Processing

Upload multiple document types: PDF, DOCX, PPTX, and LaTeX.

Extracts and processes text from uploaded files.

Intelligent Conversational AI

Engage in meaningful conversations about your research documents.

Receive accurate, contextually relevant answers to your queries.

Provides sources for the responses generated.

Local AI Model Integration

Utilizes free, open-source models (e.g., LLaMA, GPT-2) for text generation.

No dependency on paid APIs like OpenAI or HuggingFace Hub.

Streamlit-Powered UI

A clean and user-friendly interface for interaction.

Typewriter effect for dynamic response display.

Getting Started

Follow these steps to set up and run LuminAI on your local machine.

Prerequisites

Ensure you have the following installed:

Python 3.8+

pip (Python package installer)

Installation

Clone the repository:

git clone https://github.com/your-username/luminai.git
cd luminai

Install the required Python packages:

pip install -r requirements.txt

Set up environment variables:

Create a .env file in the root directory.

Add the following variables:

MODEL_NAME=mistralai/Mistral-7B-Instruct-v0.1
EMBEDDING_MODEL=hkunlp/instructor-xl

Running the Application

Start the Streamlit application:

streamlit run app.py

Open your web browser and navigate to:

http://localhost:8501

Usage

Upload Documents:

Drag and drop your research documents into the "Document Library" section.

Supported formats: PDF, DOCX, PPTX, LaTeX.

Ask Questions:

Enter your query in the text input field.

LuminAI will process your documents and generate answers based on the content.

Download Chat History:

Export your chat history as a text file for future reference.

File Structure

LuminAI/
├── app.py                # Main Streamlit application
├── document_processor.py # Document processing logic
├── requirements.txt      # Python dependencies
├── .env                  # Environment variables
├── README.md             # Project documentation
├── htmlTemplates2.py     # UI templates
└── ...                   # Other supporting files

Contributing

Contributions are welcome! If you have ideas or improvements for LuminAI, feel free to:

Fork the repository.

Create a new branch.

Submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments

Inspired by the need for efficient research tools.

Built using Streamlit and LangChain.
