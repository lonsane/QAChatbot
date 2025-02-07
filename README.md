# QAChatbot

## Overview

QAChatbot is an intelligent chatbot that allows users to upload a file and ask questions based on its content. The chatbot quickly processes the uploaded document and provides accurate responses using advanced AI models. The project utilizes technologies like Gemini, Python, Streamlit, Anaconda, and LLaMA.

## Features

- **File Upload**: Users can upload documents (PDF, TXT, etc.).
- **Intelligent Question Answering**: Users can ask questions about the uploaded file, and the chatbot will provide precise responses.
- **Quick Processing**: Uses state-of-the-art AI models for fast and accurate answers.
- **User-Friendly Interface**: Built with Streamlit for an interactive and responsive UI.

## Technologies Used

- **Gemini**: For AI-powered question-answering capabilities.
- **Python**: Backend logic and AI processing.
- **Streamlit**: For building the web-based user interface.
- **Anaconda**: Environment and dependency management.
- **LLaMA**: Leveraging LLaMA for efficient natural language processing.

## Installation and Setup

### Prerequisites

Ensure you have the following installed on your system:

- Python (>=3.8)
- Anaconda
- Git

### Steps to Run

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd QAChatbot
   ```
2. **Create a Virtual Environment** (Optional but recommended)
   ```bash
   conda create --name qachatbot-env python=3.8
   conda activate qachatbot-env
   ```
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Download Necessary Models**
   ```bash
   python download_models.py
   ```
5. **Set Up Environment Variables**
   ```bash
   export API_KEY=your_api_key_here
   ```
6. **Run the Application**
   ```bash
   streamlit run app.py
   ```

## Usage

1. Upload a file (PDF, TXT, etc.).
2. Type your question in the chat input.
3. Receive an AI-generated response based on the content of the file.

## Contributing

If you would like to contribute, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any queries or suggestions, feel free to reach out via GitHub issues or email.

