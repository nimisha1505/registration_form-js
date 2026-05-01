Interactive Animated Login & Registration Form
A modern, responsive, and highly animated Login and Sign-Up interface built using HTML, CSS, and Vanilla JavaScript. This project features a unique sliding "glassmorphism" effect with background sweeping animations and floating labels.

🚀 Features
Dual-Form Toggle: Seamlessly switch between Login and Registration without page reloads.
Dynamic Backgrounds: Custom-shaped background animations that sweep across the screen during transitions.
Floating Labels: Interactive input fields where labels move and change color upon focus or input.
Responsive Design: Styled with Poppins font and optimized for different screen sizes.
Boxicons Integration: Modern iconography for usernames, emails, and passwords.

🛠️ Tech Stack
HTML5: Semantic structure for the forms and content.
CSS3: Custom properties (variables), Flexbox, and complex CSS transitions/transforms.
JavaScript: Vanilla JS for DOM manipulation and class toggling.

Icons: Boxicons

📁 Project Structure
├── index.html   # Main structure of the forms
├── style.css    # All styling and animation logic
└── script.js   # Logic for toggling the 'active' class

⚙️ How to Use
Clone the repository: git clone https://github.com/your-username/registration-form.git

Open the project:
Simply open index.html in any modern web browser.

Toggle Forms:
Click on the "Sign Up" link to see the login form slide out and the registration form slide in. Click "Login" to return.

🎨 Key Animations
.active Toggle: When the active class is added to the .wrapper via JavaScript, it triggers the translateX properties in CSS to move the forms.

Input Focus: Uses the :focus and :valid pseudo-classes to keep labels in the "active" state even after a user stops typing, provided the field isn't empty.

Customization Tip
To change the primary theme color (currently Cyan #0ef), simply search and replace #0ef in style.css with your preferred hex code.

Developed with ❤️ by Nimisha Agarwal.
