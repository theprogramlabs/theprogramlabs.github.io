# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is The Program Labs website hosted on GitHub Pages (theprogramlabs.github.io). It's a static HTML website for a social impact organization that offers two main services:
- **Builder Service**: Helping nonprofits build entrepreneurship programs and community impact hubs
- **Advisor Service**: Coaching social impact executives on program launch hurdles

## Project Structure

- `index.html` - Main landing page with all content sections
- `Paper.md` - Content model/planning document for website services and messaging
- `README.md` - Basic repository name only

## Development Commands

Since this is a static HTML site hosted on GitHub Pages, there are no build commands needed. To develop:

1. **Local Development**: Open `index.html` directly in a browser or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (if http-server is installed)
   npx http-server
   ```

2. **Deploy**: Changes pushed to the main branch are automatically deployed to GitHub Pages

## Technology Stack

- **Frontend**: Plain HTML5, CSS3, JavaScript (no framework)
- **CSS Framework**: Bootstrap 5.3.0 (via CDN)
- **Icons**: Font Awesome 6.0.0 (via CDN)
- **Hosting**: GitHub Pages

## Key Website Sections

The single-page application includes:
- Hero section with service overview
- Impact statistics showcase
- Detailed Builder Service section with pain points and credentials
- Detailed Advisor Service section with methodology and testimonials
- About section for Alex Waters (Executive Director)
- Contact/CTA section

## Content Management

- All content is hardcoded in `index.html`
- Styling is inline within `<style>` tags in the HTML head
- JavaScript for smooth scrolling and navbar effects is inline at bottom of HTML

## Design Notes

- Color scheme uses CSS variables: primary (#2c3e50), secondary (#18bc9c), accent (#e74c3c)
- Responsive design using Bootstrap's grid system
- Smooth scroll navigation between sections
- Fixed navbar with transparency effect on scroll