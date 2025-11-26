# preed

A modern, responsive web application featuring a grid-based card layout with a sunny beach day color theme.

## Overview

preed is a web application that displays a collection of items in a responsive grid layout. The project features a clean, modern design with a teal and papaya color scheme, inspired by sun-drenched beach days. Each item is presented as a card with an image and descriptive text.

### Features

- **Responsive Grid Layout**: Adapts from single column (mobile) to 2 columns (tablet) to 3 columns (desktop)
- **Custom Color Theme**: "Sunny Beach Day" palette featuring navy, teal, soft sand, vivid orange, and cocoa
- **Modern Typography**: Uses Google's Roboto font family with multiple weights
- **Icon Integration**: FontAwesome icons for visual elements
- **Animated Elements**: Rotating school icon in the header

## Development

### Tech Stack

- **Build Tool**: Vite 7.2.4
- **Markup**: HTML5
- **Styling**: CSS3 with CSS custom properties (variables)
- **JavaScript**: ES6+ modules
- **Fonts**: Google Fonts (Roboto)
- **Icons**: FontAwesome

### Project Structure

```
preed/
├── index.html          # Main HTML file
├── package.json        # Project dependencies and scripts
├── LICENSE            # MIT License
├── public/            # Static assets
└── src/
    ├── main.js        # JavaScript entry point
    └── style.css      # Stylesheet with responsive design
```

### Getting Started

1. **Install dependencies**:

   ```bash
   npm install
   ```

2. **Run development server**:

   ```bash
   npm run dev
   ```

3. **Build for production**:

   ```bash
   npm run build
   ```

4. **Preview production build**:
   ```bash
   npm run preview
   ```

### CSS Architecture

The stylesheet is organized into logical sections:

- **Color Theme Variables**: CSS custom properties for consistent theming
- **Base Styles**: Global body and box-sizing rules
- **Header Section**: Flex-based header with navigation icons
- **Grid Layout**: Responsive CSS Grid implementation
- **Card Items**: Styled item cards with images
- **Media Queries**: Breakpoints at 480px (tablet) and 1024px (desktop)

### Color Palette

| Color Name      | HEX     | HSL                    | Usage            |
| --------------- | ------- | ---------------------- | ---------------- |
| Ink Black       | #001524 | hsla(205, 100%, 7%, 1) | Dark accents     |
| Stormy Teal     | #15616d | hsla(188, 68%, 25%, 1) | Primary/Headers  |
| Papaya Whip     | #ffecd1 | hsla(35, 100%, 91%, 1) | Background/Text  |
| Vivid Tangerine | #ff7d00 | hsla(29, 100%, 50%, 1) | Accent           |
| Brandy          | #78290f | hsla(15, 78%, 26%, 1)  | Secondary accent |

## License

MIT License - see [LICENSE](LICENSE) file for details.
