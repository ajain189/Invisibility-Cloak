# Invisibility-Cloak
This project uses a webcam and Python to create an invisibility effect. By detecting a blue cloth, it makes anything covered by it disappear on screen, just like an invisibility cloak.

# Invisible Cloak Project

This project uses Python and OpenCV to create a fun invisibility effect with a webcam. By detecting a blue cloth, it makes anything covered by it disappear on screen, similar to an invisibility cloak from the movies!

## How It Works

1. **Background Capture**: The program captures the background when no one is in view.
2. **Color Detection**: It detects a specific color range (blue by default) in the webcam feed.
3. **Cloak Effect**: The detected blue areas are replaced with the captured background, making them appear invisible.
4. **Real-Time Display**: The result is displayed in real-time.

## Requirements

- Python 3.x
- OpenCV
- NumPy

## Usage

1. Run the script:
   ```bash
   python main.py
   ```
2. Follow the instructions to capture an empty background
3. Use something blue to see the invisibiltiy effect
4. Press 'q' to quit the application.

## Notes

- Ensure you are in a well-lit area
- You can change the color range in the script to use a different color for the cloak
