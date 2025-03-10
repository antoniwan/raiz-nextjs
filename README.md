# Raiz NextJS Application

A modern, performant web application built with Next.js 15, React 19, and TailwindCSS. This project uses the latest features of Next.js including the App Router, Server Components, and TurboPack for enhanced development experience.

## 🚀 Features

- **Modern Tech Stack**: Built with Next.js 15, React 19, and TypeScript
- **Optimized Performance**: Utilizes TurboPack for faster development builds
- **Responsive Design**: Mobile-first approach using TailwindCSS
- **Type Safety**: Full TypeScript support for enhanced development experience
- **Modern Styling**: Tailwind CSS for utility-first styling
- **Optimized Fonts**: Uses Geist font family through `next/font` for optimal loading
- **ESLint Configuration**: Strict linting rules for code quality

## 🛠️ Prerequisites

- Node.js 18.x or later
- npm, yarn, pnpm, or bun package manager

## 📦 Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd raiz-nextjs
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

## 🚀 Development

Start the development server with TurboPack enabled:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

The application will be available at [http://localhost:3000](http://localhost:3000).

## 🏗️ Build

Create a production build:

```bash
npm run build
# or
yarn build
# or
pnpm build
# or
bun build
```

## 🧪 Linting

Run the linter:

```bash
npm run lint
# or
yarn lint
# or
pnpm lint
# or
bun lint
```

## 📁 Project Structure

```
raiz-nextjs/
├── app/                    # App router directory
│   ├── page.tsx           # Main page component
│   ├── layout.tsx         # Root layout
│   └── globals.css        # Global styles
├── public/                # Static assets
├── next.config.ts         # Next.js configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── postcss.config.mjs     # PostCSS configuration
└── tsconfig.json         # TypeScript configuration
```

## 🔧 Configuration

- **Next.js**: Configuration in `next.config.ts`
- **TypeScript**: Configuration in `tsconfig.json`
- **TailwindCSS**: Configuration in `tailwind.config.js`
- **ESLint**: Configuration in `eslint.config.mjs`

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)

## 🚀 Deployment

The application is optimized for deployment on [Vercel](https://vercel.com). Simply connect your repository to Vercel for automatic deployments.

For other platforms, build the application using:
```bash
npm run build
npm run start
```

## 📄 License

This project is licensed under the MIT License.
