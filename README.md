# Teeth Care Clinic Website 🦷

[![Vite](https://img.shields.io/badge/Vite-5.0+-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Design_System-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-teal.svg?style=flat-square)](LICENSE)

A modern, responsive, and feature-rich web platform designed and engineered for **Teeth Care**. Built with high performance and accessibility in mind, the website combines a soothing clinical aesthetic (*"Soft Teal & Clinical White"*) with patient trust, dynamic tools, client-side SPA routing, and appointment scheduling.

---

## 🚀 Live Demo & Overview

- **Brand Name**: Teeth Care
- **Website URL**: [https://www.teethcare.com](https://www.teethcare.com)
- **Patient Intake Portal**: [https://portal.teethcare.com/intake](https://portal.teethcare.com/intake)

---

## 🎨 Design Philosophy & Branding

The design embraces a clean, anxiety-reducing visual language:
- **Color Palette**: Clinical White, Soft Teal (`#0d9488` / `hsl(173, 80%, 40%)`), Sky Blue, and Slate Gray.
- **Typography**: Plus Jakarta Sans for crisp legibility and approachable medical professionalism.
- **Accessibility & UX**: High contrast, subtle elevation shadows, smooth micro-interactions, dark/light theme switching, and fluid responsive layouts across mobile, tablet, and desktop viewports.

---

## ✨ Key Features & Interactive Modules

### 1. 🧭 Navigation & Header
- **Sticky Glassmorphism Navbar**: Retains position with blur and elevation shadow upon page scrolling.
- **Mobile Drawer Navigation**: Slide-out mobile menu with animated hamburger icon toggle.
- **Multi-Language Switcher (EN / ES)**: Instant in-place translation between English and Spanish powered by data attribute dictionaries (`data-i18n`).
- **Dark / Light Mode Toggle**: System that persists the patient's theme choice via `localStorage`.

### 2. 🌟 Split Hero & Trust Architecture
- High-converting split hero layout featuring trust indicators and patient avatar stacks (+2,000 satisfied patients, 5.0-star rating).
- Animated pulsing status dot highlighting *"Accepting New Patients"*.
- Instant action triggers: *"Book Your Visit"* (opens booking modal) and *"View Procedures"* (anchors to services).

### 3. 🕒 Dynamic Floating Info Cards & Real-Time Status
- **Real-Time Clinic Status**: Dynamically calculates whether the clinic is currently **"Open Now"** (green) or **"Closed"** (red) according to live local business hours (Mon–Fri: 8am–6pm, Sat: 9am–2pm, Sun: Closed).
- **Visit Clinic Card**: Clinic address with direct route to Google Maps directions.
- **Emergency & Helpline Card**: Displays both the primary office desk and the dedicated alternative 24/7 emergency telephone line.

### 4. 🧮 Interactive Out-of-Pocket Treatment Cost Calculator
- Select multiple procedures: Routine Cleaning & Exam, Laser Teeth Whitening, White Composite Fillings, Porcelain Crowns, Dental Implants, and Clear Invisalign Aligners.
- Choose insurance provider: Self-Pay / No Insurance, Delta Dental (PPO), Cigna Dental (PPO), MetLife Dental, or Aetna Dental.
- Calculates subtotal, estimated insurance coverage deduction, and out-of-pocket balance in real time.
- Displays a CareCredit 12-month interest-free installment financing estimate (`$ / mo`).

### 5. 🪞 Before & After Smile Gallery & Case Study Lightbox
- **Interactive Dual-Image Comparison Slider**: Smooth slider supporting mouse dragging and touch gestures to inspect cosmetic whitening results before and after treatment.
- **Case Study Lightbox Modal**: View clinical before-and-after cases (Porcelain Veneers, Composite Dental Bonding, Porcelain Crowns) with dentist notes, clinical tags, and treatment schedules.

### 6. ⚡ SPA Client-Side Hash Router (Dynamic Detail Pages)
- **Procedure Detail Pages** (`#services/:id`):
  - `#services/whitening` — Cosmetic Teeth Whitening
  - `#services/implants` — Permanent Dental Implants
  - `#services/exams` — Preventive Exams & Ultrasonic Scaling
  - `#services/pediatric` — Gentle Pediatric Dental Care
  - Each detail view loads step-by-step treatment journeys, average costs, appointment durations, recovery timelines, and insurance statuses without page reload.
- **Educational Dental Blog Articles** (`#blog/:id`):
  - `#blog/brushing` — The Right Way to Brush (Modified Bass Method)
  - `#blog/diet` — Top 5 Foods for Naturally Stronger Enamel
  - `#blog/floss` — Flossing vs. Waterpicks: Which is better?

### 7. 🔍 Searchable & Filterable FAQ Accordion
- Real-time search bar that filters questions and answers as the user types.
- Category filter buttons: *All Questions*, *Insurance & Billing*, *Dental Anxiety*, and *General Info*.
- Accordion mechanism with chevron transitions and single-open state management.

### 8. ⭐ Verified Google Reviews Testimonials Slider
- Responsive multi-card review carousel with previous/next controls and touch support.
- Showcases verified 5-star patient reviews from Google Maps.

### 9. 📅 Appointment Booking Modal & Validation
- Fully accessible dialog overlay with keyboard dismiss (Escape key) and outside-click support.
- Client-side validation:
  - Full Name validation.
  - Email format validation (standard regex).
  - Phone validation with **automatic phone formatting** (`(555) 000-0000`).
- Integrated with Web3Forms API support (with safe mock fallback and loading spinner).
- **HIPAA Compliance Notice** with direct link to the encrypted patient intake portal.

### 10. 📋 Clinic Price Schedule Modal
- Tabbed price schedule covering *Preventive*, *Cosmetic*, *Restorative*, and *Orthodontic* procedures with average pricing and insurance coverage tags.

### 11. 📱 Mobile Sticky Quick-Action Bar
- Bottom sticky conversion bar triggered after 500px scroll on mobile devices, providing one-tap phone calling and appointment booking.

### 12. 🔍 SEO & Schema.org Structured Data
- Complete Schema.org `Dentist` JSON-LD markup.
- Primary and alternative contact points (`customer service` and `emergency`).
- Geolocation coordinates, opening hours specification, and canonical OpenGraph / Twitter meta cards.

---

## 📞 Contact Information & Alternative Details

| Channel | Primary Detail | Alternative Detail |
| :--- | :--- | :--- |
| **Phone** | `(555) 382-7200` *(Main Clinic Desk)* | `(555) 948-2273` *(Alt / 24/7 Emergency Line)* |
| **Email** | `hello@teethcare.com` *(Inquiries & General)* | `appointments@teethcare.com` *(Bookings & Support)* |
| **Address** | 789 Smile Boulevard, Suite 300, Healthcare District, San Francisco, CA 94103 | *Google Maps directions linked in footer and info cards* |
| **Intake Portal**| [https://portal.teethcare.com/intake](https://portal.teethcare.com/intake) | *Encrypted HIPAA Patient Intake Form* |
| **Hours** | Mon - Fri: 8:00 AM – 6:00 PM<br>Sat: 9:00 AM – 2:00 PM | Sun: Closed *(On-call emergency triage via 24/7 line)* |

---

## 💻 Tech Stack

- **Markup**: HTML5 (Semantic tags, Schema.org JSON-LD microdata, Open Graph)
- **Styling**: Modern CSS3 (CSS Custom Properties / Design Tokens, Flexbox, CSS Grid, media queries)
- **Scripts**: Vanilla JavaScript (ES6+ Modules, client-side hash router, regex phone mask, reactive opening hours)
- **Icons & Fonts**: [Font Awesome 6.4](https://fontawesome.com/) & [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)
- **Bundler & Dev Server**: [Vite 5.x](https://vitejs.dev/)

---

## 📂 Project Structure

```text
Teeth-Care/
├── dist/                          # Production distribution build (generated by Vite)
│   ├── assets/
│   │   ├── index-[hash].css       # Minified, optimized styles
│   │   └── index-[hash].js        # Bundled, tree-shaken JavaScript
│   └── index.html                 # Optimized production HTML entry
├── node_modules/                  # Installed dependencies
├── index.css                      # Design system, CSS variables, and layout styles
├── index.html                     # Source HTML document and templates
├── main.js                        # Core application script, router, and data stores
├── package.json                   # Project configuration, scripts, and dependencies
├── package-lock.json              # Exact package version lockfile
├── README.md                      # Comprehensive project documentation
└── vite.config.js                 # Vite server and build settings
```

---

## 🛠️ Installation & Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (version 18 or higher recommended)
- `npm` (bundled with Node.js)

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/teeth-care.git
cd teeth-care
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:3000` (or the port specified in `vite.config.js`).

### 4. Build for production
```bash
npm run build
```
This bundles and optimizes all assets into the `dist/` directory.

### 5. Preview production build locally
```bash
npm run preview
```

---

## ⚙️ Configuration & Customization

- **Web3Forms Key**: In `index.html`, locate the booking form input `<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">`. Replace with your free key from [Web3Forms](https://web3forms.com/) to receive live emails.
- **Port Settings**: Modify `vite.config.js` to change the local dev server port.

---

## 🤝 Contributing

1. Fork the repository
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and distributed under the **MIT License**. See the `LICENSE` file for more details.

Designed & Developed for **Teeth Care Clinic**.
