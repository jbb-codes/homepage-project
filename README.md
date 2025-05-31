# Personal Portfolio Homepage

A modern, responsive personal portfolio website designed to showcase your skills, projects, and contact information. This project serves as a professional online presence to share your work with potential employers or clients.

## Description

This portfolio website is a clean, responsive design built with modern web technologies. It features a gradient-colored layout with three main sections: an about me section, a project showcase, and a contact section. The site is fully responsive and adapts to mobile, tablet, and desktop screen sizes, ensuring a great user experience across all devices.

## Features

### Responsive Design

- Mobile-first approach with breakpoints for tablet (885px) and desktop (1201px)
- Fluid typography and responsive images using responsive image techniques
- Adaptive layout that reorganizes content based on screen size

### About Me Section

- Personal introduction with a professional photo
- Brief bio text to introduce yourself to visitors
- Social media links to connect with you on other platforms

### Projects Showcase

- Flexbox layout displaying your portfolio projects
- Each project includes:
  - Screenshot/preview image
  - Project title
  - GitHub repository link
  - Live demo link
  - Brief project description

### Contact Section

- Professional contact information
- Physical address
- Phone number and email
- Social media icons
- Secondary profile image

## Technologies Used

- **HTML5** - Semantic markup for structure
- **CSS3** - Custom styling with:
  - Flexbox for layout
  - CSS Variables
  - Media queries for responsive design
  - Custom web fonts (Playfair and Roboto)
- **JavaScript** - For Webpack CSS import
- **Webpack** - Module bundling and development environment
- **NPM Packages**:
  - css-loader
  - html-loader
  - html-webpack-plugin
  - style-loader
  - webpack-dev-server

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/homepage-project.git
   cd homepage-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Development

### Starting the Development Server

To run the development server with hot reloading:

```bash
npm run start
```

This will start the webpack development server, usually at http://localhost:8080

### Building for Production

To build the project for production:

```bash
npm run build
```

This will create optimized production files in the `dist` directory.

### Customizing Content

1. **Personal Information**: Edit the `template.html` file to update your name, bio, and contact information.
2. **Styling**: Modify the `styles.css` file to change colors, fonts, or layout.
3. **Images**: Replace the image files in the `images` directory with your own photos.
4. **Projects**: Update the project sections in `template.html` with your own project details.

## License

[MIT License](LICENSE)

## Author

[Jarren Bess](https://github.com/yourusername)
