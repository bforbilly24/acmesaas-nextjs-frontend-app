# Acme SaaS - Frontend Application

<img width="3024" height="1660" alt="Image" src="https://github.com/user-attachments/assets/308604ee-5b8f-47af-8d09-4e11e679efdd" />

A modern SaaS landing page template built with [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), and [Magic UI](https://magicui.design/) components. This project showcases a complete frontend solution for AI-powered SaaS applications with beautiful animations and responsive design.

## 🚀 Features

- **Modern Stack**: Built with Next.js 14, TypeScript, and Tailwind CSS
- **Magic UI Components**: Beautiful pre-built components with animations
- **Responsive Design**: Mobile-first approach with responsive layouts
- **Blog System**: Built-in blog functionality with MDX support
- **Authentication Pages**: Ready-to-use login and signup pages
- **Dark Mode**: Theme switching with next-themes
- **Performance Optimized**: SEO-friendly with optimized fonts and images

## 🛠️ Tech Stack

- **Framework**: Next.js 14 with App Router
- **Styling**: Tailwind CSS with custom animations
- **UI Components**: Radix UI primitives + Magic UI
- **Typography**: Custom Inter font optimization
- **Icons**: Lucide React icons
- **Charts**: Recharts for data visualization
- **Animation**: Framer Motion

## 📦 Getting Started

### Prerequisites

Make sure you have Node.js 18+ installed on your machine.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/bforbilly24/acmesaas-nextjs-frontend-app.git
cd acmesaas-nextjs-frontend-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `src/app/page.tsx`. The page auto-updates as you edit the file.

## 📁 Project Structure

```
acmesaas-nextjs-frontend-app/
├── 📁 src/
│   ├── 📁 app/                    # Next.js App Router
│   │   ├── (auth)/               # Authentication pages
│   │   ├── (marketing)/          # Marketing & blog pages
│   │   └── og/                   # OG image generation
│   ├── 📁 components/            # Reusable components
│   │   ├── magicui/             # Magic UI components
│   │   ├── sections/            # Page sections
│   │   └── ui/                  # Base UI components
│   ├── 📁 lib/                  # Utilities & config
│   └── 📁 assets/               # Static assets
├── 📁 content/                  # MDX blog content
├── 📁 public/                   # Public assets
├── 📄 package.json
├── 📄 tailwind.config.ts
├── 📄 next.config.mjs
└── 📄 tsconfig.json
```

## 🎨 Components

This project includes various pre-built components:

- **Hero Section**: Eye-catching landing page hero with animations
- **Features**: Horizontal and vertical feature showcases
- **Testimonials**: Customer testimonials carousel
- **Pricing**: Flexible pricing tables
- **Blog**: MDX-powered blog system
- **Authentication**: Login and signup forms
- **Charts**: Data visualization components

## 🚀 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 📝 Content Management

Blog posts are written in MDX format and stored in the `content/` directory. You can add new blog posts by creating `.mdx` files with frontmatter.

## 🎨 Customization

### Colors & Themes
- Modify `tailwind.config.ts` for custom colors and design tokens
- Theme switching is handled by `next-themes`

### Components
- Base components are in `src/components/ui/`
- Magic UI components are in `src/components/magicui/`
- Page sections are in `src/components/sections/`

## 📚 Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API
- [Tailwind CSS](https://tailwindcss.com/docs) - Utility-first CSS framework
- [Magic UI](https://magicui.design/) - Beautiful animated components
- [Radix UI](https://www.radix-ui.com/) - Unstyled, accessible components
- [MDX](https://mdxjs.com/) - Markdown for the component era

## 🚀 Deployment

### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

### Other Deployment Options

You can also deploy this application on:
- **Netlify**: Connect your Git repository for automatic deployments
- **AWS Amplify**: Full-stack deployment with hosting and backend services
- **Railway**: Simple deployment with Git integration
- **DigitalOcean App Platform**: Container-based deployment

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Halim Putra**

- GitHub: [@bforbilly24](https://github.com/bforbilly24)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/bforbilly24/acmesaas-nextjs-frontend-app/issues).

## ⭐ Show your support

Give a ⭐️ if this project helped you!
