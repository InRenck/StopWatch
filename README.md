## Simple Stopwatch App

# Overview
This is a simple stopwatch app built with HTML, CSS, and JavaScript. It allows users to start, pause, and reset the stopwatch. The interface is designed with a clean and user-friendly layout.

# Table of Contents
  - Project Structure
  - Usage
  - CSS Styles
  - JavaScript Logic
  - License

# Project Structure
The project consists of the following files:
  - HTML file (index.html):
    Defines the structure of the stopwatch app, including the container, timer display, and control buttons.
  - JavaScript file (script.js):
    Implements the logic for starting, pausing, and resetting the stopwatch. It also handles the display of the elapsed time.
  - CSS file (style.css):
    Provides styles for the stopwatch app, including the container, timer display, and control buttons.

# Usage
To use the stopwatch app, follow these steps:
  1. Clone the repository:
     git clone <repository-url>
  2. Open the index.html file in your preferred web browser.
  3. Click the "Start" button to begin the stopwatch.
  4. Click the "Pause" button to temporarily stop the stopwatch.
  5. Click the "Reset" button to reset the stopwatch to zero.

# CSS Styles
The CSS styles are designed to create an aesthetically pleasing and user-friendly interface for the stopwatch app. Key styles include:

  - Container:
    The container has a white background, rounded corners, and a shadow, creating a card-like appearance.
  - Timer Display:
    The timer display has a white background, uses the 'Roboto Mono' font for a monospace appearance, and is centered within the container.
  - Control Buttons:
    The control buttons have a colored background, white text, and a border-radius. The "Pause" button has a different color for visual distinction.
  - Button Hover Effect:
    The buttons have a subtle box-shadow on hover to provide visual feedback.

# JavaScript Logic
The JavaScript logic enables the functionality of the stopwatch app. Key features include:
 - Start Timer:
   The "Start" button initiates the timer, updating the display every 10 milliseconds.
 - Pause Timer:
   The "Pause" button stops the timer by clearing the interval.
 - Reset Timer:
   The "Reset" button stops the timer and resets the elapsed time to zero.
 - Display Timer:
   The displayTimer function calculates and displays the elapsed time in hours, minutes, seconds, and milliseconds.

# License
This project is licensed under the MIT License.
