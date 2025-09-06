# Research Scientist Website

A modern, responsive website template designed specifically for research scientists and academics. This website showcases your research, publications, CV, and contact information in a professional and visually appealing format.

## Features

- **Modern Design**: Clean, professional layout with a beautiful gradient hero section
- **Responsive**: Fully responsive design that works on all devices (desktop, tablet, mobile)
- **Sections Included**:
  - Hero/Home section with introduction
  - About section with research interests and statistics
  - Research section highlighting current work and methods
  - Publications section with recent papers
  - CV section with education and download link
  - Contact section with multiple ways to reach you
- **Interactive Elements**: Smooth scrolling, mobile navigation, hover effects
- **Social Media Integration**: Links to LinkedIn, Twitter, Google Scholar, ORCID, and GitHub
- **GitHub Pages Ready**: Optimized for hosting on GitHub Pages

## Customization

### Personal Information
Replace the following placeholders in `index.html` with your actual information:

- `[Your Name]` - Replace with your full name
- `[Your Field]` - Replace with your research field (e.g., "Computer Science", "Biology", "Physics")
- `[Your Research Area]` - Replace with your specific research focus
- `[Your Research Domain]` - Replace with your broader research domain
- `[Research Area 1-4]` - Replace with your specific research interests
- `[X]` - Replace with your years of experience
- `your.email@university.edu` - Replace with your actual email
- `[Your University/Institution]` - Replace with your institution name
- `[City, State, Country]` - Replace with your location
- `+1 (XXX) XXX-XXXX` - Replace with your phone number

### Publications
Update the publications section with your actual papers:
- Replace publication titles, authors, and journal information
- Add links to your papers (DOI, journal website, or PDF)
- Update publication years

### Research Section
Customize the research cards with your actual:
- Current research projects
- Research methodologies
- Collaborations and partnerships

### CV Section
Update the education section with your actual:
- Degree information
- University names and graduation years
- Add a link to your actual CV PDF

### Social Media Links
Update the social media links in the contact section with your actual profiles:
- LinkedIn
- Twitter
- Google Scholar
- ORCID
- GitHub

### Profile Image
Replace the placeholder icon with your actual profile photo:
1. Add your photo to the project folder
2. Update the `.profile-image` section in the HTML to use an `<img>` tag instead of the icon

## GitHub Pages Setup

### Method 1: Using GitHub Web Interface

1. **Create a new repository** on GitHub:
   - Go to [GitHub](https://github.com) and sign in
   - Click "New repository"
   - Name it `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Make it public
   - Don't initialize with README (since we already have files)

2. **Upload your files**:
   - Click "uploading an existing file"
   - Drag and drop all your website files (index.html, styles.css, script.js, README.md)
   - Commit the changes

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website**:
   - Your website will be available at `https://your-username.github.io`
   - It may take a few minutes to deploy

### Method 2: Using Git Command Line

1. **Initialize Git repository**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Create GitHub repository**:
   - Create a new repository on GitHub named `your-username.github.io`

3. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages** (same as Method 1, step 3)

## File Structure

```
research-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

This website is compatible with all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Customization Tips

1. **Colors**: The main color scheme uses blue tones (#2563eb). You can change this by updating the CSS color values.

2. **Fonts**: The website uses Inter font from Google Fonts. You can change this by updating the font import and font-family declarations.

3. **Layout**: The website uses CSS Grid and Flexbox for layout. You can modify the grid structures in the CSS file.

4. **Animations**: The website includes smooth scrolling and hover effects. You can customize these in the JavaScript file.

## Support

If you need help customizing this website or have questions about GitHub Pages, feel free to:
- Check the GitHub Pages documentation
- Look at the source code comments
- Modify the code to fit your specific needs

## License

This template is free to use and modify for personal and academic purposes.

---

**Note**: Remember to replace all placeholder text with your actual information before publishing your website!