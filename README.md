## Acme UI — Front-End Prompt Engineering Assignment

This repository contains my complete submission for the **Front-End Development Intern – Prompt Engineering Assignment**.

The purpose of this challenge is to demonstrate:

* Ability to design prompts that reliably produce high-quality UI components
* Skill in building responsive, accessible layouts
* Understanding of prompt engineering patterns
* Ability to combine independently generated UI sections into one polished final webpage
* Use of HTML + Tailwind CSS + minimal JavaScript (no frameworks)

Every section in this project was generated **using my own prompts** (listed below).
No manual HTML/CSS rewriting was done beyond combining and fixing interactions.

The finished webpage includes:

✔ Navigation Bar
✔ Hero Section
✔ Services / Features
✔ About Section
✔ Contact / Lead Form
✔ Footer
✔ Dark/Light Theme Toggle
✔ Mobile Navigation
✔ Form Validation + LocalStorage
✔ Toast Notifications
✔ Smooth Anchored Navigation

The complete final implementation is available in **`index.html`**.

---

## 🚀 Live Demo

**Hosted URL:**
**[https://AsthaPitambarwale.github.io/acme-ui/](https://AsthaPitambarwale.github.io/acme-ui/)**


## 🧰 Tech Stack

| Layer         | Technology                                         |
| ------------- | -------------------------------------------------- |
| Markup        | Semantic HTML5                                     |
| CSS Framework | Tailwind CSS (Play CDN)                            |
| JS            | Vanilla JavaScript                                 |
| Icons         | Custom SVG + Heroicons                             |
| Images        | Unsplash (Royalty-free)                            |
| Storage       | LocalStorage (for theme + form draft + demo leads) |


## 🧩 Features

### 🎨 **Responsive Design**

* Mobile-first layout
* Flexible navbar
* Adaptive hero grid
* Responsive cards and spacing

### 🌙 **Dark / Light Theme (Persisted)**

* Toggle stored in `localStorage`
* Uses Tailwind `dark` class mode
* SVG icons update dynamically

### 📱 **Mobile Navigation**

* Accessible hamburger menu
* ESC to close
* Auto-close after clicking a link

### 🧾 **Lead / Contact Form**

* Required fields with inline error messages
* Honeypot anti-spam field
* “Save Draft” → saves to LocalStorage
* “Submit” → saves lead locally + shows toast

### 🔔 **Toast Notifications**

* Lightweight
* Auto fades
* Used for: draft saved, validation, submit success

### 🧱 **Clean, Accessible Markup**

* ARIA labels
* Role attributes
* High contrast
* Keyboard-friendly interactions


## Folder Structure

```
acme-ui/
│
├── index.html        # Final combined webpage
├── README.md         # Documentation (you are reading it)
└── screenshots/      # (optional) UI previews for the repo
```

---

# 🧠 Prompt Engineering Deliverables

Below are **all prompts** used to generate the final webpage.
This demonstrates MY prompt design skill and reproducibility.

---

## **1️⃣ MASTER META-PROMPT**

```
You are an expert front-end developer and UI designer. Generate clean, 
accessible, production-ready HTML + TailwindCSS (using Tailwind Play CDN; no build step). 
Follow these rules:
- Use modern semantic HTML5 (header, nav, section, main, footer).
- Use Tailwind utility classes only. No external CSS except micro inline helpers.
- The result must be fully responsive (mobile-first).
- The design must be polished, visually balanced, with industry-level spacing.
- Include ARIA roles and keyboard accessibility when necessary.
- Use free Unsplash images with stable URLs and <img loading="lazy">.
- JS must be minimal, inline, and only for interactions (theme toggle, mobile menu, form validation).
- Output must be self-contained so sections can be combined without conflicts.
- No extra explanation except a short design rationale comment at the top.

```

---

## **2️⃣ SECTION PROMPTS**

### **A) Navigation Bar Prompt**

```
Generate a responsive navigation bar using Tailwind CSS:
- Brand logo + text.
- Desktop navigation links (Services, Contact, About, Demo).
- Mobile hamburger menu with open/close animation.
- Sticky top navbar with backdrop blur.
- Dark mode compatible.
- Add a dark/light theme toggle with localStorage persistence.
- Use semantic <header> and <nav>.
- Include minimal JS for toggles.
- Output clean, self-contained code only.
```

---

### **B) Hero Section Prompt**

```
Generate a hero section using Tailwind CSS:
- A bold headline, supporting text, and two CTAs.
- Right side: large Unsplash image with rounded corners.
- Add a small floating stat card over the image.
- Responsive grid: text left, image right.
- Include semantic <section> and heading levels.
```

---

### **C) Services / Features Section Prompt**

```
Generate a services section (3–6 cards):
- Each card: icon (SVG), title, description.
- Responsive grid: 1 column mobile, 2 tablet, 3 desktop.
- Rounded-2xl cards with light shadow.
- Use accessible contrast and spacing.
- Output as a standalone <section>.
```

---

### **D) About Section Prompt**

```
Generate a simple About section in TailwindCSS:
- Two-column layout on desktop (stack on mobile).
- Left: heading, text paragraph, bullet points.
- Right: small image card or illustration.
- Section must blend smoothly between Services and Contact.
- Use soft shadows, rounded corners, and brand colors.
```

---

### **E) Contact / Lead Form Prompt**

```
Generate a contact form section using TailwindCSS:
Fields required:
- name (required)
- email (required, validate pattern)
- company (optional)
- message (required)
- hidden honeypot "website" field for bots (display: none).
Functionality:
- Inline error messages.
- “Save Draft” → saves all fields to localStorage.
- On submit: validate, then save lead into localStorage array, show toast message.
- Include right-side contact info card.
- Fully responsive two-column grid.
```

---

### **F) Footer Prompt**

```
Generate a clean footer for a SaaS landing page:
- Left: Brand + short description.
- Center: Product and Company link groups.
- Right: Legal links.
- Dark background (#0f172a) with white/high-contrast text.
- Small social icons (SVG).
- Semantic <footer> only.
```

---

# 🛠 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/acme-ui.git
cd acme-ui
```

### 2. Open the project

Just open `index.html` in any browser:

* Windows: `start index.html`
* macOS: `open index.html`
* Linux: `xdg-open index.html`

No dependencies required.

---

# 🌍 Deployment

## **GitHub Pages**

1. Push repo
2. Settings → Pages
3. Source → “Deploy from branch”
4. Branch → `main`, folder → `/ (root)`
5. Save and wait 1–2 minutes

Your live link appears automatically.

---

## **Netlify (Drag & Drop)**

1. Go to [https://netlify.com](https://netlify.com)
2. New site → “Deploy manually”
3. Select `index.html`
4. Done — instant URL.

---

# 👤 Author

**ASTHA PITAMBARWALE**
Front-End Developer • UI Engineer
Email: [asthapitambarwale@gmail.com](asthapitambarwale@gmail.com)
GitHub: [https://github.com/AsthaPitambarwale](https://github.com/AsthaPitambarwale)



