# Moshify - Cloud Hosting Landing Page

A modern, responsive landing page for a cloud hosting service built with HTML, CSS, and JavaScript.
Features a component-based architecture and optimized performance with responsive images and
animations.

## 🚀 Features

- **Responsive Design** - Fully responsive layout that works on all devices
- **Component-Based Architecture** - Modular HTML components for easy maintenance
- **Performance Optimized** - WebP images with fallbacks, lazy loading, and optimized assets
- **Modern CSS** - CSS Grid, Flexbox, and custom properties
- **Interactive Elements** - Collapsible navigation, smooth animations with AOS
- **SEO Optimized** - Semantic HTML, meta tags, and Open Graph properties
- **Cross-Browser Compatible** - Normalized CSS for consistent rendering

## 🛠️ Tech Stack

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Modern CSS with Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Interactive components and DOM manipulation
- **Parcel** - Build tool for development and production
- **AOS (Animate On Scroll)** - Scroll-triggered animations
- **Google Fonts** - Inter font family for typography

## 📁 Project Structure

```
moshify/
├── css/
│   ├── normalize.css          # CSS reset and normalization
│   └── styles.css             # Main stylesheet
├── js/
│   └── main.js               # JavaScript functionality
├── images/                   # Optimized images (WebP + fallbacks)
├── components/               # Reusable HTML components
│   ├── navbar/
│   ├── collapsible/
│   ├── button.html
│   ├── card.html
│   └── ...
├── block/                    # Page section components
│   ├── hero.html
│   ├── feature.html
│   ├── testimonial.html
│   └── ...
├── Layout/
│   └── grid.html            # Grid system examples
├── index.html               # Main landing page
├── playground.html          # Component testing page
└── package.json            # Project dependencies
```

## 🎨 Components

The project uses a modular component system:

### UI Components

- **Buttons** - Various button styles (primary, secondary, accent, outline)
- **Cards** - Content containers with headers and bodies
- **Badges** - Small status indicators
- **Icons** - SVG sprite-based icon system
- **Forms** - Input groups and form elements
- **Lists** - Styled list components
- **Media Objects** - Image + content combinations

### Layout Components

- **Grid System** - Responsive CSS Grid layouts
- **Navigation** - Collapsible mobile-friendly navbar
- **Hero Section** - Landing page header with CTA
- **Feature Blocks** - Service highlight sections
- **Testimonials** - Customer review components
- **Pricing Plans** - Subscription plan cards
- **Footer** - Multi-column footer with links

## 🚀 Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm or yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd moshify
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm start
   ```

   or

   ```bash
   npx parcel index.html
   ```

4. **Build for production**
   ```bash
   npm run build
   ```
   or
   ```bash
   npx parcel build index.html
   ```

## 📱 Responsive Breakpoints

The design adapts to different screen sizes:

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Key Sections

1. **Hero Section** - Main value proposition with CTA
2. **Domain Search** - Interactive domain name search
3. **Pricing Plans** - Three-tier hosting plans
4. **Features** - Key service benefits with icons
5. **Showcase** - Control panel preview
6. **Testimonials** - Customer reviews
7. **Call-to-Action** - Final conversion section
8. **Footer** - Links and company information

## 🔧 Customization

### Colors

Primary colors are defined as CSS custom properties in `styles.css`:

- Primary: Blue theme
- Secondary: Orange accents
- Dark: Navigation and footer backgrounds

### Typography

- Font Family: Inter (Google Fonts)
- Responsive font sizes using clamp()
- Consistent vertical rhythm

### Images

- WebP format with PNG/JPG fallbacks
- Retina-ready (@2x versions)
- Optimized file sizes

## 📈 Performance Features

- **Lazy Loading** - Images load as needed
- **WebP Images** - Modern format with fallbacks
- **Minified Assets** - Compressed CSS and JS
- **Font Display Swap** - Improved font loading
- **Preconnect** - Faster Google Fonts loading

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE11+ (with graceful degradation)

## 👨‍💻 Author

Created as part of a web development learning project.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test responsiveness across devices
5. Submit a pull request
