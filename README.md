# AI Assistant

Welcome to the AI Assistant project! This intelligent assistant can perform a variety of tasks to make your life easier. From opening applications to checking system status, this assistant has got you covered.

## Features

- **Web Browsing**: Open your favorite web browsers and search the web effortlessly.
- **Application Management**: Launch applications like Safari, Chrome, TextEdit, and more with simple voice commands.
- **System Monitoring**: Check CPU, memory, and disk usage with ease.
- **System Preferences**: Quickly access system settings like Wi-Fi, Bluetooth, Display, and more.
- **Meeting Management**: Start, join, and manage online meetings seamlessly.
- **System Operations**: Perform operations like shutdown, restart, and minimize windows.
- **OpenAI GPT Integration**: Generate intelligent responses using OpenAI's GPT models.

## Requirements

- Python 3.6+
- `speech_recognition` library
- `pyttsx3` library
- `openai` library
- `psutil` library

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/ai-assistant.git
    cd ai-assistant
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv my_env
    source my_env/bin/activate  # On Windows use `my_env\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set your OpenAI API key in `main.py`:
    ```python
    openai.api_key = "your-api-key"  # Replace with your OpenAI API key
    ```

## Usage

Run the assistant:
```sh
python [main.py](http://_vscodecontentref_/0)
