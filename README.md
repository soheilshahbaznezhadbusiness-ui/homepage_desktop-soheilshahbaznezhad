# Homepage Desktop - سهیل بیمه

A modern, desktop-first insurance company homepage built with pure HTML, CSS, and JavaScript for the "soheilbime" brand.

## Technologies Used

- **HTML5**: Semantic markup with RTL support for Persian
- **CSS3**: Modern CSS with custom properties, Grid, and desktop-first responsive design
- **JavaScript (Vanilla)**: Interactive navigation, smooth scrolling, and scroll animations
- **Google Fonts**: Vazirmatn (Persian/Arabic font) and Caveat for branding

## Features

- ✅ Desktop-first responsive design (optimized for large screens)
- ✅ Modern purple & white color scheme
- ✅ Sticky navigation with smooth scrolling
- ✅ Multi-column grid layouts (3-column on desktop, responsive on tablets/mobile)
- ✅ Pricing plans with featured option
- ✅ Customer testimonials section
- ✅ Interactive animations on scroll
- ✅ Accessibility features (keyboard navigation, focus states)
- ✅ Fully RTL for Persian language

## Design Decisions

- **Color Palette**: Purple (#6C5CE7) as primary brand color with white backgrounds
- **Layout**: CSS Grid for main layouts, Flexbox for navigation and components
- **Typography**: Vazirmatn for body text with Caveat for logo/branding
- **Spacing System**: Consistent spacing scale using CSS custom properties
- **Animations**: Subtle animations on scroll for enhanced UX

## Running Locally

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required!

## Publishing to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon and select "New repository"
3. Name your repository (e.g., `homepage_desktop-soheilshahbaznezhad`)
4. Initialize with README (optional)
5. Click "Create repository"

### Step 2: Upload Files

1. Open your terminal/command prompt in the project folder
2. Initialize git:
   ```bash
   git init
   ```
3. Add all files:
   ```bash
   git add .
   ```
4. Commit:
   ```bash
   git commit -m "Initial commit: Desktop homepage"
   ```
5. Add your GitHub repository as remote:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/homepage_desktop-soheilshahbaznezhad.git
   ```
6. Push to GitHub:
   ```bash
   git branch -M main
   git push -u origin main
   ```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll to "Pages" section
4. Under "Source", select "main" branch
5. Select "/ (root)" as folder
6. Click "Save"
7. Your homepage will be live at: `https://YOUR_USERNAME.github.io/homepage_desktop-soheilshahbaznezhad/`

## File Structure

```
homepage_desktop-soheilshahbaznezhad/
├── index.html          # Main HTML file
├── style.css           # Desktop-first responsive CSS
├── script.js           # Navigation and animations
├── README.md           # This file
└── LICENSE             # MIT License
```

## Sections

- **Hero**: Large headline with CTAs
- **Features**: 6 insurance services in grid layout
- **About**: Company mission and statistics
- **Portfolio**: 3 example insurance plans
- **Pricing**: 3 pricing tiers with estimated prices (Persian format)
- **Testimonials**: Customer reviews with avatars
- **Footer**: Contact info and social links

## Pricing Information

The pricing section uses estimated prices for Iranian insurance market (based on 1403 reference prices). All prices are clearly marked as samples and may vary based on vehicle type and insurance history.

## Accessibility

- Semantic HTML elements
- Keyboard navigation support
- Focus states for interactive elements
- ARIA labels where appropriate
- High contrast for readability
- Minimum touch target sizes (44px)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - see LICENSE file for details

