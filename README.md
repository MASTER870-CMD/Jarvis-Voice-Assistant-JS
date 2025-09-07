# Jarvis Project Voice Assistant

## Short Description

Jarvis is a simple voice assistant built using HTML, CSS, and JavaScript. It utilizes the Web Speech API to recognize voice commands and provide spoken responses.  This project demonstrates basic voice interaction and can be extended with more functionalities and integrations.

## Features

*   **Voice Recognition:** Uses the browser's SpeechRecognition API to convert speech to text.
*   **Text-to-Speech:** Uses the SpeechSynthesis API to convert text to speech, providing spoken responses.
*   **Initial Greeting:** Greets the user with a personalized message based on the time of day.
*   **Simple User Interface:** A clean and intuitive interface for initiating voice commands.
*   **Microphone Activation:** A button to activate voice recognition.

## Requirements

*   Modern web browser with support for Web Speech API (Chrome, Edge, etc.).
*   A microphone for voice input.

## Installation

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    cd JARVIS-voice-assistant-main
    ```

2.  No server-side installation is required.  The project can be run directly from the file system.

## Usage

1.  Open `index.html` in your web browser.
2.  Click the microphone button to activate voice recognition.
3.  Speak your command. The recognized text will be displayed on the screen.  Note that the project currently transcribes speech to text, but doesn't implement any command processing beyond that.

## File Structure

```
JARVIS-voice-assistant-main/
├── index.html    # Main HTML file for the user interface
├── style.css     # CSS file for styling the application
├── app.js        # JavaScript file for handling voice recognition and text-to-speech
├── avatar.png    # Favicon image
├── giphy.gif     # Animated GIF used in the interface
└── README.md     # This file
```

## Testing

This project primarily relies on manual testing through a web browser:

1.  Ensure that the browser has microphone access enabled.
2.  Open `index.html` and click the microphone button.
3.  Speak clearly and verify that the transcribed text is accurate.
4.  Check that the initial greeting is played correctly upon page load.

Automated testing is not currently implemented.

## Configuration

There is no configuration file. The core functionality resides within `app.js` and `style.css`. The speech rate, pitch and volume are configured directly in the `app.js` file.
## Contributing

Contributions are welcome! Here's how you can contribute:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Implement your changes.
4.  Submit a pull request with a clear description of your changes.

## License

This project is open source and available under the [MIT License](LICENSE).

## Improvements

Here are some potential improvements for the project:

*   **Command Processing:** Implement command parsing and execution based on recognized text (e.g., opening websites, setting reminders).
*   **More complex interaction**: Extend the project with more complex interaction that uses APIs to search on the internet, or to control hardware devices.
*   **Error Handling:** Add error handling for speech recognition and text-to-speech functionalities.
*   **UI Enhancements:** Improve the user interface with better styling and animations.
*   **Automated Testing:** Implement automated tests to ensure the reliability of the voice assistant.
*   **Cross-Browser Compatibility:** Test and ensure compatibility across different web browsers.
*   **User Configuration:** Allow users to customize the voice assistant's behavior (e.g., voice, greeting).
