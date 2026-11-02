# KS Software Company — Website Documentation

**Live URL:** [kssoftware.co.in](https://kssoftware.co.in)  
**Version:** 2.0 (Enhanced with Project Popup System)  
**Last Updated:** March 2026

---

## 📁 File Structure

```
kssoftware/
├── index.html          ← Main homepage (this file)
├── about.html          ← About Us page
├── clients.html        ← Portfolio / Clients page
├── contact.html        ← Contact page
├── KS.png              ← Logo image (required)
└── README.md           ← This file
```

---

## ✅ Quality Checklist

| Feature | Status |
|---|---|
| Fully Responsive Design | ✅ Working |
| SEO Optimized (All Pages) | ✅ Working |
| Fast Loading | ✅ Working |
| Cross-Browser Compatible | ✅ Working |
| Accessible Design (WCAG) | ✅ Working |
| Professional UI | ✅ Working |
| Working Contact Forms | ✅ Working |
| WhatsApp Integration | ✅ Working |
| Email Integration | ✅ Working |
| Premium Animations | ✅ Working |
| SSL Secured & HTTPS | ✅ Working (server-side) |
| Google Analytics Ready | ✅ Add GA4 tag to `<head>` |

---

## 🆕 New in Version 2.0 — Project Popup System

Every service card now has a **"View Projects →"** button. When clicked, a full-screen popup modal opens showing:

### What's Inside Each Popup:
1. **Stats Row** — Key numbers (projects done, ratings, metrics)
2. **Tabbed Navigation** — Filter projects by category
3. **Project Cards** — Each with thumbnail, description, and tech tags
4. **Technologies Grid** — Tools & stack used for that service
5. **Quality Checklist** — (shown for Web Dev & Mobile App services)
6. **CTA Buttons** — "Start a Similar Project" + WhatsApp direct link

### Services with Project Popups:
| Service | Projects Shown |
|---|---|
| 🌐 Web Development | 8 projects (E-Commerce, Corporate, Educational) |
| 📱 Mobile App Development | 6 apps (Android, iOS, Cross-Platform) |
| 🎓 College Projects | 6 academic projects (Final Year, Mini Projects) |
| 🔍 SEO & Digital Marketing | 4 case studies with results |
| ☁️ Cloud Solutions | 4 cloud deployments |
| 🤖 AI & Automation | 4 AI/ML projects |
| 🔧 Website Maintenance | Service details & process |
| 🛠️ Software Maintenance | Service breakdown |
| 🌍 Website Hosting | Hosting plans & features |
| 🔒 SSL & Security | Security services |
| 🌐 Domain Registration | TLDs & DNS services |
| 💾 Backup & Recovery | Backup plans |
| ⚡ Speed Optimization | What we fix & results |
| 📧 Business Email | Email platforms & setup |

---

## 🎨 Design System

### Colors (CSS Variables)
```css
--black:       #050A14   /* Main background */
--card:        #0B1527   /* Card background */
--blue-mid:    #1565C0   /* Primary blue */
--blue-bright: #1E88E5   /* Bright blue */
--blue-el:     #42A5F5   /* Accent blue */
--white:       #FFFFFF
--off-white:   #E8F0FE   /* Body text */
--gray-mid:    #B0BEC5   /* Muted text */
```

### Fonts
- **Rajdhani** — Headings, logo, numbers
- **Exo 2** — Body text, buttons
- **JetBrains Mono** — Badges, labels, tags

---

## ⚙️ Configuration — Things to Update

### 1. WhatsApp Number
Find and replace `917385522051` with your number (country code + number, no spaces):
```
917385522051  →  91XXXXXXXXXX
```

### 2. Email Address
```
mrdeveloper1397@gmail.com  →  your@email.com
```

### 3. Phone Number Display
```
+91 73855 22051  →  your number
```

### 4. Address
```
Begumpet, Hyderabad, Telangana, India  →  your address
```

### 5. Discount Popup Deadline
```javascript
// Find this line in the script:
var deadline = new Date('2026-04-30T12:00:00+05:30').getTime();
// Change the date as needed
```

### 6. Google Analytics (Add to `<head>`)
```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

## 📱 Sections on the Homepage

| Section | Description |
|---|---|
| **Navbar** | Sticky nav with mobile hamburger menu |
| **Hero** | Full-height hero with animated orbs, stats, and service cards |
| **Services** | 14 service cards — each clickable to open project popup |
| **Why Choose Us** | 4 feature cards |
| **Trust Numbers** | Stats banner (50+ projects, 100% satisfaction, etc.) |
| **Process** | 4-step process: Discover → Plan → Build → Deliver |
| **Quality Checklist** | 12-item checklist showing what every project includes |
| **CTA** | Final call-to-action with WhatsApp button |
| **Footer** | 4-column footer with links, services, contact |

---

## 🔧 Floating Elements

| Element | Behavior |
|---|---|
| **WhatsApp Button** | Bottom-right, pulses with notification badge; auto-opens after 3s (once per session) |
| **Scroll to Top** | Appears after scrolling 300px |
| **Discount Popup** | Auto-shows after 4 seconds (once per session); counts down to Apr 30, 2026 12:00 PM IST |

---

## 🚀 Deployment Checklist

- [ ] Upload `index.html`, `about.html`, `clients.html`, `contact.html`, `KS.png` to server
- [ ] Enable SSL/HTTPS on hosting panel
- [ ] Set correct file permissions (644 for files, 755 for folders)
- [ ] Submit `sitemap.xml` to Google Search Console
- [ ] Verify Google My Business listing
- [ ] Add Google Analytics 4 tag
- [ ] Test all WhatsApp links
- [ ] Test contact form submission
- [ ] Check mobile responsiveness on real device
- [ ] Run Google PageSpeed Insights test

---

## 📞 Support

For any changes or issues, contact KS Software:

- 📞 **Phone:** +91 73855 22051
- 💬 **WhatsApp:** [wa.me/917385522051](https://wa.me/917385522051)
- ✉️ **Email:** mrdeveloper1397@gmail.com
- 🌐 **Website:** [kssoftware.co.in](https://kssoftware.co.in)

---

*© 2026 KS Software Company, Begumpet, Hyderabad, Telangana, India*


# KS Software — Logo Redesign Brief

## Project
Redesign the KS Software logo into a premium, modern global tech-brand identity. Keep the "KS" initials as the core identity; everything else is open to reinvention.

## Company Context
- **Name:** KS Software
- **Location:** Hyderabad, India
- **Services:** AI solutions, custom software development, mobile app development, web development, ERP/CRM development, SaaS products, cloud applications, UI/UX design, API development, enterprise solutions, digital transformation

## Current Logo (starting point)
- Blue "K", white "S"
- Blue swoosh/orbit ring around the letters
- Black or dark background
- "SOFTWARE" wordmark below in white
- Reads as dated (circa 2012–2015 styling)

## Direction
Do not just polish the old mark — rethink it. Only the "KS" initials must carry over.

**Target feel:** premium, minimal, geometric, trustworthy, future-ready — visually at home next to brands like Stripe, Linear, Figma, Vercel, Atlassian, Google, Microsoft, and OpenAI.

**Avoid:** 3D effects, bevels, lens flares, drop shadows, swooshes/orbit rings, generic globe icons, clipart, cartoon styling, busy compositions.

## Concepts to Explore (pick 2–3 to develop)
1. Lettermark (clean "KS" monogram)
2. Abstract/geometric symbol referencing network, connection, or data flow
3. Negative-space mark (icon and letters share space)
4. AI-inspired mark (subtle nod to intelligence/automation without literal robot/circuit clichés)

## Typography
- Modern geometric sans-serif for "KS SOFTWARE" wordmark
- Reference fonts: Inter, Satoshi, Circular, Neue Haas Grotesk, SF Pro Display
- Wide, confident letter spacing; no decorative fonts

## Color Palette
- **Primary:** Royal blue / electric blue / deep navy
- **Secondary:** White, silver, light gray
- **Optional accent:** Cyan or a subtle blue gradient (use sparingly)

## Required Variations
- Primary (horizontal) logo
- Vertical/stacked logo
- Icon only (for favicon / app icon)
- Wordmark only
- Monochrome black & monochrome white versions
- Versions for white, black, dark navy, and transparent backgrounds
- App icon (1024×1024) and favicon (512×512)

## Quality Bar
Should look agency-made (Pentagram / Collins / Wolff Olins tier): timeless, scalable, legible at small sizes, and instantly recognizable in black-and-white with no gradient.

## Deliverable Formats
SVG (vector master), PNG (transparent), PDF, high-res 4K exports for mockups.