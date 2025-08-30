# DevCraft Website v2

> A modern, professional portfolio website with landing page & sales sections built with React, TypeScript, and Tailwind CSS.

![DevCraft Website](https://img.shields.io/badge/DevCraft-Website%20v2-blue)
![React](https://img.shields.io/badge/React-18.3.1-61dafb)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.1-38bdf8)
![Vite](https://img.shields.io/badge/Vite-5.4.2-646cff)

## 🚀 Overview

DevCraft Website v2 is a comprehensive business website featuring a modern design, responsive layout, and professional portfolio showcase. Built with cutting-edge web technologies, it provides a complete solution for showcasing services, case studies, and business information.

## ✨ Features

- **🎨 Modern Design**: Clean, professional interface built with Tailwind CSS
- **📱 Fully Responsive**: Optimized for all devices and screen sizes
- **⚡ Fast Performance**: Built with Vite for lightning-fast development and builds
- **🧭 Multi-page Navigation**: Complete routing system with React Router
- **💼 Business Pages**: Services, case studies, about, and contact sections
- **🛒 E-commerce Ready**: Checkout functionality and payment integration
- **🔔 Toast Notifications**: User feedback system with toast messages
- **♿ Accessibility**: Built with accessibility best practices
- **🔍 SEO Optimized**: Meta tags and SEO-friendly structure

## 🏗️ Tech Stack

### Frontend
- **React 18.3.1** - Modern React with hooks and functional components
- **TypeScript 5.5.3** - Type-safe JavaScript development
- **React Router DOM 7.8.1** - Client-side routing and navigation
- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **Lucide React 0.344.0** - Beautiful, customizable icons

### Build & Development
- **Vite 5.4.2** - Next-generation frontend tooling
- **ESLint 9.9.1** - Code linting and quality assurance
- **PostCSS 8.4.35** - CSS processing and optimization
- **Autoprefixer 10.4.18** - Automatic CSS vendor prefixing

## 📁 Project Structure

```
devcraft-websitev2/
├── public/                 # Static assets
├── src/
│   ├── components/         # Reusable UI components
│   │   ├── About.tsx
│   │   ├── CheckoutForm.tsx
│   │   ├── Contact.tsx
│   │   ├── Footer.tsx
│   │   ├── Header.tsx
│   │   ├── Hero.tsx
│   │   ├── LoadingSpinner.tsx
│   │   ├── Modal.tsx
│   │   ├── ScrollToTop.tsx
│   │   ├── Toast.tsx
│   │   ├── WebsiteCard.tsx
│   │   └── WebsitesSection.tsx
│   ├── hooks/              # Custom React hooks
│   │   └── useToast.ts
│   ├── pages/              # Page components
│   │   ├── AboutPage.tsx
│   │   ├── CareersPage.tsx
│   │   ├── CaseStudiesPage.tsx
│   │   ├── DocumentationPage.tsx
│   │   ├── HelpCenterPage.tsx
│   │   ├── HomePage.tsx
│   │   ├── PrivacyPage.tsx
│   │   ├── RefundPolicyPage.tsx
│   │   ├── ServicesPage.tsx
│   │   ├── TermsPage.tsx
│   │   └── WebsitesPage.tsx
│   ├── App.tsx             # Main application component
│   ├── main.tsx            # Application entry point
│   ├── index.css           # Global styles
│   └── vite-env.d.ts       # Vite type definitions
├── deployment/             # Deployment guides and configs
├── package.json            # Project dependencies
├── vite.config.ts          # Vite configuration
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── README.md               # Project documentation
```

## 🛠️ Installation

### Prerequisites
- Node.js 18.0 or higher
- npm or yarn package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd devcraft-websitev2
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:5173`

## 📜 Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build production-ready application |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint for code quality checks |

## 🎨 Pages & Routes

| Route | Component | Description |
|-------|-----------|-------------|
| `/` | HomePage | Landing page with hero section |
| `/websites` | WebsitesPage | Portfolio of website projects |
| `/services` | ServicesPage | Business services overview |
| `/case-studies` | CaseStudiesPage | Detailed project case studies |
| `/about` | AboutPage | Company information and team |
| `/privacy` | PrivacyPage | Privacy policy and data handling |
| `/terms` | TermsPage | Terms of service |
| `/documentation` | DocumentationPage | Product documentation |
| `/help` | HelpCenterPage | Help center and support |
| `/careers` | CareersPage | Job opportunities |
| `/refund-policy` | RefundPolicyPage | Refund policy information |

## 🎯 Key Components

### Core Components
- **Header**: Navigation bar with responsive mobile menu
- **Footer**: Site-wide footer with links and information
- **Hero**: Eye-catching landing section with call-to-action
- **Contact**: Contact form and information display
- **About**: Company overview and team information

### Interactive Components
- **Modal**: Reusable modal dialog system
- **Toast**: Notification system for user feedback
- **LoadingSpinner**: Loading states for async operations
- **CheckoutForm**: E-commerce checkout functionality

### Content Components
- **WebsiteCard**: Portfolio item display card
- **WebsitesSection**: Gallery of website projects

### Utility Components
- **ScrollToTop**: Automatic scroll-to-top on route changes

## 🎨 Styling

The project uses **Tailwind CSS** for styling with:
- Utility-first approach for rapid development
- Responsive design classes
- Custom color scheme and branding
- Optimized for performance with purged unused styles

## 🚀 Deployment

### Quick Deploy Options
- **Vercel**: Connect your Git repository for automatic deployments
- **Netlify**: Drag & drop the `dist` folder or connect via Git
- **GitHub Pages**: Use GitHub Actions for automated deployment

### Manual Deployment
1. Build the project: `npm run build`
2. Upload the `dist` folder contents to your web server
3. Configure your server for single-page application routing

For detailed deployment instructions, see [deployment/README.md](./deployment/README.md).

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes and commit: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📝 Development Guidelines

### Code Style
- Use TypeScript for all new components
- Follow React functional component patterns
- Use Tailwind CSS for styling
- Implement proper error handling
- Write descriptive commit messages

### Component Structure
```tsx
import React from 'react';

interface ComponentProps {
  // Define prop types
}

const Component: React.FC<ComponentProps> = ({ prop }) => {
  // Component logic
  
  return (
    <div className="tailwind-classes">
      {/* JSX content */}
    </div>
  );
};

export default Component;
```

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory:
```env
VITE_API_URL=your_api_url
VITE_PAYMENT_KEY=your_payment_key
```

### Tailwind Configuration
Customize the design system in `tailwind.config.js`:
```js
module.exports = {
  content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
  theme: {
    extend: {
      // Custom configurations
    },
  },
  plugins: [],
}
```

## 📊 Performance

### Optimization Features
- **Code Splitting**: Automatic route-based code splitting
- **Tree Shaking**: Unused code elimination
- **Asset Optimization**: Image and font optimization
- **Lazy Loading**: Components loaded on demand
- **Caching**: Efficient browser caching strategies

### Performance Metrics
- Lighthouse Score: 90+ (Performance, Accessibility, SEO)
- First Contentful Paint: < 1.5s
- Largest Contentful Paint: < 2.5s
- Cumulative Layout Shift: < 0.1

## 🔐 Security

- **HTTPS Only**: Secure communication protocols
- **Content Security Policy**: XSS attack prevention
- **Input Validation**: Form data sanitization
- **Dependency Updates**: Regular security updates
- **Environment Variables**: Sensitive data protection

## 🐛 Troubleshooting

### Common Issues

**Development server not starting**
```bash
rm -rf node_modules package-lock.json
npm install
npm run dev
```

**Build fails**
```bash
npm run lint
# Fix any linting errors
npm run build
```

**Routing issues in production**
Configure your server to serve `index.html` for all routes.

## 📈 Analytics & Monitoring

The website is ready for integration with:
- Google Analytics 4
- Google Tag Manager
- Hotjar or similar heat mapping tools
- Error tracking services (Sentry, LogRocket)

## 📞 Support

For technical support and questions:
- Check the [Help Center](./src/pages/HelpCenterPage.tsx)
- Review the [Documentation](./src/pages/DocumentationPage.tsx)
- Contact the development team

## 📄 License

This project is proprietary software. All rights reserved.

---

**DevCraft Website v2** - Built with ❤️ using React, TypeScript, and Tailwind CSS.
