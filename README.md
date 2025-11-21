# Manoj's Portfolio Website

🔗 Link: https://manoj-9899.github.io/manojpawar/

A fully responsive, modern, and interactive portfolio website built with HTML, CSS, and JavaScript.

## Features
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop.
- **Dark Mode**: Toggle between light and dark themes.
- **Interactive Elements**: Typing effect, scroll animations, and hover effects.
- **Sections**: Hero, About, Skills, Projects, Education, Contact.
- **Contact Form**: Integrated with Formspree for email submissions.

## Setup & Deployment

### Local Development
1. Clone the repository or download the files.
2. Open `index.html` in your web browser.
3. To make changes, edit the HTML, CSS, or JS files in your code editor.

### Deployment (GitHub Pages)
1. Push this code to a GitHub repository.
2. Go to the repository **Settings** > **Pages**.
3. Under **Source**, select `main` (or `master`) branch and click **Save**.
4. Your site will be live at `https://yourusername.github.io/repository-name`.

## Customization

### Contact Form
To make the contact form work, you need to sign up for [Formspree](https://formspree.io/).
1. Create a new form on Formspree.
2. Copy your unique Form ID endpoint.
3. Open `index.html` and find the `<form>` tag in the Contact section.
4. Replace `https://formspree.io/f/YOUR_FORM_ID` with your actual endpoint.

### Adding Projects
To add a new project, copy the `.project-card` HTML block in `index.html` and paste it inside the `.projects-grid` container. Update the image, title, description, and links.

### Updating Skills
To add a new skill, copy the `.skill-card` HTML block in `index.html` and paste it inside the `.skills-grid`. Update the icon (using FontAwesome classes) and the skill name.

```

## Credits
- Icons: [FontAwesome](https://fontawesome.com/)
- Fonts: [Google Fonts](https://fonts.google.com/)
