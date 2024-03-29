# Stellar Stream

Stellar Stream is a simple desktop application built using Python for downloading videos and audio from YouTube.

## Screenshots
![image](https://github.com/AbedIronman/Stellar-Stream/assets/57958425/442c8daa-b642-4f51-bbbe-8070054d658d)  ![image](https://github.com/AbedIronman/Stellar-Stream/assets/57958425/4b87b939-3e2d-434d-a5b1-fe050973189f)
![image](https://github.com/AbedIronman/Stellar-Stream/assets/57958425/854541da-cbde-4f44-95e3-b9aaef55847b) ![image](https://github.com/AbedIronman/Stellar-Stream/assets/57958425/59e5ca9c-7eb8-41d1-9ec9-303e182cc84e)
 ![image](https://github.com/AbedIronman/Stellar-Stream/assets/57958425/a95d81c7-4993-42cb-a9bb-501b98d7d039) ![image](https://github.com/AbedIronman/Stellar-Stream/assets/57958425/0acde619-a137-4986-94f3-fe66e34ea3a7)

## Features

- Download videos or audio from YouTube by pasting the video URL
- Choose a destination folder to save the downloaded files
- Multithreading
- Option to switch between dark and light modes for the user interface
- Visual progress indication during the download process
- Once the video starts downloading, the UI becomes disabled in order to prevent multiple downloads at the same moment

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AbedIronman/stellar-stream.git
    ```

2. Install the required dependencies:

    ```bash
    pip install pytube customtkinter
    ```

3. Run the application:

    ```bash
    python app.py
    ```

## Usage

1. Paste the YouTube video URL into the provided field.
2. Choose a destination folder to save the downloaded files.
3. Click on the "Video" or "Audio" button to start the download process.
4. Monitor the progress using the progress bar and percentage indicator.
5. Once the download is complete, the status will be displayed.

## Dependencies

- pytube
- customtkinter



