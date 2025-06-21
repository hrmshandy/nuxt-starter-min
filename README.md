# Nuxt Minimal Starter

A minimal starter pack for building modern, full-stack web application built with Nuxt.js, providing a clean and responsive user interface with powerful developer experience.

## 🚀 Tech Stack

### Frontend Framework
- **[Nuxt.js 3.17+](https://nuxt.com/)** - Vue.js framework for production-ready applications
- **[Vue.js 3.5+](https://vuejs.org/)** - Progressive JavaScript framework
- **[TypeScript 5.8+](https://www.typescriptlang.org/)** - Type-safe JavaScript development

### Styling & UI
- **[Tailwind CSS 4.1+](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Shadcn/UI](https://ui.shadcn.com/)** - Re-usable components built with Radix Vue and Tailwind CSS
- **[Reka UI](https://reka-ui.com/)** - Vue component library for building design systems
- **[Lucide Vue Next](https://lucide.dev/)** - Beautiful & consistent icon set

### Developer Experience
- **[Biome](https://biomejs.dev/)** - Fast linter and formatter for JavaScript/TypeScript
- **[Nuxt DevTools](https://devtools.nuxt.com/)** - Enhanced development experience
- **[Nuxt Test Utils](https://nuxt.com/docs/getting-started/testing)** - Testing utilities for Nuxt applications

### Additional Features
- **[@nuxt/fonts](https://fonts.nuxtjs.org/)** - Font optimization and management
- **[@nuxt/icon](https://icon.nuxtjs.org/)** - Icon management and optimization  
- **[@nuxt/image](https://image.nuxtjs.org/)** - Image optimization and processing

## 📋 Requirements

Before getting started, ensure you have the following installed:

- **Node.js** 18.x or higher ([Download](https://nodejs.org/))
- **pnpm** 9.x or higher ([Install pnpm](https://pnpm.io/installation))
- **Git** for version control ([Download](https://git-scm.com/))

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd nuxt-starter-min
```

### 2. Install Dependencies

```bash
pnpm install
```

### 3. Start Development Server

```bash
pnpm dev
```

The application will be available at `http://localhost:3000`

## 📜 Available Scripts

### Development
```bash
# Start development server with hot reload
pnpm dev

# Run development server with debugging
pnpm dev --debug
```

### Code Quality
```bash
# Format code with Biome
pnpm biome:format

# Lint code with Biome
pnpm biome:lint

# Check and fix code issues
pnpm biome:check
```

### Building & Deployment
```bash
# Build for production
pnpm build

# Generate static site
pnpm generate

# Preview production build locally
pnpm preview
```

### UI Components
```bash
# Add new Shadcn/UI components
pnpm ui:add
```

## 🏗️ Project Structure

```
savebox/
├── assets/           # Stylesheets, images, fonts
├── components/       # Vue components
│   └── ui/          # Reusable UI components
├── lib/             # Utility functions and helpers
├── public/          # Static assets
├── server/          # Server-side functionality
├── app.vue          # Main application component
├── nuxt.config.ts   # Nuxt configuration
└── package.json     # Project dependencies and scripts
```

## 🔧 Configuration

The project uses several configuration files:

- `nuxt.config.ts` - Nuxt.js configuration
- `biome.json` - Code formatting and linting rules
- `components.json` - Shadcn/UI component configuration
- `tsconfig.json` - TypeScript configuration

## 🚀 Deployment

### Build for Production

```bash
pnpm build
```

### Static Site Generation

```bash
pnpm generate
```

For detailed deployment instructions, check the [Nuxt deployment documentation](https://nuxt.com/docs/getting-started/deployment).

## 📖 Learn More

- [Nuxt.js Documentation](https://nuxt.com/docs)
- [Vue.js Documentation](https://vuejs.org/guide/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Shadcn/UI Documentation](https://ui.shadcn.com/)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
