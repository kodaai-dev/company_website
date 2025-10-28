# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development

Static website for Koda AI Tools. Open `index.html` in browser to test locally.

## Deployment

### GitHub Pages Setup
1. Go to repository Settings → Pages
2. Select `main` branch, `/ (root)` folder
3. Site available at: `https://koda-ai-dev.github.io/company_website`

### Custom Domain (kodaaitools.com)
**CNAME file already exists** with `kodaaitools.com`

1. In GitHub Pages settings, add custom domain: `kodaaitools.com`
2. Check "Enforce HTTPS"
3. Configure DNS with domain provider:
   - **CNAME record**: `kodaaitools.com` → `koda-ai-dev.github.io`
   - **Or A records** to GitHub IPs: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153

DNS propagation takes 5-10 minutes. Site will be live at `https://kodaaitools.com`