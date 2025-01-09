# Pomodoro Timer

A **Pomodoro Timer** built with Python's `tkinter` library, designed to help you stay productive by alternating focused work sessions with short and long breaks. The timer is inspired by the Pomodoro Technique, a time-management method that encourages 25-minute work sessions followed by breaks to maintain focus and avoid burnout.

## Features

- **Work Timer**: 25 minutes of focused work time.
- **Short Breaks**: 5 minutes after each work session.
- **Long Breaks**: 20 minutes after completing four work sessions.
- **Visual Feedback**: Display of a tomato image as a timer background.
- **Check Marks**: Tracks the number of completed work sessions with checkmarks.

## How It Works

1. **Start the Timer**: Click the **Start** button to begin the timer.
2. **Timer Mechanism**: The timer alternates between work sessions, short breaks, and long breaks.
   - After 4 work sessions, a long break is triggered.
3. **Reset the Timer**: Click the **Reset** button to stop the timer and reset progress.
4. **Progress Tracking**: After each work session, a checkmark is displayed to indicate completion.

## Requirements

- Python 3.x
- `tkinter` module (pre-installed with Python)
- An image file named `tomato.png` for the timer background. Place this image in the same directory as the script.

## Installation

1. Clone or download this repository.
2. Place the `tomato.png` image in the same directory as the script.

## Usage

1. Run the script:
   ```bash
   python pomodoro_timer.py
