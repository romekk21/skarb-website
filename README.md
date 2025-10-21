# Website Backbone

A responsive website template ready for localhost testing.

## Files Created

- `index.html` - Main HTML structure with semantic markup
- `styles.css` - Responsive CSS with mobile-first design
- `script.js` - JavaScript for interactivity and mobile navigation

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Smooth scrolling between sections
- **Modern CSS**: Uses CSS Grid, Flexbox, and modern properties
- **Accessibility**: Focus styles and semantic HTML
- **Performance**: Optimized with debounced scroll handlers

## Testing on Localhost

### Option 1: Using Python (Recommended)
```bash
cd /Users/romekkozdrowicz/Desktop/Website
python3 -m http.server 8000
```
Then open: http://localhost:8000

### Option 2: Using Node.js
```bash
cd /Users/romekkozdrowicz/Desktop/Website
npx serve .
```
Then open the URL shown in the terminal

### Option 3: Using PHP
```bash
cd /Users/romekkozdrowicz/Desktop/Website
php -S localhost:8000
```
Then open: http://localhost:8000

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Next Steps

1. Test the website on localhost using one of the methods above
2. Resize your browser window to test responsive design
3. Test on mobile devices using browser dev tools
4. Add your content to replace placeholder text
5. Customize colors, fonts, and styling as needed

## Structure

- **Header**: Fixed navigation with logo and menu
- **Hero Section**: Welcome area with call-to-action
- **About Section**: About content area
- **Services Section**: Grid of service cards
- **Contact Section**: Contact information area
- **Footer**: Copyright and additional links
