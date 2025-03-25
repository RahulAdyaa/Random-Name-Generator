Random Name Generator
Description
The Random Adjective-Noun Name Generator is a web application built using Node.js, Express, and EJS. It generates random name combinations from predefined adjective and noun lists, providing a fun and interactive user experience. The project also demonstrates best practices in web development, including server-side rendering, environment variable management, and UI enhancements using Tailwind CSS.

Features & Implementations
1. Project Setup
npm init → Initializes the Node.js project and creates a package.json file.

npm install express body-parser ejs dotenv → Installs required dependencies.

2. Server Setup & Routing
Express → Handles server requests and responses.

EJS → Templating engine for rendering dynamic HTML.

Body-Parser → Middleware for handling form data.

3. UI Enhancements with Tailwind CSS
Tailwind CSS is used for styling, ensuring a clean, responsive, and modern UI.

Custom styles are applied for buttons, form elements, and overall page layout.

4. Environment Variables Management
The project uses .env files (managed by dotenv) to store sensitive data such as API keys or configurations.

.gitignore is used to exclude .env and other unnecessary files from Git commits.

5. Static File Serving
Express serves static assets (CSS, images, etc.) from the public/ directory.

6. Random Name Generation Logic
GET / → Renders the home page with a form.

POST /generate → Generates a random name by selecting words from predefined lists and displays the result dynamically.

7. EJS Templates for Code Reusability
Includes partials (header.ejs, footer.ejs) for a modular and maintainable code structure.

8. Dynamic Year in Footer
JavaScript fetches the current year dynamically for display in the footer.
