# Koda LLC - Company Website

Professional website for Koda LLC AI & Computer Vision consulting services.

## Features

- **Modern Design**: Animated gradients, floating shapes, scroll animations
- **Dynamic Elements**: Interactive hover effects, animated counters, parallax scrolling
- **Responsive**: Mobile-optimized with smooth transitions
- **Performance**: Intersection Observer API for efficient animations

## Local Development

Open `index.html` in browser or use Live Server extension.

## Deployment

Auto-deployed via GitHub Pages on push to `main` branch.

- **GitHub Pages**: https://kodaai-dev.github.io/company_website
- **Custom Domain**: https://site.kodaaitools.com (current)
- **Desired Domain**: https://kodaaitools.com (requires DNS migration)

## DNS Setup

Currently using subdomain due to Squarespace limitations. For root domain:
1. **Transfer DNS to Cloudflare** (recommended)
2. Keep domain registered with Squarespace
3. Copy Google Workspace MX records to Cloudflare
4. Update CNAME file to `kodaaitools.com`
