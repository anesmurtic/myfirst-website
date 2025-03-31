# Personal Website

A clean, minimalist personal website with dark mode support, smooth animations, and a functional contact form.

## Features

- 🎨 Clean, minimalist design
- 🌓 Dark/Light mode toggle with system preference detection
- ✨ Smooth scroll animations
- 📱 Fully responsive layout
- 📝 Functional contact form
- 🔍 SEO optimized
- ♿ Accessibility focused

## Setup Instructions

1. Clone this repository:
```bash
git clone https://github.com/anesmurtic
cd your-website
```

2. Replace the placeholder content:
   - Update `index.html` with your personal information
   - Replace `placeholder-profile.jpg` with your profile picture
   - Update social media links in the footer
   - Customize the color scheme in `styles.css` (optional)

3. Set up the contact form:
   - Sign up for a [Formspree](https://formspree.io/) account
   - Create a new form and get your form ID
   - Replace `your-formspree-id` in the form action URL in `index.html`

## Deployment

### Option 1: GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select your main branch as the source
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Vercel

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel
```

3. Follow the prompts to complete deployment

## Customization

### Colors
The website uses CSS variables for easy color customization. Edit the following in `styles.css`:

```css
:root {
    --bg-primary: #ffffff;
    --bg-secondary: #f5f5f5;
    --text-primary: #121212;
    --text-secondary: #666666;
    --accent-color: #6E07F3;
    --border-color: #e0e0e0;
    --shadow-color: rgba(0, 0, 0, 0.1);
}

[data-theme="dark"] {
    --bg-primary: #121212;
    --bg-secondary: #1e1e1e;
    --text-primary: #F5F5F7;
    --text-secondary: #a0a0a0;
    --accent-color: #8B5CF6;
    --border-color: #2d2d2d;
    --shadow-color: rgba(0, 0, 0, 0.3);
}
```

### Profile Image
1. Add your profile image to the project root
2. Name it `placeholder-profile.jpg` or update the image source in `index.html`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use this template for your personal website! 