# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Professional website for Koda LLC AI & Computer Vision consulting. Features modern animations, dynamic interactions, and responsive design.

## Development

- **Local testing**: Open `index.html` in browser or use Live Server
- **Tech stack**: HTML5, CSS3, Vanilla JavaScript
- **Key features**: Animated gradients, scroll animations, parallax effects, interactive elements

## Deployment

**Current setup**: GitHub Pages with subdomain
- Site: https://site.kodaaitools.com
- GitHub Pages: https://kodaai-dev.github.io/company_website

**Desired setup**: Root domain (requires DNS migration)
- Target: https://kodaaitools.com

### DNS Migration to Cloudflare
1. Add domain to Cloudflare (free account)
2. Update nameservers in Squarespace to Cloudflare's
3. Import existing DNS records (especially Google Workspace MX records)
4. Add A records pointing to GitHub Pages IPs
5. Update CNAME file from `site.kodaaitools.com` to `kodaaitools.com`

**GitHub Pages IPs**: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153