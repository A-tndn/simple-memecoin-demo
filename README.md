# Simple Meme Coin Demo

A customizable meme coin website template with a modern, responsive design.

## 🚀 Overview

This repository contains a single-page HTML website for a meme coin project. The site features:
- Responsive design that works on all devices
- Modern gradient color scheme
- Feature cards with hover effects
- Call-to-action buttons
- Community statistics section
- Clean, professional layout

## 📋 Customization Instructions

### 1. Branding & Text Content

Open `index.html` and modify the following sections:

**Page Title** (Line 6):
```html
<title>Your Coin Name - Your Tagline</title>
```

**Header Section** (Lines ~160-162):
```html
<h1>🚀 Your Coin Name</h1>
<p class="tagline">Your Custom Tagline Here!</p>
```

**Hero Section** (Lines ~166-168):
- Update the welcome heading
- Modify the description paragraph
- Customize the statistics (Members, Trading info, etc.)

**Feature Cards** (Lines ~187-220):
- Change the emoji icons
- Update feature titles and descriptions
- Add or remove feature cards as needed

**Call-to-Action Section** (Lines ~224-233):
- Update the heading and description
- Modify button text and links

**Footer** (Lines ~236-238):
- Update copyright information
- Customize disclaimer text

### 2. Color Scheme

Modify the colors in the `<style>` section:

**Primary Gradient** (Line 14 and throughout):
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```
Replace `#667eea` and `#764ba2` with your brand colors.

**Accent Colors**:
- `.stat-number` color (Line ~121)
- `.feature-card h3` color (Line ~74)
- `h2` colors throughout

### 3. Button Links

Update the href attributes for action buttons (Lines ~230-231):
```html
<a href="YOUR_BUY_LINK" class="cta-button">Buy Now</a>
<a href="YOUR_COMMUNITY_LINK" class="cta-button">Join Community</a>
```

Replace with:
- DEX/exchange links for "Buy Now"
- Discord, Telegram, or Twitter links for "Join Community"

### 4. Statistics

Update community stats (Lines ~174-184):
```html
<div class="stat-number">1M+</div>
<div class="stat-label">Community Members</div>
```

### 5. Add Your Logo (Optional)

To add a logo, insert before the `<h1>` tag:
```html
<img src="your-logo.png" alt="Logo" style="width: 100px; margin-bottom: 20px;">
```

### 6. Social Media Links (Optional)

Add social media icons in the footer:
```html
<div style="margin-top: 20px;">
    <a href="TWITTER_LINK" style="color: white; margin: 0 10px;">🐦 Twitter</a>
    <a href="DISCORD_LINK" style="color: white; margin: 0 10px;">💬 Discord</a>
    <a href="TELEGRAM_LINK" style="color: white; margin: 0 10px;">📱 Telegram</a>
</div>
```

## 🌐 Deployment

### Deploy to Render (Static Site)

1. Fork or clone this repository
2. Go to [Render.com](https://render.com)
3. Click "New" → "Static Site"
4. Connect your GitHub account and select this repository
5. Configure:
   - **Build Command**: Leave blank (no build needed)
   - **Publish Directory**: `./` (root directory)
6. Click "Create Static Site"
7. Your site will be live at `https://your-site-name.onrender.com`

### Deploy to Other Platforms

**GitHub Pages**:
1. Go to repository Settings → Pages
2. Select main branch as source
3. Site will be at `https://your-username.github.io/repo-name`

**Netlify**:
1. Drag and drop your repository folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect via GitHub for continuous deployment

**Vercel**:
1. Import repository at [Vercel](https://vercel.com)
2. Deploy with default settings

## 📝 License

This template is free to use and customize for your project.

## ⚠️ Important Notes

- Always comply with local regulations regarding cryptocurrency projects
- Ensure all claims and statistics are accurate
- Include appropriate risk disclaimers
- Test thoroughly on multiple devices before launching

## 🆘 Support

For issues or questions, please open an issue in this repository.

---

**Built with ❤️ for the crypto community**
