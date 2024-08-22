
# Desktop Virtual Assistant

A desktop virtual assistant that uses Google's Gemini Pro model for natural language understanding and vision-based tasks, enabling easy interaction through voice commands, application launching, screen management, and more, all within an intuitive GUI interface.

## Overview

The Desktop Virtual Assistant is an AI-powered assistant designed to help you perform various tasks on your computer effortlessly. It leverages the power of Google's Gemini Pro model for natural language understanding and vision-based tasks, enabling it to execute commands and respond to queries intelligently.

## Features

- **Open Applications**: Launch commonly used applications like Notepad, Word, Excel, PowerPoint, Calculator, and Command Prompt.
- **Web Navigation**: Open websites directly by speaking the URL.
- **Screen Management**: Capture screenshots and record your screen.
- **Voice Interaction**: Interact with the assistant using natural language voice commands.
- **Camera Vision**: Capture and describe images from your screen or webcam.
- **GUI Interface**: A simple and interactive graphical user interface for easier interaction.

## Requirements

To install the necessary dependencies, you can use the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Setup

1. Clone the repository:

```bash
git clone https://github.com/sherwinvishesh/Desktop-Virtual-Assistant.git
```

2. Set up environment variables in a `.env` file:

```env
VA_NAME=Virtual Assistant
GOOGLE_GEMINI_API_KEY=your_google_gemini_api_key
MEDIA_DIR=media
SCREENSHOT_FILE=screenshot.png
VIDEO_FILE=screen_record.avi
```

3. Ensure you have the required media directory structure:

```bash
mkdir media
```

4. Run the assistant:

```bash
python main.py
```

## Usage

- **Awaken the Assistant**: Say "Awaken" to activate the assistant.
- **Execute Commands**: Use natural language to command the assistant to open applications, take screenshots, start/stop screen recording, etc.
- **Interact with Websites**: Ask the assistant to open websites by stating the URL.
- **Use Camera Vision**: Capture and get a description of what the assistant sees through the camera.

## Project Structure

- **act/**: Contains actions the assistant can perform, such as opening applications and taking screenshots.
- **aim/**: Handles AI-related tasks like conversing and vision processing.
- **audio/**: Manages speech synthesis and recognition.
- **ui/**: Contains the graphical user interface code.
- **main.py**: The main script that runs the virtual assistant.
- **.env**: Environment variables for configuring the assistant.
- **requirements.txt**: Lists all the Python dependencies required for the project.

## Contributing

We welcome contributions from the community, especially those that enhance its capabilities. Feel free to fork the repository, make your improvements, and submit a pull request.


## License

This project is licensed under the Apache-2.0 license - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to everyone who visits and uses this page. Your interest and feedback are what keep us motivated.
- Special thanks to all the contributors who help maintain and improve this project. Your dedication and hard work are greatly appreciated.
- Special acknowledgment to architecturebytes for there project [ai-virtual-assistant](https://github.com/architecturebytes/ai-virtual-assistant). It served as a significant inspiration for this project, demonstrating the powerful impact of Gemini as a vertual assistant.


## Contact

Feel free to reach out and connect with me on [LinkedIn](https://www.linkedin.com/in/sherwinvishesh) or [Instagram](https://www.instagram.com/sherwinvishesh/).



---


Made with ❤️ by Sherwin
