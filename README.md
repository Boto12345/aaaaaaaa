# RAG Application (Gemini)

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/isurulkh/rag-application-gemini/main/app.py)

## Description

The RAG Application (Gemini) is a Streamlit web application designed to question answering system that retrieves information from uploaded PDFs using Google Generative AI and LangChain. Ask questions about the document's content and get detailed, context-aware answers.

## Technologies Used

- **Streamlit:** The web framework used for building the interactive user interface.
- **Google Generative AI (Gemini):** A powerful language model used for natural language understanding and question answering. You can learn more about Gemini [here](https://deepmind.google/technologies/gemini/#introduction).
- **LangChain:** A library for building language-based applications, used for creating custom prompts and managing text data.
- **ChromaDB:** A vector store used for efficient storage and retrieval of embeddings generated by the Google Generative AI model.

## Demo

You can access the live demo [here](https://geminirag.streamlit.app/).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/isurulkh/rag-application-gemini.git
    ```

2. Navigate to the project directory:

    ```bash
    cd rag-application-gemini
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

5. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

2. Open your browser and go to `http://localhost:8501`.

3. [Provide any additional usage instructions].

## Configuration

### Environment Variables

- `GOOGLE_API_KEY`: Obtain a Google Generative AI API key from the [Google Cloud Console](https://console.cloud.google.com/) and set it as an environment variable.

    ```bash
    export GOOGLE_API_KEY=your_google_api_key
    ```

## Contributing

If you would like to contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new branch:

    ```bash
    git checkout -b feature/my-feature
    ```

3. Commit your changes:

    ```bash
    git commit -m "Add my feature"
    ```

4. Push to the branch:

    ```bash
    git push origin feature/my-feature
    ```

5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
