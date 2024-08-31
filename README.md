# DSA Project

1. Introduction
- Project Overview: This is a desktop application developed in C++ using QT for GUI and SFML (if applicable) for rendering. The application allows users to create and manipulate graph structures interactively, providing a platform for visualizing graph algorithms and structures.

- Purpose and Use Cases: This tool can be used in educational settings for teaching graph theory, in research for visualizing complex networks, or in software development for building and testing graph algorithms.

2. Getting Started

- Installation Instructions:

- - Step 1: Ensure that your system meets the minimum requirements: Windows OS, QT framework installed, and a C++ compiler (like MinGW).
- -  Step 2: Download the project files from the repository or extract the provided ZIP archive.
- - Step 3: Compile the project using the provided .pro file in QT Creator.
- - Step 4: Run the builder.exe file located in the build directory.

## Project Structure Overview: 

The project is organized into several key directories and files:

- /src: Contains the source code files (.cpp and .h).
- /ui: Contains the UI definitions (.ui files).
- /resources: Holds resource files like images and icons (icons.qrc).

## User Interface

Main Window and Navigation: The main window is the central hub for all graph-building activities. It consists of a toolbar, a canvas for graph visualization, and various side panels for interacting with graph elements.

![Screenshot (596)](https://github.com/user-attachments/assets/ff40f0d8-223a-428c-94b4-d7e71d723ff8)

Main Window

![Screenshot (595)](https://github.com/user-attachments/assets/54a05444-dc63-4e1e-aec2-069e8b5359e2)

Main Window 2 

- Custom Widgets and Controls:
- CustomScrollContainer: This widget provides enhanced scrolling capabilities for large graphs.
- CustomWidgets: These are tailored UI elements designed to improve user interaction with the graph.

## Code Overview
Main Components and Their Responsibilities:

Main.cpp: The entry point of the application. It initializes the application and displays the main window.

MainWindow.cpp/h: Manages the main application window, including the layout and interaction with the UI components.

Graph_implement.cpp/h: Handles the core logic of graph creation, manipulation, and algorithm execution.

Graph_View.cpp/h: Responsible for rendering the graph on the canvas.

## For Testing 
Download the graphBuilderV1.3.exe file and run it
