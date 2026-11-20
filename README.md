# 🍽️ Restaurant Website

<p align="center">
  <strong>A modern, responsive restaurant website built with React and Vite.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License" />
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-project-structure">Project Structure</a>
</p>

---

## ✨ Overview

**Restaurant Website** is a polished, single-page restaurant experience with an inviting hero section, featured dishes, restaurant highlights, booking guidance, testimonials, operating hours, FAQs, and calls to action.

The interface uses smooth scrolling and motion effects to create an engaging dining brand experience across desktop, tablet, and mobile devices.

## 🚀 Features

- 🏠 **Hero Landing Section** — Strong visual introduction with a clear call to action.
- 📖 **About the Restaurant** — Showcase the restaurant's story and personality.
- 📊 **Business Highlights** — Present key statistics and achievements.
- 🍕 **Featured Dishes** — Display popular menu items and culinary offerings.
- 🌟 **Feature Highlights** — Explain the restaurant's strengths and services.
- 📅 **Booking Process** — Guide visitors through reservation steps.
- 🕐 **Opening Hours** — Share available timings clearly.
- 💬 **Testimonials** — Feature customer reviews and positive feedback.
- ❓ **FAQ Section** — Answer common guest questions.
- 📢 **Conversion CTA** — Encourage visitors to book or explore further.
- 🧭 **Responsive Navigation** — Easy navigation across the entire page.
- 🦶 **Detailed Footer** — Provide useful links and contact information.
- 🌊 **Smooth Scrolling** — Enhanced scrolling powered by Lenis.
- 🎞️ **Motion Effects** — Interactive animations with Motion.

## 🖼️ Screenshots

> Add screenshots of the running website here to give visitors a quick visual preview.

```text
public/
└── assets/
```

Place project screenshots in `public/assets` and update the following section with image links:

```markdown
<p align="center">
  <img src="public/assets/preview.png" alt="Restaurant Website Preview" />
</p>
```

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React 19** | Component-based user interface |
| **Vite** | Fast development server and production builds |
| **Tailwind CSS 4** | Utility-first styling |
| **Motion** | UI animations and transitions |
| **Lenis** | Smooth scrolling experience |
| **Lucide React** | Modern icon library |
| **Oxlint** | JavaScript and JSX linting |

## ✅ Requirements

- **Node.js** 18 or newer
- **npm** 9 or newer

## ⚡ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/SahilMujawar-19265/Restaurant-website.git
cd Restaurant-website
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

Open the local URL displayed by Vite in your browser.

## 📦 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the Vite development server |
| `npm run build` | Create an optimized production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run Oxlint checks |

## 📁 Project Structure

```text
Restaurant-website/
├── public/
│   └── assets/          # Publicly accessible static assets
├── src/
│   ├── assets/          # Imported images and media
│   ├── components/      # Reusable UI components
│   ├── data/            # Shared content and data
│   ├── sections/        # Page sections
│   ├── App.jsx          # Main application composition
│   ├── index.css        # Global styles
│   └── main.jsx         # React entry point
├── index.html
├── package.json
└── vite.config.js
```

## 🧩 Main Page Sections

| Section | Responsibility |
|---|---|
| `Navbar` | Navigation and branding |
| `HeroSection` | Primary introduction |
| `About` | Restaurant story |
| `Stats` | Key numbers and achievements |
| `Dishes` | Featured menu items |
| `Features` | Service highlights |
| `BookingProcess` | Reservation guidance |
| `Timing` | Opening hours |
| `TestimonialSection` | Guest reviews |
| `FAQs` | Common questions |
| `CTA` | Final call to action |
| `Footer` | Footer links and details |

## 🌐 Deployment

### Build for production

```bash
npm run build
```

The optimized output is generated in the `dist` directory. This folder can be deployed to platforms such as:

- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add your feature"
   ```

4. Push the branch and open a pull request.

## 👤 Author

**Sahil Mujawar**

- GitHub: [@SahilMujawar-19265](https://github.com/SahilMujawar-19265)

## 📄 License

This project is currently without an explicit license. Add a `LICENSE` file before applying an open-source license.

---

<p align="center">Made with ❤️ for restaurant lovers</p>
