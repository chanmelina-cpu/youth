# YouthOK Application Blueprint

## Overview

YouthOK is a mobile-first web application designed to provide mental wellness support for young adults. The application allows users to track their mood, and will eventually connect them with coaches, counselors, and peers for support. The application is built using modern web technologies, including HTML, CSS, and JavaScript, and leverages Firebase for backend services.

## Design and Features

### Implemented

*   **Application Shell:** A mobile-first design with a header, main content area, and navigation.
*   **Header:** Displays the application title "YouthOK", a placeholder logo, a back button, and a menu button.
*   **Home Screen:**
    *   Prompts the user with "What is your mood now?"
    *   Presents a grid of six mood trackers: Happy, Sad, Anxious, Excited, Calm, and Angry, currently represented by emojis.
    *   Includes "Youth" and "Coach" buttons.
*   **About Us Page:**
    *   Displays a mission statement and information about the team.
*   **Styling:**
    *   Modern, clean design with a defined color palette and typography.
    *   Responsive design for mobile devices.

### Current Plan

1.  **Create Custom SVG Icons:** Replace the current emoji-based mood trackers with custom SVG icons to create a more unique and polished user interface. This will involve:
    *   Creating a new `icons` directory to store the SVG files.
    *   Designing and creating SVG icons for each of the six moods.
    *   Updating the `index.html` file to use the new SVG icons.
    *   Adjusting the `style.css` file to ensure the icons are displayed correctly.

2.  **Implement Firebase Authentication:** Enable user registration and login functionality using Firebase Authentication.

3.  **Develop Mood Tracking Functionality:** Store the user's mood selections in a database.

4.  **Build out Additional Screens:** Create the "Registration", "Login", and "Contact Us" screens.
