# Astro Portfolio Boilerplate

A clean, modern portfolio website starter built with [Astro](https://astro.build/).

This boilerplate is designed for designers, developers, and creatives who want a beautiful, customizable, and easy-to-update portfolio without extra dependencies.

---

## 🚀 Features

- Astro-only: No frameworks or build tools beyond Astro itself. Just pure `.astro`, CSS, and JS.
- Modern layout: Responsive design with a minimalist navbar, centered logo, and clear section structure.
- Portfolio, About, Contact pages: Ready to showcase your projects, tell your story, and let people reach out.
- Customizable theme picker: Instantly switch between Light, Dark, and Hot (red) themes. Remembers your choice.
- Persistent theme: User theme is saved via `localStorage`.
- Full CSS variables: Easy theming and style changes.
- Accessible and semantic HTML: Built with accessibility in mind.
- Ready for Netlify or Vercel: Easy to deploy, zero config needed.

---

## ✏️ How to Use & Customize

### 1. Installation

npm create astro@latest  
# or clone this repo  
git clone https://github.com/drubino8/astro-web-boilerplate.git  
cd astro-portfolio-boilerplate  
npm install

### 2. Development

npm run dev

Visit http://localhost:4321 to see your site.

### 3. Updating Your Content

- **Logo:** Edit in `src/layouts/MainLayout.astro` (`<a href="/" class="logo">MyLogo</a>`)
- **Navbar:** Links are in `MainLayout.astro`. You can rename or add more as needed.
- **Portfolio items:** Edit your projects in `src/pages/index.astro`
- **About page:** Update your bio, skills, and profile photo in `src/pages/about.astro`
- **Contact info:** Update your email, phone, location, and social links in `src/pages/contact.astro`
- **Theme colors:** Edit theme variables at the top of `src/styles/global.css` for your own palette or add more themes.
- **Deploy:** Push to GitHub and connect to Netlify or Vercel.

### 4. Theme Picker

- Switch themes with the dropdown in the top right.
- To add more themes, extend the `:root[data-theme="your-theme"]` CSS block in `global.css` and add an `<option>` in the picker.

---

## ☕️ Support

If you enjoy this template or want to support future updates:

[![Buy Me a Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/drubino8)

---

**Made with Astro • Designed for creators**