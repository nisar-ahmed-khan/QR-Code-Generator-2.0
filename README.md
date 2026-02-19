QR Code Generator 2.0

An interactive QR Code Generator built using HTML, CSS, and JavaScript.
This project started as a simple QR generator, but I rebuilt it with a stronger focus on user experience, state management, and clean interaction flow rather than just functionality.

Project Overview
The goal was not just to generate a QR code but to understand how dynamic data, UI states, and user interaction work together in a real frontend application.

Instead of keeping it static, I designed it to behave like a small tool with proper UI transitions and logic control.

🔄 How It Works
•The user enters text or a URL.
•The input is safely processed using encodeURIComponent() to handle special characters.
•A dynamic API request URL is constructed.
•The QR image source is updated in real time.
•The Generate button smoothly transitions to a Download button.
•The QR appears with a fade + scale animation.
•If the user edits the input again, the UI automatically resets to the initial state.
•Every different input produces a completely different QR code pattern because the encoded string sent to the API changes.

Even a small character difference results in a new QR matrix structure.

Key Features
•Dynamic QR generation based on user input
•Safe URL encoding for reliable API requests
•Animated button state transition (Generate ↔ Download)
•Smooth QR appearance using GPU-friendly CSS animations
•Download QR as PNG
•Automatic UI reset on input change

Tech Stack:
•HTML5
•CSS3
•JavaScript
•QR Server API
