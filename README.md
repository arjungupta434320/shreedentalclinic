# Shree Dental Care - Luxury Dental Studio Website

> **"Precision Dentistry. Elevated Comfort. Timeless Smiles."**

A complete, production-ready, ultra-modern luxury dental clinic website built with **HTML5**, **Tailwind CSS**, and **Vanilla JavaScript** (with **GSAP** & **ScrollTrigger** for smooth micro-interactions). Fully responsive, mobile-first, and designed to deliver effortless patient bookings.

---

## 🌟 Key Features

* **White & Modern Mixel Luxury Palette:** Crisp alabaster white (`#FFFFFF`) and soft pearl (`#F8FAFC`) canvas accented with medical teal (`#0D9488`), sky blue (`#0284C7`), and champagne gold (`#D4AF37`) badges.
* **Editorial Typography:** Editorial serif headings powered by **Playfair Display** & **Cormorant Garamond**, paired with the modern sans-serif **Plus Jakarta Sans** for UI legibility.
* **Interactive Clinic Showcase:** Bento-grid masonry gallery featuring high-resolution operatory visuals with hover zooms and interactive full-screen lightboxes.
* **Google Reviews Showcase (Infinite Marquee):** Pure text-based verified Google reviews extracted from authentic patient feedback with avatar initials, 5-star ratings, treatment tags, and continuous smooth luxury marquee animation with hover-pause (zero screenshot images in the reviews section).
* **Signature Treatments Bento:** 6 specialization cards with instant *"Book Consultation"* triggers that pre-select the treatment in the reservation form.
* **Concierge Booking Form:**
  * Real-time 10-digit mobile number validation (`:user-invalid` feedback).
  * Treatment pills & Morning/Afternoon/Evening slot toggles.
  * Native date selector with automated next-day minimum date constraint.
  * Automated confirmation modal with celebratory confetti.
  * Direct **Instant WhatsApp Booking** compiling all form fields straight to `+91 81261 26513`.
* **Mobile-First Ergonomics:**
  * Auto-collapsing sticky navbar with a full-featured glassmorphic slide-over drawer.
  * Fixed mobile bottom action bar (`Call: 81261 26513` + `Book Online`) with iOS safe-area support.
  * Floating WhatsApp assistance widget.
  * Zero horizontal overflow (`max-width: 100vw; overflow-x: hidden`).

---

## 📁 Repository Structure

```text
├── index.html                           # Self-contained master webpage
├── .gitignore                           # Git ignore definitions
├── README.md                            # Documentation
├── shree dental care 1.webp             # Primary surgical operatory suite
├── shree dental care 2.webp             # Executive consultation cabin
├── shree dental care 3.webp             # Digital imaging & diagnostic bay
├── shree dental care 4.webp             # Implantology & microsurgical theater
├── Screenshot 2026-11-10 011310.png     # Asset
├── Screenshot 2026-11-10 011330.png     # Asset
├── Screenshot 2026-11-10 011340.png     # Asset
├── Screenshot 2026-11-10 011350.png     # Asset
└── Screenshot 2026-11-10 011358.png     # Asset
```

---

## 🚀 Quick Start

Simply open `index.html` in any modern web browser, or serve locally:

### Option 1: Python
```bash
python -m http.server 3000
```
Then visit `http://localhost:3000`.

### Option 2: Node.js (npx)
```bash
npx serve .
```

---

## ⚡ Deployment to Cloudflare Pages (via Git)

Because this is a modern static HTML5 + Tailwind CSS site, hosting on **Cloudflare Pages** is instantaneous, completely free, and gives you a worldwide CDN with automated SSL:

1. **Log into Cloudflare:**
   - Go to [dash.cloudflare.com](https://dash.cloudflare.com) and log in.
2. **Go to Workers & Pages:**
   - In the left sidebar, click **Compute (Workers & Pages)** > **Create application**.
   - Select the **Pages** tab and click **Connect to Git**.
3. **Connect Your GitHub Repository:**
   - Link your GitHub account and select `arjungupta434320/shreedentalclinic`.
4. **Configure Settings:**
   - **Project Name:** `shreedentalclinic` (or any custom name)
   - **Production Branch:** `main`
   - **Framework Preset:** `None`
   - **Build Command:** *(Leave blank)*
   - **Build Output Directory:** `/` *(or leave blank)*
5. **Deploy:**
   - Click **Save and Deploy**.
   - Your site will be live in under 20 seconds at a free `https://shreedentalclinic.pages.dev` URL with automatic deployments on every `git push`.

---

## 📞 Clinic Details

* **Clinic Name:** Shree Dental Care
* **Primary Phone / WhatsApp:** [+91 81261 26513](tel:8126126513)
* **WhatsApp Booking:** [Chat with Clinic](https://wa.me/918126126513)
* **Address:** Galira Road, Gali Number 3, near Ravinder molu ki kothi, Wills Colony, Saharanpur, Uttar Pradesh 247001
* **Hours:** Monday – Saturday: 9:30 AM – 8:30 PM | Sunday: 10:00 AM – 2:00 PM (Emergency)

---

© 2026 Shree Dental Care. All rights reserved.
