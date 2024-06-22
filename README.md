# My Cool Browser
My Cool Browser is a simple web browser built using Python and PyQt5. This project demonstrates how to create a basic web browser with navigation functionalities such as back, forward, reload, and home buttons, as well as a URL bar for navigating to different websites.
## Features
- **Back Button**: Navigate to the previous page.
- **Forward Button**: Navigate to the next page.
- **Reload Button**: Reload the current page.
- **Home Button**: Navigate to the home page (`http://youtube.com`).
- **URL Bar**: Enter a URL to navigate to that page.
## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Jaswanthi220/.git    ```
2. Navigate to the project directory:
    ```bash
    cd your-Personlized_browser
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
5. Install the required packages:
    install the necessary packages directly:
    ```bash
    pip install PyQt5 PyQtWebEngine    ```
## Usage
Run the following command to start the browser:
```bash
python main.py
## Code Overview--
    The main components of the browser are:
    MainWindow Class: This class sets up the main window of the browser, including the navigation bar and URL bar.
    Browser Setup: Initializes the QWebEngineView to load web pages.
    Navigation Methods: Methods for handling back, forward, reload, and home navigation.
    URL Handling: Methods for updating the URL bar and navigating to new URLs.


