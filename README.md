# TechNet Website

A modern, responsive website built with HTML, CSS, and JavaScript, deployed on GitHub Pages.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient backgrounds and smooth animations
- **Fast Loading**: Optimized for performance
- **GitHub Pages Ready**: Automatically deployed with GitHub Actions

## 📁 Project Structure

```
TechNet/
├── index.html          # Main website file
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment workflow
├── src/                # Original Java web application
│   ├── main/
│   │   ├── java/       # Java servlets
│   │   └── webapp/     # JSP files
│   └── test/           # Test files
├── pom.xml             # Maven configuration
└── README.md           # This file
```

## 🌐 Live Website

The website is automatically deployed to GitHub Pages at:
**https://[your-username].github.io/[repository-name]**

## 🛠️ Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/[repository-name].git
   cd [repository-name]
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. Visit `http://localhost:8000` to view the website

## 📦 Deployment

### Automatic Deployment (Recommended)

The website is automatically deployed to GitHub Pages whenever you push changes to the main branch:

1. Make changes to your files
2. Commit and push to GitHub:
   ```bash
   git add .
   git commit -m "Update website"
   git push origin main
   ```
3. GitHub Actions will automatically build and deploy your site

### Manual Deployment

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select **GitHub Actions**
4. The deployment will start automatically

## 🎨 Customization

### Colors and Styling
Edit the CSS variables in `index.html` to customize:
- Background gradients
- Text colors
- Button styles
- Spacing and layout

### Content
- Update the welcome message
- Modify the features section
- Add new sections as needed

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients and animations
- **GitHub Pages**: Free hosting
- **GitHub Actions**: Automated deployment
- **Maven**: Java project management (for original servlet code)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

If you have any questions or need help, please open an issue on GitHub.

---

**Made with ❤️ and deployed on GitHub Pages**
