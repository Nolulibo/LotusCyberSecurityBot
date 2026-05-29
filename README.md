Lotus Cybersecurity Awareness Bot

Overview

Lotus Cybersecurity Awareness Bot is a WPF-based cybersecurity education chatbot developed in C# using .NET 8.0 and Visual Studio 2026.
The purpose of the chatbot is to educate users about cybersecurity threats and online safety through interactive conversation, emotional awareness, personalised responses, keyword recognition, memory recall, and voice interaction.
This project was developed as Part 2 of a Cybersecurity Awareness Chatbot assignment.


Features

GUI Interface

-Modern WPF graphical user interface

-Dark cybersecurity-themed design

-Scrollable chat display

-Chat bubbles with timestamps

-Enter key support for sending messages


Voice Greeting

-WAV audio greeting on startup

-Text-to-speech chatbot responses using System.Speech


ASCII Art

-Cybersecurity-themed ASCII banner displayed in the interface


Keyword Recognition

The chatbot recognises multiple cybersecurity topics including:

-Passwords

-Phishing

-Malware

-Privacy

-Scams

-Ransomware

-Firewalls


Random Responses

-Multiple responses per cybersecurity topic

-Randomised reply selection for more natural conversation


Sentiment Detection

The chatbot detects emotional tone including:

-Worried

-Curious

-Frustrated

-Happy

The bot responds empathetically before providing cybersecurity guidance.


Memory and Recall

The chatbot remembers:

-User name

-Favourite cybersecurity topic


Responses are personalised using stored memory.

Conversation Flow

-Follow-up support

-“Tell me more” functionality

-Topic continuation without resetting the conversation


Persistent Chat History

Conversation history is automatically saved to a text file.


Code Architecture

The project follows object-oriented programming principles with separated responsibilities across multiple classes.


Technologies Used

-C#

-.NET 8.0

-WPF

-Visual Studio 2022

-GitHub Actions

-System.Speech


Project Structure

File & Responsibility

MainWindow.xaml	--> GUI layout

MainWindow.xaml.cs --> GUI event handling

Chatbot.cs -->	Core chatbot routing logic

KeywordResponder.cs -->	Cybersecurity keyword responses

SentimentDetector.cs -->	Emotion detection

MemoryStore.cs -->	User memory and recall

ConversationManager.cs -->	Follow-up handling

AudioPlayer.cs -->	Audio greeting and speech

build.yml -->	GitHub Actions CI workflow


Author

Developed by:

Nolulibo Songqushwa



