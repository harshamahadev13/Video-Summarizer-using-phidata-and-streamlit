# Video Summarizer with Question Answering

This project is a video summarizer that uses Python, PhiData, Streamlit, and the Gemini AI model to generate summaries and answer questions based on video content. It's designed to process videos under 200MB Videos.

## Features

* **Video Summarization:** Generates concise summaries of video content.
* **Question Answering:** Allows users to ask questions about the video and receive relevant answers.
* **User-Friendly Interface:** Built with Streamlit for easy interaction.
* **AI-Powered:** Utilizes the Gemini AI model for natural language processing.

## Technologies Used

* **Python:** The core programming language.
* **PhiData:** Framework for building multi-modal agents and workflows
* **Streamlit:** For creating the web application.
* **Gemini AI Model:** For computer vision, natural language understanding and generation.

## Prerequisites

* Python (3.12+)
* pip (Python package installer)

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/harshamahadev13/video-summarizer-using-phidata-and-streamlit
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



## Usage

1.  **Run the Streamlit application:**

    ```bash
    streamlit run video_summarizer.py
    ```

2.  **Open the application in your browser:**

    * Streamlit will provide a local URL (e.g., `http://localhost:8501`). Open this URL in your web browser.

3.  **Upload a video:**
    * Use the file upload widget to select a video file (under 200MB).

4.  **Summarize or Ask Questions:**
    * Use the provided interface to generate a summary or ask questions about the video.



## Known Issues

* Video files larger than 200MB are not supported.
* Scaling up
