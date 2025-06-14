# C10 Insurance - Specialized Coverage for Chevy C10 Pickup Trucks

![C10 Insurance](https://img.shields.io/badge/C10-Insurance-14b8a6?style=for-the-badge)
![Eleventy](https://img.shields.io/badge/Eleventy-v2.0.1-000000?style=for-the-badge)
![Netlify Status](https://img.shields.io/badge/Netlify-Deployed-00C7B7?style=for-the-badge)

## 🚛 About C10 Insurance

C10 Insurance is a specialized insurance website dedicated exclusively to Chevy C10 pickup truck owners. We provide tailored coverage for all C10 models from 1960-1998, including the C10 Fleetside, Stepside, Suburban, Cheyenne, Scottsdale, and Silverado variants.

**Live Site**: [https://c10insurance.netlify.app](https://c10insurance.netlify.app)

## 🎯 Target Audience

- Chevy C10 pickup truck owners (1960-1998)
- C10 enthusiasts with restored classics
- Classic C10 collectors
- Daily C10 drivers seeking specialized coverage

## ✨ Features

- **C10-Specific Coverage**: Tailored insurance for every C10 variant
- **Model Timeline**: Interactive showcase of all C10 generations
- **Instant Quotes**: 60-second online quotes for C10 owners
- **Modification Friendly**: Coverage for restorations, engine swaps, and custom parts
- **C10 Parts Network**: Access to OEM and quality aftermarket parts
- **24/7 Support**: Dedicated C10 insurance specialists

## 🛠️ Tech Stack

- **Framework**: [Eleventy (11ty)](https://www.11ty.dev/) v2.0.1
- **Template Engine**: [Nunjucks](https://mozilla.github.io/nunjucks/)
- **Hosting**: [Netlify](https://www.netlify.com/)
- **Styling**: Component-scoped CSS with glassmorphism effects
- **Design**: Ultra-modern, futuristic aesthetic

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/MCERQUA/C10-Insurance.git

# Navigate to project directory
cd C10-Insurance

# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build
```

### Development Workflow

1. Run `echo init` at the start of each session (loads project context)
2. Check Component Registry before creating new components
3. Use Nunjucks syntax (NOT Liquid)
4. Test locally before pushing to main branch

## 📁 Project Structure

```
C10-Insurance/
├── src/
│   ├── _includes/
│   │   └── components/
│   │       └── sections/      # C10-specific components
│   ├── _layouts/              # Page layouts
│   ├── _data/                 # Global data files
│   ├── css/                   # Global styles
│   ├── js/                    # JavaScript files
│   └── index.njk              # Homepage
├── docs/                      # Documentation
│   ├── components/            # Component documentation
│   ├── development-log.md     # Development history
│   └── PROJECT_SUMMARY.md     # Project overview
└── AI/
    └── Memory/               # AI context files
        └── memory.json       # Project memory
```

## 🎨 Design System

### Color Palette

- **Primary Blue**: `#1e5ba8` → `#3b82f6`
- **Teal Secondary**: `#14b8a6` → `#06b6d4`
- **Dark Background**: `#050714` → `#0f172a`

### Components

The site uses a component-based architecture with 11 reusable components:

**C10-Specific Components:**
- `section-hero-c10` - Animated hero with C10 truck silhouette
- `section-c10-models` - Timeline of all C10 generations
- `section-why-c10` - Value proposition for C10 insurance
- `section-coverage-grid` - C10 coverage options
- `section-c10-stats` - Trust indicators and statistics
- `section-cta-c10` - Call to action with animated truck

## 📊 SEO Strategy

Optimized for C10-related keywords:
- C10 insurance
- Chevy C10 insurance
- C10 pickup insurance
- C10 Fleetside insurance
- C10 Stepside insurance
- All model years: 1960-1998

## 🔧 Component Development

Components follow these conventions:
- Self-contained with embedded styles
- BEM-like naming: `.c-[component-name]__[element]`
- Responsive design with mobile-first approach
- Documented in Component Registry

### Creating New Components

1. Check Component Registry first
2. Create in `src/_includes/components/sections/`
3. Follow naming convention: `section-[name].njk`
4. Include self-contained styles
5. Document immediately in registry
6. Update development log

## 📝 Documentation

- **[Component Registry](docs/components/COMPONENT_REGISTRY.md)** - All available components
- **[Development Log](docs/development-log.md)** - Development history
- **[Project Summary](docs/PROJECT_SUMMARY.md)** - Comprehensive overview
- **[Master Guide](docs/MASTER_DEVELOPMENT_GUIDE.md)** - Development guidelines

## 🚀 Deployment

The site automatically deploys to Netlify when changes are pushed to the main branch.

```bash
# Test build locally
npm run build

# Push to deploy
git push origin main
```

## 🤝 Contributing

1. Check Component Registry before creating new components
2. Follow the established design system
3. Test all changes locally
4. Document new components immediately
5. Update the development log

## 📞 Contact

For questions about the C10 Insurance website development:
- **Repository**: [https://github.com/MCERQUA/C10-Insurance](https://github.com/MCERQUA/C10-Insurance)
- **Live Site**: [https://c10insurance.netlify.app](https://c10insurance.netlify.app)

## 📄 License

This project is proprietary to C10 Insurance.

---

Built with ❤️ for Chevy C10 owners everywhere 🚛
