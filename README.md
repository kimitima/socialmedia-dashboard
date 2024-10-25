Social Media App 🌐
A modern, responsive social media application with dynamic theme switching capabilities. Built using HTML, CSS, and JavaScript.
🌟 Features
accessibility
Theme Toggle-   take system color by default but can change using toggle
https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme
three point toggle -https://codepen.io/renddrew/pen/bRomab
updating css variables using  javascript
https://css-tricks.com/updating-a-css-variable-with-javascript/
https://webaim.org/techniques/css/invisiblecontent/-screen  only reader = texts that are only visible to the  screen but are not visible to the user or someone  browsing the page


Seamless dark/light mode switching
User preference persistence using localStorage
Smooth transition animations


Core Social Features

social media dashboard



🛠️ Technologies Used

HTML5
CSS3

Custom variables for theming
Flexbox/Grid for layouts
Media queries for responsiveness


JavaScript (Vanilla)

DOM Manipulation
Event Handlers
Local Storage



🚀 Getting Started

Clone the repository:
bashCopygit clone https://github.com/yourusername/social-media-app.git

Open index.html in your browser
Start developing!

💡 Implementation Details
Theme Toggle
The dark/light mode toggle is implemented using CSS variables and JavaScript:
cssCopy/* Example of theme variables */
:root {
  --primary-bg: #ffffff;
  --text-color: #333333;
}

[data-theme="dark"] {
  --primary-bg: #1a1a1a;
  --text-color: #ffffff;
}
🔄 Coming Features

 User Authentication
 Image Upload
 Comment System
 Real-time Notifications
 Direct Messaging

🤝 Contributing

Fork the repository
Create your feature branch: git checkout -b feature/NewFeature
Commit your changes: git commit -m 'Add NewFeature'
Push to the branch: git push origin feature/NewFeature
Submit a pull request

📝 Learning Resources

MDN Web Docs
CSS-Tricks
JavaScript.info

📜 License
This project is licensed under the MIT License - see the LICENSE.md file for details.
