# CLENT Africa Website Developer Repository

## About CLENT Africa
CLENT Africa is dedicated to fostering sustainable development through education, renewable energy, environmental conservation, community engagement, and technology. Our mission is to create a sustainable and equitable future for Africa through collaborative and innovative solutions. 
### Focus: 
Development and maintenance of the official CLENT Africa website - www.clentafrica.org. 
### Contents: 
Source code for the website, including HTML, CSS, JavaScript. 
### Purpose: 
Ensure the website is up-to-date, user-friendly, and informative for visitors and stakeholders.

## Table of Contents
- [About CLENT Africa](#about-clent-africa)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Issues](#issues)
- [License](#license)
- [Contact](#contact)

## Getting Started
To get started with contributing to the CLENT Africa website development, follow these steps:

### Prerequisites
- Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
- Install [WordPress](https://wordpress.org/download/) locally for development and testing.

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/CLENTAfrica/web-dev.git
   cd web-dev
   ```

2. **Switch to staging branch**
   ```bash
   git checkout staging 
   cd web-dev
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm start
   ```

## Project Structure
Here's an overview of the project's structure:

```plaintext
website-dev/
├── public/               # Static files
├── src/                  # Source files
│   ├── components/       # React components
│   ├── pages/            # Page components
│   ├── styles/           # CSS and SCSS files
│   ├── utils/            # Utility functions
│   ├── App.js            # Main app component
│   ├── index.js          # Entry point
├── .gitignore            # Git ignore file
├── package.json          # NPM dependencies and scripts
├── README.md             # This file
└── wp-content/           # WordPress content (themes, plugins, etc.)
```

## Contributing
We welcome contributions from the community! To contribute, please follow these steps:

1. **Fork the repository:**
   Click the "Fork" button at the top right of this page to create a copy of this repository under your GitHub account.

2. **Clone your fork:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/web-dev.git
   cd web-dev
   ```

3. **Create a new branch:**
   ```bash
   git checkout -b feature-name
   ```

4. **Make your changes:**
   Implement your feature or fix a bug.

5. **Commit your changes:**
   ```bash
   git commit -m "Description of your changes"
   ```

6. **Push to your fork:**
   ```bash
   git push origin feature-name
   ```

7. **Create a pull request:**
   Navigate to the original repository and click the "New pull request" button.

## Issues
If you find any bugs or have feature requests, please create an issue [here](https://github.com/CLENTAfrica/web-dev/issues).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, please contact us at [info@clentafrica.org](mailto:info@clentafrica.org).
