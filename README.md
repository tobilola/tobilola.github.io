# Fully Responsive Portfolio Website

## Features

### Responsive Design
- **Desktop (1024px+):** Full navigation bar, optimal reading width
- **Tablet (768px - 1024px):** Adjusted spacing, readable on iPads
- **Mobile (< 768px):** Hamburger menu, single-column layout, touch-friendly
- **Small Mobile (< 480px):** Optimized for iPhone SE and small screens

### Mobile Menu
- Hamburger icon (3 lines) on mobile devices
- Smooth slide-down animation
- Closes when clicking a link
- Closes when clicking outside menu
- Works perfectly on all phones and tablets

### Professional Features
- Smooth scroll navigation
- Fade-in animations on scroll
- Active link highlighting
- Touch-friendly buttons
- Clean, readable text on all devices

## What Works On

- **iPhone** (all models)
- **Android phones** (all sizes)
- **iPad** (all models)
- **Android tablets**
- **Laptops** (Mac, Windows, Linux)
- **Desktop computers**

## Files Included

- `index.html` - Main page with mobile menu
- `styles.css` - Fully responsive styling
- `script.js` - Mobile menu toggle and animations
- `README.md` - This file

## Testing Locally

### Open in Browser
Just double-click `index.html` and it opens in your browser.

### Test Responsive Design
1. Open the page in Chrome or Firefox
2. Press **F12** to open Developer Tools
3. Click the **phone icon** (top left of dev tools)
4. Select different devices from dropdown:
   - iPhone SE (small phone)
   - iPhone 12 Pro (medium phone)
   - iPad (tablet)
   - Desktop

### Test Mobile Menu
1. Resize browser window to mobile size (< 768px)
2. You should see hamburger menu (3 lines)
3. Click it - menu drops down
4. Click a link - menu closes automatically
5. Click hamburger again - menu closes

## Deploy to GitHub Pages

### Step 1: Create GitHub Repo

```bash
cd C:\Users\ogunb\Desktop\Projects
mkdir portfolio
cd portfolio

# Copy all files here (index.html, styles.css, script.js)

git init
git add .
git commit -m "Fully responsive portfolio with mobile menu"
```

### Step 2: Push to GitHub

Create repo at https://github.com/new
- Name: `portfolio`
- Public
- Don't initialize with anything

```bash
git remote add origin https://github.com/tobilola/portfolio.git
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo
2. Click **Settings**
3. Click **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait 1-2 minutes

Live at: `https://tobilola.github.io/portfolio`

## Test Your Live Site

### On Desktop
Just visit the URL in any browser.

### On Mobile Phone
1. Open the URL on your phone
2. Test the hamburger menu
3. Test all links
4. Scroll through all sections
5. Try landscape and portrait mode

### On Tablet
1. Open the URL on iPad/Android tablet
2. Menu should still work
3. Layout should be comfortable to read

## Update Patient Health Dashboard Link

## Responsive Breakpoints

The design adapts at these screen sizes:
- **1024px and above:** Desktop layout
- **768px - 1024px:** Tablet layout  
- **480px - 768px:** Mobile layout
- **Below 480px:** Small mobile layout

## Browser Support

Works on:
- Chrome (desktop, mobile)
- Firefox (desktop, mobile)
- Safari (desktop, iOS)
- Edge (desktop, mobile)
- Samsung Internet
- Opera

## Mobile Menu Behavior

**On Desktop (> 768px):**
- Normal horizontal menu bar
- No hamburger icon

**On Mobile/Tablet (< 768px):**
- Hamburger icon appears (3 lines)
- Menu hidden by default
- Click hamburger → menu slides down
- Click link → menu closes automatically
- Click outside → menu closes
- Smooth animations


## For Job Applications

**Portfolio URL:** https://tobilola.github.io/portfolio

**Features to mention:**
- Fully responsive (mobile, tablet, desktop)
- Mobile-first design
- Hamburger menu navigation
- Smooth scroll and animations
- Production-ready front-end

---

