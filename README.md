# Life Weeks App Walkthrough

The **Life Weeks App** (`Vista`) has been successfully created. This minimalist application visualizes your life in weeks, inspired by Dieter Rams' design philosophy.

## How to Run

### Option 1: Using the Running Server (Recommended)
A Python HTTP server has been started on port 8000.
1. Open your browser.
2. Navigate to: [http://localhost:8000](http://localhost:8000)

### Option 2: Run the Server Manually
If the server stops or you wish to run it later:
1. Open a terminal in the project directory (the folder that contains `index.html`)
2. Run: `python -m http.server 8000`
3. Open [http://localhost:8000](http://localhost:8000)

### Option 3: Open Directly
You can also open the `index.html` file directly in your browser, though strict browser security policies might occasionally affect some features (like custom fonts or local storage if added later).

## Features
- **Minimalist Design**: Clean interface with thoughtful typography (Outfit & DM Sans).
- **Life Visualization**: Inputs your birth date to generate a grid of weeks lived vs. weeks remaining (based on a 90-year horizon).
- **Reflective Stats**: Shows "Summers Left", "Saturdays Left", and current "Life Era".
- **Dynamic Background**: Subtle particle system for a living feel.
- **Dark Mode**: Toggle between light and dark themes.

Enjoy your reflection!
