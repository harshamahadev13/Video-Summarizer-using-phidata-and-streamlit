# Video Summarizer with Question Answering

This project is a video summarizer that uses Python, PhiData, Streamlit, and the Gemini AI model to generate summaries and answer questions based on video content. It's designed to process videos under 200MB.

## Features

* **Video Summarization:** Generates concise summaries of video content.
* **Question Answering:** Allows users to ask questions about the video and receive relevant answers.
* **User-Friendly Interface:** Built with Streamlit for easy interaction.
* **AI-Powered:** Utilizes the Gemini AI model for natural language processing.

## Technologies Used

* **Python:** The core programming language.
* **PhiData:** (Please specify what PhiData is used for, e.g. data processing, vector database, etc. If it is a private library, please add details on how to install it)
* **Streamlit:** For creating the web application.
* **Gemini AI Model:** For natural language understanding and generation.

## Prerequisites

Before running the application, ensure you have the following installed:

* Python (3.7+)
* pip (Python package installer)

## Installation

1.  **Clone the repository:**

    ```bash
    git clone [your-repository-url]
    cd [your-repository-directory]
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

    (Make sure you create a `requirements.txt` file listing all the Python dependencies: `pip freeze > requirements.txt`)

4.  **Set up Gemini API Key:**
    * Obtain an API key from Google AI Studio.
    * Set the API key as an environment variable or within your script. For example:
        * `export GOOGLE_API_KEY="your_api_key"` (macOS/Linux)
        * `set GOOGLE_API_KEY="your_api_key"` (Windows)

5.  **PhiData Installation:**
    * If PhiData is a custom or private library, add specific installation instructions here.

## Usage

1.  **Run the Streamlit application:**

    ```bash
    streamlit run app.py
    ```

    (Replace `app.py` with the name of your Streamlit script.)

2.  **Open the application in your browser:**

    * Streamlit will provide a local URL (e.g., `http://localhost:8501`). Open this URL in your web browser.

3.  **Upload a video:**
    * Use the file upload widget to select a video file (under 200MB).

4.  **Summarize or Ask Questions:**
    * Use the provided interface to generate a summary or ask questions about the video.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them.
4.  Push your changes to your fork.
5.  Submit a pull request.

## License

[Add your license here, e.g., MIT License]

## Known Issues

* Video files larger than 200MB are not supported.
* [Add any other known issues]

## Contact

[Your contact information, e.g., email address or GitHub profile]

---

**Note:**

* Remember to create a `requirements.txt` file listing all the Python dependencies.
* Replace placeholder values (e.g., `[your-repository-url]`, `[your-repository-directory]`, `[your_api_key]`, `app.py`) with your actual values.
* If PhiData requires specific installation, provide details.
* Add the license you are using.
* If you have a logo, add it to the top of the readme.