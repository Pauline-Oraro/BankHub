# BankHub - Modern React Banking Landing Page

![BankHub preview](public/logo.svg)

BankHub is a polished, responsive banking and fintech landing page built with React, Vite, and Tailwind CSS. It showcases a modern digital banking brand through reusable components, structured content constants, responsive navigation, customer testimonials, partner logos, call-to-action sections, and an elegant dark visual theme.

**Live demo:** [https://bank-hub-beta.vercel.app](https://bank-hub-beta.vercel.app)

## Features

- Responsive navigation with a mobile menu
- Conversion-focused hero section
- Key banking statistics
- Feature and rewards highlights
- Billing, card, and payment product showcases
- Customer testimonials
- Partner/client logo section
- Call-to-action panel
- Multi-column footer with social links
- Reusable React components and centralized content
- Tailwind CSS styling and custom gradients
- Vite-powered development and production builds

## Tech Stack

| Technology | Purpose |
| --- | --- |
| React 19 | Component-based user interface |
| Vite 7 | Development server and production bundling |
| Tailwind CSS 4 | Utility-first styling |
| JavaScript (ES modules) | Application logic and configuration |
| ESLint 9 | Code quality and linting |

## Project Structure

```text
BankHub/
├── public/
│   ├── logo.svg
│   └── vite.svg
├── src/
│   ├── assets/         # Images, icons, logos, and exported assets
│   ├── components/     # Landing page sections and reusable UI components
│   ├── constants/      # Navigation, feature, testimonial, and footer content
│   ├── App.css
│   ├── App.jsx         # Main page composition
│   ├── index.css       # Global styles and Tailwind configuration
│   ├── main.jsx        # React entry point
│   └── styles.js       # Shared Tailwind utility classes
├── eslint.config.js
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Page Sections

The landing page is assembled in `src/App.jsx` and includes:

- **Navbar** — Desktop and mobile navigation
- **Hero** — Primary banking value proposition and get-started action
- **Stats** — User, transaction, and partner statistics
- **Business** — Benefits and feature highlights
- **Billing** — Billing and invoice management presentation
- **CardDeal** — Card rewards and deal information
- **Testimonials** — Customer feedback cards
- **Clients** — Partner and company logos
- **CTA** — Final conversion call to action
- **Footer** — Footer links and social channels

## Getting Started

### Prerequisites

Install:

- Node.js 18 or newer
- npm

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Pauline-Oraro/BankHub.git
cd BankHub
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open the local URL displayed in the terminal, typically:

```text
http://localhost:5173
```

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Create a production build in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint across the project |

## Customization

### Update page content

Landing-page text and repeatable data are primarily stored in:

```text
src/constants/index.js
```

This includes navigation items, features, testimonials, footer links, social links, statistics, and client information.

### Update images and icons

Add or replace assets in:

```text
src/assets/
```

Assets are exported through:

```text
src/assets/index.js
```

Then import them by name where they are needed.

### Update shared styles

Reusable layout and typography classes are defined in:

```text
src/styles.js
```

Global styles, custom animation rules, and theme styles are located in:

```text
src/index.css
```

## Production Build

Build the application:

```bash
npm run build
```

Preview the generated build:

```bash
npm run preview
```

The production bundle is written to `dist/` and can be deployed to Vercel, Netlify, GitHub Pages, or any static hosting provider.

## Deployment

The project is suitable for static deployment. To deploy on Vercel:

1. Import the GitHub repository into Vercel.
2. Set the framework preset to **Vite**.
3. Use `npm run build` as the build command.
4. Set `dist` as the output directory.

No environment variables are currently required.

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Run lint and build checks:

```bash
npm run lint
npm run build
```

5. Commit and push the branch.
6. Open a pull request.

Please keep components reusable and ensure changes remain responsive across mobile, tablet, and desktop layouts.

## Author

Created by [Pauline Oraro](https://github.com/Pauline-Oraro).
