# Saad's Portfolio

A modern, interactive portfolio website built with Next.js 14, showcasing my projects, skills, and experience as a full-stack developer.

## Features

- **Modern UI/UX**: Built with cutting-edge design using Tailwind CSS and Framer Motion animations
- **3D Interactions**: Interactive 3D globe and visual effects using Three.js and React Three Fiber
- **Bento Grid Layout**: Sleek component-based design with hover effects and smooth transitions
- **Project Showcase**: Pin-style project cards with live site links
- **Tech Stack Display**: Animated tech stack visualization
- **Testimonials Section**: Client feedback and recommendations
- **Contact Integration**: Easy-to-use contact form with email copy functionality
- **Lottie Animations**: Delightful micro-interactions using Lottie animations
- **Responsive Design**: Fully responsive across all devices

## Tech Stack

### Frontend
- **Next.js 14** - React framework with App Router
- **React 18** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first styling
- **Framer Motion** - Animation library
- **Three.js / React Three Fiber** - 3D graphics
- **Lottie React** - Animation rendering

### Tools & Libraries
- **Aceternity UI** - Custom UI components
- **React Icons** - Icon library
- **Sentry** - Error tracking and monitoring
- **Clsx** - Conditional class names

## Getting Started

### Prerequisites
- Node.js 18+ and npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SaadOuayallal/portfolio.git
cd saad-portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
saad-portfolio/
├── app/                    # Next.js app directory
├── components/             # React components
│   ├── ui/                 # Reusable UI components
│   ├── Grid.tsx            # Bento grid section
│   ├── Hero.tsx            # Hero section
│   ├── RecentProjects.tsx  # Projects showcase
│   └── ...
├── data/                   # Static data and content
├── public/                 # Static assets
└── styles/                 # Global styles
```

## Key Components

- **BentoGrid**: Responsive grid layout with animated cards
- **PinContainer**: 3D perspective project cards with hover effects
- **GridGlobe**: Interactive 3D globe visualization
- **TextGenerateEffect**: Animated text reveal effect
- **MagicButton**: Custom button with gradient effects

## Customization

### Update Personal Information
Edit the data in `/data/index.ts` to customize:
- Projects
- Tech stack
- Work experience
- Testimonials
- Social media links

### Modify Styling
Tailwind configuration can be adjusted in `tailwind.config.ts`

### Add New Sections
Create new components in `/components` and import them into your pages

## Performance

- **Lazy Loading**: Dynamic imports for heavy components
- **Image Optimization**: Next.js Image component
- **Code Splitting**: Automatic route-based splitting
- **SSR/SSG**: Server-side rendering for optimal performance

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- Email: saad.ouayallal@gmail.com
- LinkedIn: [Saad Ouayallal](https://www.linkedin.com/in/saad-ouayallal/)
- GitHub: [SaadOuayallal](https://github.com/SaadOuayallal)

---

Built with love using Next.js and modern web technologies
