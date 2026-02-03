# Leon - Creative & Minimal Agency Web Template

Leon is a clean, responsive, and minimal HTML/CSS agency template for showcasing services, portfolio projects, and company information. Easy to customize via CSS variables and ready to deploy as a static site or starter landing page.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Features

- ✨ **Modern & Minimal Design** - Clean and professional layout
- 📱 **Fully Responsive** - Works perfectly on all devices (mobile, tablet, desktop)
- 🎨 **Customizable Colors** - Easy-to-use CSS variables for theme customization
- ⚡ **Fast & Lightweight** - Optimized performance with minimal dependencies
- 🎯 **Smooth Scrolling** - Enhanced user experience with smooth page scrolling
- 📦 **Well-Organized** - Clean code structure for easy maintenance

## Sections

- **Header** - Navigation menu with hamburger icon for mobile
- **Landing** - Eye-catching hero section with background image
- **Features** - Showcase key features or highlights
- **Services** - Display your services/offerings with icons
- **Portfolio** - Showcase your projects with cards
- **About** - Tell your story with image and descriptive text
- **Contact** - Contact information and social media links
- **Footer** - Footer with copyright information

## Project Structure

```
Template-1-Leon/
├── index.html           # Main HTML file
├── css/
│   ├── leon.css        # Main stylesheet
│   ├── normalize.css   # CSS reset
│   └── all.min.css     # Font Awesome icons
├── images/             # Image assets
├── webfonts/           # Font files
└── README.md          # This file
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables
- **Font Awesome** - Icon library
- **Google Fonts** - Work Sans font family
- **Responsive Design** - Mobile-first approach with media queries

## CSS Variables

The template uses CSS custom properties for easy color customization:

```css
:root {
    --main-color: #10cab7;          /* Primary accent color */
    --secondary-color: #2c4755;     /* Secondary color */
    --Section-padding: 60px;        /* Section padding */
    --section-color: #f6f6f6;       /* Background color */
    --paragraph-color: #777;        /* Text color */
    --special-color: #ebeced;       /* Special elements color */
}
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/leon-template.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd leon-template
   ```

3. **Open in your browser**
   - Simply open `index.html` in your web browser
   - Or use a local server (e.g., Live Server in VS Code)

## Customization

### Change Colors
Edit the CSS variables in `css/leon.css` (lines 2-7):
```css
:root {
    --main-color: #your-color;
    --secondary-color: #your-color;
    /* ... update other colors ... */
}
```

### Update Content
Edit the text and images directly in `index.html`:
- Update service descriptions
- Add/remove portfolio items
- Change contact information
- Update about section text

### Add More Sections
Use the existing section structure as a template to add new sections to the page.

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Responsive Breakpoints

- **Mobile:** < 768px
- **Tablet:** 768px - 991px
- **Desktop:** 992px - 1199px
- **Large Desktop:** ≥ 1200px

## Dependencies

- [Font Awesome Icons](https://fontawesome.com/) - For beautiful icons
- [Google Fonts - Work Sans](https://fonts.google.com/specimen/Work+Sans) - Typography

## Credits

**Design Credits:** This project is based on the free template design from [Graphberry](https://www.graphberry.com/item/leon-html-agency-template). The original design concept and layout were created by Graphberry and adapted for this implementation.

Perfect template for:
- Freelancers
- Creative agencies
- Portfolio websites
- Service-based businesses
- Startup landing pages

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## Contact

For questions or support, please open an issue on GitHub.

---

**Made with ❤️ by Amr Khaled**
