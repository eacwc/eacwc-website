# Empathy + Action = Change Website

A modern, responsive website for Empathy+Action=Change (EACWC) - a cooperative alliance built on empathy and kindness, focused on empowering marginalized individuals in our community.

## 🌐 Website

Visit: [www.eacwc.org](https://www.eacwc.org)

## 📋 About

Empathy+Action=Change is a volunteer-driven cooperative alliance that:
- Strengthens and empowers marginalized individuals
- Encourages active participation in community growth
- Fosters connection, engagement, acceptance, action, transformation, and learning
- Creates spaces where love and belonging thrive

## 🚀 Deployment to GitHub Pages

This website is designed to be deployed using GitHub Pages. Follow these steps:

### Option 1: Automatic Deployment (Recommended)

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it `eacwc` or any name you prefer
   - Make it public (required for free GitHub Pages)

2. **Push Your Code**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: EACWC website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** in the left sidebar
   - Under **Source**, select `main` branch and `/ (root)` folder
   - Click **Save**
   - Your site will be available at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

4. **Custom Domain (Optional)**
   - In the same Pages settings, add your custom domain `www.eacwc.org`
   - Add a `CNAME` file to your repository root with the content: `www.eacwc.org`
   - Configure DNS records with your domain provider:
     - Add a CNAME record: `www` → `YOUR_USERNAME.github.io`
     - Or add A records pointing to GitHub Pages IPs (see GitHub Pages docs)

### Option 2: Using GitHub Actions (Advanced)

If you want more control, you can set up a GitHub Actions workflow for deployment.

## 📁 Project Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript for interactivity
├── README.md          # This file
└── .nojekyll          # Prevents Jekyll processing (if needed)
```

## 🛠️ Local Development

To view the website locally:

1. **Simple Method**: Open `index.html` in your web browser

2. **Using a Local Server** (Recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
   
   Then visit `http://localhost:8000` in your browser

## 🎨 Features

- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Accessible**: Semantic HTML and proper ARIA labels
- **Fast Loading**: Optimized CSS and JavaScript
- **SEO Friendly**: Proper meta tags and semantic structure

## 📝 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... */
}
```

### Content
Edit `index.html` to update:
- Organization information
- Mission and values
- Contact information
- Donation details

## 📄 License

This project is open source and available for the Empathy+Action=Change organization.

## 🤝 Contributing

This is a volunteer-driven project. Contributions are welcome!

## 📧 Support

For questions or support, please contact the Empathy+Action=Change organization.

---

**Built with ❤️ for Empathy+Action=Change**
