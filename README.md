# Professional Portfolio Website

A modern, responsive portfolio website showcasing professional projects, skills, and experience.

## Features

- Clean, modern design with responsive layout
- Projects showcase section
- Skills and experience presentation
- Contact information
- Optimized for all devices

## Technology Stack

- HTML5
- CSS3 (with custom styling)
- Responsive Design
- Google Fonts (Inter and Playfair Display)

## Important Notes

This portfolio is now a completely self-contained HTML/CSS website that doesn't rely on any external resources except Google Fonts. All CSS styles are included inline within the HTML file for maximum compatibility.

## Deployment Instructions

### Option 1: Deploy with GitHub Pages (Free and Easy)

1. Create a new repository on GitHub
2. Upload all files from the `portfolio-deploy` directory to your repository
3. Go to your repository settings
4. Scroll down to the GitHub Pages section
5. Select the main branch as the source and click Save
6. Your site will be published at `https://yourusername.github.io/repository-name/`

### Option 2: Deploy with Netlify (Free and Easy)

1. Sign up for a free Netlify account at [netlify.com](https://www.netlify.com/)
2. Drag and drop the entire `portfolio-deploy` folder onto the Netlify dashboard
3. Netlify will automatically detect the settings from the netlify.toml file
4. Your site will be deployed to a random subdomain (e.g., random-name.netlify.app)
5. You can change the subdomain in the site settings or connect your own custom domain

### Option 3: Deploy Locally

1. Simply open the `index.html` file in your browser to view the site
2. No server or build process required

### Option 4: Deploy with a Web Server

1. Copy all files to your web server's public directory (e.g., `/var/www/html/` for Apache)
2. Configure your server to serve the site (if needed)

## Troubleshooting Black/Blank Screen Issues

If you're still seeing a blank or black screen when viewing the portfolio:

1. **Try Different Browsers**: Test the site in Chrome, Firefox, Edge, or Safari to see if the issue is browser-specific.

2. **Disable Extensions**: Some browser extensions might be blocking content. Try viewing in an incognito/private browsing window.

3. **Check File Structure**: Make sure you're opening the `index.html` file directly, not just the folder.

4. **Direct Method**: Try this ultra-simple approach:
   - Create a new text file on your desktop
   - Copy ALL content from the `index.html` file
   - Save the file with a `.html` extension (e.g., `portfolio.html`)
   - Double-click to open this file directly in your browser

5. **Online Preview**: Try using a free online HTML preview service:
   - Go to [htmlpreview.github.io](https://htmlpreview.github.io/)
   - Paste your GitHub repo URL + /index.html
   - View the result

6. **Development Server**: If you have Node.js installed, you can run a simple server:
   ```
   npx serve portfolio-deploy
   ```

## Customization

To customize this portfolio:

1. Edit `index.html` to update personal information, projects, and content
2. Modify CSS styles directly in the `<style>` section of the index.html file
3. Replace image URLs with your own images

## License

This project is available for personal and commercial use.

## Credits

- Google Fonts for typography
- Placeholder images from Unsplash 