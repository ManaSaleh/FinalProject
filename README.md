![Logo](PythonScripts/logo.png)
# Wathiq Interview/Presentation Analysis System

This project was created as the capstone project for [T5/Data Since and ML] by Tuwaiq/SDAIA

## Overview

This project aims to analyze various aspects of human behavior from a video, including body language, stutter detction, eye contact, emotion detection, and hand movement analysis, as well as transcribe and summarize the spoken content.

## Features

- **Body Language Recognition**: Detects and summarizes body language cues.
- **Audio Processing**: Generates a stutter report, transcribes speech, and provides text summaries.
- **Eye Contact Detection**: Analyzes the frequency and duration of eye contact.
- **Emotion Detection**: Identifies and quantifies emotions from the video.
- **Hand Movement Detection**: Detects and assesses hand movements.
- **Body Tracking**: Tracks body movement within the video.

## Installation

To get started with the project, follow these steps:

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/ManaSaleh/FinalProject.git
    ```
2. Install the required dependencies by running:
    ```sh
    pip install -r requirements.txt
    ```
3. Ensure you have ffmpeg installed on your system. You can download it from [here](https://ffmpeg.org/download.html).

   
## Usage

To use the project:

1. Navigate to the project directory:
    ```sh
    cd FinalProject/
    ```
2. Navigate to
    ```sh
   cd /PythonScripts
    ```
3. Run the following command to access the streamlit app
    ```sh
    streamlit run .\streamlit_app_test.py
    ```
3.2 Alternativley you can access the indvidual modules in their script form in the folder /PythonScripts or in their notebook form in their respective folders
## File Structure

```
FinalProject/
│
├── AudioProcessing/               # Audio Processing data
|   ├── A.ipynb                    # Audio Processing Notebook
|   └── extracted_audio.wav        # Extracted audio from notebook run
├── BodyLanguage/                  # Body Language data
|   ├── BL.ipynb                   # Body Language Notebook
│   ├── coords.csv                 # Coordinates CSV file
|   └── body_language.pkl          # Model Weights for Body Language model
├── EyeContact/                    # Eye Contact data
|   ├── Eyecontact.ipynb           # Eye Contact Notebook
│   ├── Eye.csv                    # Eye CSV file
|   └── Eye.pkl                    # Model Weights for Eye contact model
├── FaceEmotion/                   # Face Emotion data
|   ├── FaceEmotion.ipynb          # Face Emotion Notebook
|   └── bestFace.pt                # Model Weights for Face Emotion Model
├── HandMovement/                  # Hand Movement data
|   ├── hands.ipynb                # Hand Movement Notebook
|   └── hand_movement_data.csv     # Saved results from notebook run
├── PythonScripts/                 # Python scripts
│   ├── AudioProcessor.py          # Script for audio processing
│   ├── BodyLanguageRecognizer.py  # Script for body language recognition
│   ├── EmotionDetector.py         # Script for emotion detection
│   ├── EyeContact.py              # Script for eye contact analysis
│   ├── HandMovementDetector.py    # Script for hand movement detection
│   ├── ObjectTracker.py           # Script for object tracking
│   ├── main.py                    # Main script to run the analysis in CLI
|   └── streamlit_app.py      # Streamlit App script
├── requirements.txt               # Python dependencies
└── README.md                      # Project README file
```

## Contributing

We welcome contributions from the community! If you'd like to contribute to the project, please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes with descriptive messages.
- Open a pull request to the `master` branch.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback regarding the project, feel free to contact us at [breued1@gmailcom] [adamixa@gmail.com].
