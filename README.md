# macOS Portfolio

A professional, interactive portfolio experience inspired by macOS—built to showcase projects, skills, and personal branding in a desktop-like interface.

[![Live Website](https://img.shields.io/badge/Live-Website-success)](https://www.sudhanshukhosla.in/)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)

## Website Preview

![Website Preview Placeholder](./public/website-preview-placeholder.jpg)

## Highlights

- macOS-style desktop with Menu Bar, Dock, Spotlight, and Launchpad
- Multi-window interactions (open, focus, minimize, maximize, close)
- Responsive behavior for desktop, tablet, and mobile screens
- Built-in portfolio apps (About, Projects, Skills, Experience, Contact, Resume)
- Additional interactive apps (Terminal, Gallery, Camera, Spotify, YouTube, Journal)
- Light and dark appearance support with smooth UI transitions

## Tech Stack

- React + TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Radix UI components

## Getting Started

### 1) Clone the repository

```bash
git clone https://github.com/Sudhanshu-khosla-26/macos-portfolio.git
cd macos-portfolio
```

### 2) Install dependencies

```bash
npm install
```

### 3) Run the project locally

```bash
npm run dev
```

## Available Scripts

- `npm run dev` — start local development server
- `npm run build` — create production build
- `npm run lint` — run ESLint checks
- `npm run preview` — preview production build locally

## Project Structure

```text
src/
├── components/
│   ├── apps/        # Portfolio app windows
│   ├── Dock.tsx
│   ├── Desktop.tsx
│   ├── MenuBar.tsx
│   └── Window.tsx
├── hooks/           # UI and system behavior hooks
├── types/           # Shared TypeScript types
└── App.tsx          # Root app composition
```

## Author

**Sudhanshu Khosla**

- GitHub: https://github.com/Sudhanshu-khosla-26
- LinkedIn: https://www.linkedin.com/in/sudhanshu-khosla-a05b4a298/
- Email: work.sudhanshukhosla@gmail.com

## License

MIT License
