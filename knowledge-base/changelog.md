# Changelog

## 2026-04-28 — Initial Page Creation
**What**: Created premium TaxFlow Accounting Services landing page
**Why**: Client needed a professional, visually stunning HTML page for their Sydney-based accounting firm
**Files Changed**: `index.html`, `styles.css`, `images/*`
- Built complete landing page with hero, trust bar, credibility, services, why-us, clients, process, FAQ, CTA, and footer sections
- Generated 5 custom images (hero, individual services, business services, clients, CTA background)
- Implemented scroll-triggered animations via IntersectionObserver
- Added FAQ accordion with JSON-LD structured data
- Full responsive design with mobile breakpoints
- Corporate blue theme with Inter font

## 2026-04-29 — Hero Heading Update
**What**: Replaced hero section heading to feature Pooja Chillana as the registered tax agent
**Why**: Client requested personalised branding with the tax agent's name and broader "Australian" scope
**Files Changed**: `index.html`
- Updated h1 from "Sydney Accounting and Tax Services — Registered Tax Agent and CPA-Led" to "Australian Accounting & Tax Services by Your Local Registered Tax Agent Pooja Chillana — For All Individuals & Businesses"

## 2026-04-29 — Hero Location Pins & Offer Banner
**What**: Added 📍 location pins to hero paragraph and $29 off promotional banner in contact form
**Why**: Client wanted prominent location display and a conversion-driving offer in the hero form
**Files Changed**: `index.html`
- Updated service-area paragraph to include "📍 Harris Park, 📍 Marsden Park, and 📍 Greenway Village Colebee"
- Added eye-catching gradient offer banner (orange/red) at top of hero contact form: "REGISTER NOW & GET $29 OFF on your first enquiry"
- Changed form title from "Get a Free Consultation" to "Free Consultation"

## 2026-04-29 — Premium Visual Overhaul
**What**: Comprehensive premium redesign of the entire landing page
**Why**: Client wanted an extraordinary, premium-looking page
**Files Changed**: `index.html`
- Added Google Font (Inter) for premium typography with font smoothing
- Upgraded color palette to deeper, richer blues (#2563eb, #1e40af, #0f172a)
- Enhanced hero overlay gradient for a more dramatic dark-to-blue effect
- Upgraded glassmorphism form with stronger blur, inner glow, and pulsing blue shadow
- Added gradient top-borders to credibility cards (blue, purple, teal, amber)
- Refined button design with cubic-bezier transitions and layered shadows
- Premium card hover effects with radial light glow
- Upgraded step circles, who-tags, accordion with refined borders and shadows
- Added shimmer animations on CTA buttons, gradient text on heading
- Scroll-reveal fade-up animations on all major sections via IntersectionObserver
- Added floating badge, pulsing offer banner, and hovering micro-interactions throughout

## 2026-04-29 — Mobile Layout Adjustments
**What**: Reordered layout on mobile devices
**Why**: Client requested form/map to appear before the text content on small screens
**Files Changed**: `index.html`
- Updated `.hero-inner` to `flex-direction: column-reverse` on screens under 768px
- Updated `.contact-grid` to `flex-direction: column-reverse` on screens under 768px

## 2026-05-01 — Header Bar Addition
**What**: Added TaxFlow branded header bar to the top of the page
**Why**: Client requested a header matching their brand design — logo on left, phone CTA on right
**Files Changed**: `index.html`
- Added `<header class="tf-header">` with SVG shield logo (black/gold), "TaxFlow" branding, and "ACCOUNTING SERVICES" subtitle
- Right side features a "CALL US TODAY / 0477-400-929" clickable phone link with blue circle icon
- Light gray background (#e8e8e8) with subtle bottom border
- Fully responsive: scales down logo, text, and CTA for mobile (≤768px)
- CSS scoped under `.tf .tf-header*` to avoid conflicts
