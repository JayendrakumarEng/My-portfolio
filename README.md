# Jayendra Kumar — Portfolio

[![Live](https://img.shields.io/badge/Live-JayendrakumarEng.github.io-a78bfa?style=flat-square&logo=github)](https://JayendrakumarEng.github.io)
[![Stack](https://img.shields.io/badge/Stack-MERN%20%C2%B7%20AWS%20%C2%B7%20AI-22d3ee?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Open%20to%20work-34d399?style=flat-square)](#)

> Personal portfolio website — built with vanilla HTML, CSS, and JavaScript. No frameworks, no build step, zero dependencies.

---

## 🖥️ Preview

```
https://JayendrakumarEng.github.io
```

---

## ✨ Features

- **Apple-style scroll experience** — parallax hero, blur-in section reveals, scroll-driven animations
- **3D card tilt** — perspective tilt on all project and skill cards (desktop only)
- **Custom cursor** — ring + dot cursor with hover morphing (desktop only)
- **Scroll progress bar** — gradient fill at the top of the page
- **Animated counters** — numbers count up on scroll into view
- **Frosted glass nav** — backdrop-blur nav that activates on scroll
- **Magnetic buttons** — buttons pull slightly toward the cursor
- **Mobile optimised** — all GPU-heavy effects disabled on mobile, lazy image loading
- **Keyboard navigation** — press `1`–`6` to jump sections, `0` for top

---

## 📁 Structure

```
JayendrakumarEng.github.io/
├── index.html          # Entire site — single file
├── assets/
│   ├── photo0.jpg      # Hero photo (600px, ~75KB)
│   └── photo1.jpg      # About photo (400px, ~28KB)
└── README.md
```

**Important:** `assets/photo0.jpg` and `assets/photo1.jpg` must be present alongside `index.html`. The HTML references them by relative path — they are not embedded.

---

## 🚀 Deploy to GitHub Pages

```bash
# 1. Clone or init the repo
git clone https://github.com/JayendrakumarEng/JayendrakumarEng.github.io
cd JayendrakumarEng.github.io

# 2. Add your files
# Drop index.html, assets/photo0.jpg, assets/photo1.jpg here

# 3. Push
git add .
git commit -m "deploy: portfolio v1"
git push origin main
```

Then go to **Settings → Pages → Source: main branch → Save**.

Live in ~2 minutes at `https://JayendrakumarEng.github.io`.

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Frontend | React.js, Next.js, Redux, Tailwind CSS, JavaScript ES6+ |
| Backend | Node.js, Express.js, Socket.io, WebRTC, JWT Auth |
| Database | MongoDB, MySQL, Firebase |
| Cloud | AWS EC2, S3, Elastic Beanstalk, Docker |
| AI / ML | Python, TensorFlow, Scikit-learn, OpenCV |

---

## 📦 Projects Featured

| # | Project | Key Tech | Highlight |
|---|---|---|---|
| 01 | Real-Time Competitive Quiz Platform | React · Socket.io · Node · MongoDB | <100ms sync latency |
| 02 | Smart Inventory & Demand Forecasting | Python · Scikit-learn · AWS | ~30% stockout reduction |
| 03 | LiveGuard — Biometric Identity Engine | TensorFlow · OpenCV · FastAPI | 94%+ accuracy |
| 04 | Live Education & Classroom Portal | WebRTC · Node · MongoDB | Multi-party video, RBAC |
| 05 | Secure Smart Contact Directory | MERN · JWT · Bcrypt | O(1) lookup via indexing |

---

## ⚡ Performance

| Metric | Value |
|---|---|
| HTML size | ~70KB |
| Hero image | 75KB (eager load) |
| About image | 28KB (lazy load) |
| `backdrop-filter` | Nav only (2 elements) |
| Scroll handlers | 1 RAF-throttled function |
| Mobile | Tilt, parallax, cursor all disabled |

---

## 🔧 Customisation

**Update project links** — replace the GitHub links in each `.proj-card` with your actual repo URLs:

```html
<!-- Find this in each project card -->
<a class="proj-link" href="https://github.com/JayendrakumarEng" target="_blank">

<!-- Replace with your actual repo -->
<a class="proj-link" href="https://github.com/JayendrakumarEng/your-repo-name" target="_blank">
```

**Add resume download** — find the resume button and add your PDF link:

```html
<a class="resume-btn" href="YOUR_RESUME_PDF_URL_HERE">
```

**Add live demo links** — when you deploy projects to Vercel:

```html
<!-- Add after the Source link in each project card -->
<a class="proj-link" href="https://your-project.vercel.app" target="_blank">
  <svg>...</svg> Live Demo
</a>
```

---

## 📬 Contact

- **Email:** jk.sharma9777@gmail.com
- **LinkedIn:** [linkedin.com/in/jayendra-kr](https://linkedin.com/in/jayendra-kr)
- **GitHub:** [github.com/JayendrakumarEng](https://github.com/JayendrakumarEng)
- **WhatsApp:** +91 6206197773

---

## 📄 License

This portfolio is personal work. Feel free to use it as inspiration — but please don't copy it directly and claim it as your own.

---

*Designed & built by Jayendra Kumar · Kolkata, India*
