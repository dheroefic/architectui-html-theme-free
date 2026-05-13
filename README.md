# ArchitectUI Bootstrap 5 jQuery/HTML Theme FREE
## Made with love by DashboardPack.com

[![npm version](https://img.shields.io/badge/version-4.6.0-blue.svg)](https://github.com/DashboardPack/architectui-html-theme-free)
[![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)](package.json)
[![Security](https://img.shields.io/badge/security-0%20vulnerabilities-brightgreen.svg)](package.json)
[![SASS](https://img.shields.io/badge/SASS-modernized-purple.svg)](src/assets/)

ArchitectUI is a **Modern Clean Responsive HTML Bootstrap 5 Admin UI Dashboard Template**. It is used by thousands of developers to build SaaS and various other admin panels for web apps. This version hosted on Github is for preview only. It has a limited functionality in comparison to [Pro version](https://dashboardpack.com/theme-details/architectui-dashboard-html-pro/?utm_source=github&utm_medium=readme&utm_campaign=architectui-html-upgrade&utm_content=intro-link) yet it comes with unlimited color schemes and flexibility unmatched to most other Premium admin dashboards.

## What's New in v4.6.0

### **📦 Full Dependency Refresh (May 2026)**
- **Every package on latest** - Both runtime and build toolchain updated to the most recent versions on npm
- **Major bumps** - `copy-webpack-plugin` 14, `css-minimizer-webpack-plugin` 8, `eslint` 10, `eslint-webpack-plugin` 6, `webpack-cli` 7
- **Webpack 5.106** - Latest core bundler with newest perf improvements
- **Sass 1.99** - Latest compiler
- **Zero vulnerabilities** - Clean `npm audit` after full refresh
- **Verified build** - All 26 demo pages emit cleanly with the upgraded toolchain

### **Previous Release: v4.5.0**
- **jQuery 4.0.0** - First major jQuery release in over a decade
- **MetisMenu 3.1.0** - Updated sidebar menu library with jQuery 4.0 support
- **All Dependencies Updated** - January 2026 refresh across the stack

See [CHANGELOG.md](Changelog.md) for complete details.

## Earlier Release: v4.2.0

### 🚀 **Complete Modernization**
- **Latest Dependencies** - All npm packages updated to current versions
- **Future-Proof SASS** - Modern `@use` syntax, zero deprecation warnings
- **Enhanced Security** - Zero vulnerabilities detected
- **Modern Tooling** - ESLint v9, Webpack 5.99, latest build tools

### 🗺️ **Maps Component** (Updated in v4.4.0)
- **Real Google Maps** - Fully interactive maps with actual map data
- **Free to Use** - No API key required, uses Google's iframe embed system
- **5 Global Locations** - Tokyo, New York, London, Paris, San Francisco
- **Professional Quality** - All standard Google Maps features included

### 📦 **Performance Improvements**
- **Reduced Bundle Size** - 50KB improvement (1.87 MiB → 1.82 MiB)
- **Faster Builds** - Optimized webpack configuration
- **Clean Console** - No 404 errors or warnings during development
- **Better Caching** - Improved asset loading and browser caching

### 🔧 **Developer Experience**
- **Modern SASS** - Using latest `@use` modules instead of deprecated `@import`
- **ESLint v9** - Latest linting with flat configuration format
- **Clean Development** - Professional console output without noise
- **Security First** - All dependencies audited and updated

## PRO Version Available [here](https://dashboardpack.com/theme-details/architectui-dashboard-html-pro/?utm_source=github&utm_medium=readme&utm_campaign=architectui-html-upgrade&utm_content=pro-banner) 🏆

## Preview

![ArchitectUI Bootstrap 5 Free](https://colorlib.com/wp/wp-content/uploads/sites/2/architectui-html-free.jpg)

## 🚀 Quick Start

### Installation
Download and Uncompress the theme package archive in your desired folder location.

Download and install Node.js LTS from https://nodejs.org/en/download/

Install the app dependencies by running the following command in the command line inside the folder root where you have unzipped the theme package archive.

```bash
npm install
```

After npm finishes installing the modules from package.json you can go ahead and start the application. To do so, run the command below.

```bash
npm run start
```

After the command finished, you should see a **Compiled successfully!** message in your terminal window. Also, a web server service will be started so you can view your app in the browser: **http://localhost:8080**

### Production Build
To create a production optimized build run the command below:

```bash
npm run build
```

This created another folder in the root of your project named build. You'll have an option to start a local web server to view your newly created production build.

## 🎯 **Key Features**

### **Modern Technology Stack**
- **Bootstrap 5.3.8** - Latest version with all features
- **jQuery 4.0.0** - Major modernization release
- **Chart.js 4.5.1** - Beautiful data visualizations
- **FontAwesome 7.2.0** - Latest icon library version
- **SASS 1.99.0** - Modern CSS preprocessing
- **Webpack 5.106.2** - Latest build tooling

### **Components & Features**
- ✅ **Responsive Design** - Mobile-first approach
- ✅ **Real Google Maps** - 5 interactive locations, no API keys required
- ✅ **Chart Integration** - Beautiful data visualization with Chart.js
- ✅ **Calendar Component** - Full-featured event management
- ✅ **Form Elements** - Complete form components library
- ✅ **Navigation Systems** - Multiple menu styles
- ✅ **Card Components** - Flexible content containers
- ✅ **Button Variants** - Extensive button library
- ✅ **Icon Libraries** - FontAwesome 7, PE7, Linearicons
- ✅ **Animation Support** - Smooth transitions and effects

### **Developer Benefits**
- 🔒 **Security Focused** - Zero vulnerabilities
- 🚀 **Performance Optimized** - Fast loading times
- 🛠️ **Easy Customization** - Well-structured SASS files
- 📱 **Mobile Ready** - Responsive across all devices
- 🎨 **Theme Flexibility** - Multiple color schemes
- 🔧 **Modern Tooling** - Latest development tools

## 📁 **Project Structure**
```
architectui-html-theme-free/
├── src/
│   ├── assets/           # SASS, images, fonts
│   ├── DemoPages/        # HTML templates
│   ├── layout/           # Layout components
│   └── scripts-init/     # JavaScript modules
├── build/                # Production build output
├── package.json          # Dependencies and scripts
└── webpack.config.js     # Build configuration
```

## 🔄 **Upgrade from v4.1.0**
This version includes breaking improvements. For existing projects:

1. **Backup your customizations**
2. **Update dependencies**: `npm install`
3. **Review SASS changes** if you've customized themes
4. **Test your maps** - new implementation may require updates

## **Version History**
- **v4.6.0** (2026-05-13) - Full dependency refresh, latest webpack/eslint/sass toolchain
- **v4.5.0** (2026-01-29) - jQuery 4.0 upgrade, all dependencies updated
- **v4.4.0** (2025-11-17) - Real Google Maps integration, improved UX
- **v4.3.0** (2025-09-17) - FontAwesome 7 upgrade, complete dependency refresh
- **v4.2.0** (2025-06-20) - Complete modernization, SASS future-proofing
- **v4.0.0** (2023-10-17) - React v18 migration, dependency upgrades
- **v3.1.0** (2022-08-22) - Library updates
- **v3.0.0** (2022-04-05) - WebPack v5 migration
- **v2.0.0** (2021-09-07) - Bootstrap v5 migration

## 🤝 **Contributing**
We welcome contributions! Please feel free to submit issues and pull requests.

## 📄 **License**
Licensed under MIT. See [LICENSE](LICENSE) for details.

## 🔗 **Links**
- **Website**: [DashboardPack.com](https://dashboardpack.com)
- **Pro Version**: [ArchitectUI Pro](https://dashboardpack.com/theme-details/architectui-dashboard-html-pro/?utm_source=github&utm_medium=readme&utm_campaign=architectui-html-upgrade&utm_content=footer-link)
- **Documentation**: Available with Pro version
- **Support**: [Contact Support](https://dashboardpack.com/contact)

