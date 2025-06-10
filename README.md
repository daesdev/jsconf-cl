# JSConf Chile 🇨🇱

![JSConf Chile Preview](./public/preview.webp)

JSConf Chile website built with modern web technologies, featuring a beautiful design and optimized performance.

## 🚀 Tech Stack

- **[Astro](https://astro.build/)** - Modern static site generator with partial hydration
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript development
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Bun](https://bun.sh/)** - Fast JavaScript runtime and package manager

## 🏗️ Architecture

This project follows **Atomic Design** principles for component organization:

```
src/components/
├── atoms/          # Basic building blocks (buttons, inputs, etc.)
├── molecules/      # Simple combinations of atoms
├── organisms/      # Complex components made of molecules/atoms
└── templates/      # Page-level components and layouts
```

## 🎨 Features

- **Modern Design System** - Atomic Design architecture
- **Performance Optimized** - Multiple image formats (AVIF, WebP, JPG)
- **Responsive Gallery** - Dynamic masonry layout with hover effects
- **Type Safety** - Full TypeScript integration
- **Modern Fonts** - Custom Magra font family
- **YouTube Integration** - Lite YouTube component for performance

## 📦 Installation

```bash
# Install dependencies
bun install

# Start development server
bun run dev

# Build for production
bun run build

# Preview production build
bun run preview
```

## 🎯 Project Structure

```
├── public/
│   ├── preview.webp           # Preview image
│   ├── fonts/                 # Custom fonts (Magra)
│   └── jsconf/gallery/        # Event gallery images
├── src/
│   ├── components/
│   │   ├── atoms/             # Basic components
│   │   ├── molecules/         # Gallery, forms, etc.
│   │   ├── organisms/         # Complex sections
│   │   └── templates/         # Page templates
│   ├── layouts/               # Page layouts
│   ├── pages/                 # Astro pages
│   └── styles/                # Global styles
└── astro.config.mjs           # Astro configuration
```

## 🖼️ Image Optimization

The project uses multiple image formats for optimal performance:
- **AVIF** - Modern format with best compression
- **WebP** - Widely supported modern format  
- **JPG/PNG** - Fallback for older browsers

Gallery component automatically groups images by filename and serves the best format available.

## 🎬 Components

### Gallery Component
Dynamic masonry gallery with:
- Automatic image grouping by filename
- Multiple format support (AVIF, WebP, JPG)
- Hover animations and effects
- Responsive column layout

### Picture Component
Optimized image component with:
- Automatic format selection
- Lazy loading
- Responsive sizing
- Fallback support

## 🚀 Development

```bash
# Run development server
bun run dev

# Access at http://localhost:4321
```

## 📝 License

[MIT License](./LICENSE)

---

Built with ❤️ for the Darío Espinoza