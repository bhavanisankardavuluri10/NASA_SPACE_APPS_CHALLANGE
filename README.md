
# NASA_SPACE_APPS_CHALLANGE
Here’s a sample `README.md` file for your project:

---

# GLOBE Quest Web Application

GLOBE Quest is an interactive web application designed to educate students about environmental issues using GLOBE protocols. Through storytelling and challenges, students explore their local environments, gather data, and contribute to global scientific research. The application features a visually appealing interface, including a dynamic login system that greets users with personalized messages.

## Features

- **Responsive Navbar**: Includes links to essential pages like Home, About, Leaderboard, Resources, Contact, and MyTeam.
- **Personalized Welcome**: After login, the page dynamically greets the user by name.
- **Gradient Background**: A visually engaging gradient background animation for modern aesthetics.
- **Interactive Buttons**: Call-to-action buttons with hover effects, allowing users to sign up or log out easily.
- **Storytelling Section**: Introduction to the GLOBE Quest concept and its purpose, inviting users to join the initiative.

## Project Structure

- **HTML**: The main structure of the web application is handled via HTML. It includes the dynamic welcome feature, navbar, and content sections.
- **CSS**: Embedded CSS is used to style the layout, buttons, typography, background, and overall visual elements.
- **JavaScript**: JavaScript dynamically displays the username on the login page by extracting query parameters from the URL.

## File Structure

```
.
├── index.html            # Main entry point of the application
├── style.css             # External CSS (optional if you extract from inline styles)
├── assets/
│   └── globe-image.jpg   # Placeholder for the background image used in the app
└── README.md             # Project documentation
```

## How It Works

### 1. Navbar

The navigation bar provides easy access to the major sections of the application:
- **Home**: Returns to the landing page.
- **About**: Details about the GLOBE Quest initiative.
- **Leaderboard**: Competitive ranking of participants.
- **Resources**: Educational materials and GLOBE protocol documentation.
- **Contact**: Contact details for further assistance.
- **MyTeam**: A dedicated space for users to manage their team.

### 2. Dynamic Login and Welcome Message

Upon login, the user is redirected to a welcome page where their username is extracted from the URL and displayed on the page:
```js
const params = new URLSearchParams(window.location.search);
const username = params.get("username");
document.getElementById("username").textContent = username;
```

### 3. Interactive Content

- The landing page offers a brief introduction to GLOBE Quest and an invitation for users to join the quest.
- Buttons are styled to be visually appealing and interactive with hover effects.

## Setup Instructions

1. Clone the repository or download the project files:
   ```bash
   git clone (https://github.com/bhavanisankardavuluri10/NASA_SPACE_APPS_CHALLANGE.git)
   ```

2. Open the `index.html` file in a web browser:
   ```bash
   open index.html
   ```

3. Customize the assets, such as the background image (`globe-image.jpg`) or the logo (`GLOBE TROTTERS`), by replacing the image link or adjusting the CSS styles.

## Future Enhancements

- **Backend Integration**: Connect to a backend server (e.g., Node.js, Express, MongoDB) for full authentication, leaderboard management, and real-time environmental data collection.
- **Mobile Optimization**: Further enhance the responsiveness for better mobile device support.
- **Interactive Challenges**: Add gamified features where students can complete environmental challenges and earn badges.

## License

This project is licensed under the MIT License.

## Contributors


-Balu - Developer
-Naveen-Analyst and Team lead
-Charu-Frontend Developer
-Anshuman Samanta - Developer
-Plaksha-Astronomist
-Mithin-Astronomist
- GLOBE Protocol - Educational materials and guidelines

## Acknowledgements

- Special thanks to NASA’s GLOBE Protocol initiative for inspiring this project.
- Icons and images used are sourced from open web repositories.

---

