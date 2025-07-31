# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal portfolio website for Jack McCain built with static HTML, CSS, and Tailwind CSS. The site consists of three main pages showcasing personal information, projects, and film work.

## Architecture

- **Static Website**: Pure HTML/CSS with no build process or package management
- **Styling**: Combination of custom CSS (`index.css`) and Tailwind CSS via CDN
- **Typography**: Uses Google Fonts (Noto Serif Georgian and Source Serif Pro)
- **Analytics**: Integrated with Shynet analytics service
- **Media**: Video content embedded via Vimeo player

## File Structure

- `index.html` - Main about page with personal information
- `code.html` - Projects/portfolio page showcasing various coding projects
- `film.html` - Film portfolio with embedded Vimeo videos
- `index.css` - Custom CSS styles defining layout, typography, and color scheme
- `tailwind.config.js` - Tailwind configuration (currently minimal, references non-existent src directory)
- `J.png` - Site favicon and logo

## Development Notes

- **No Build Process**: This is a static site with no compilation or bundling required
- **Tailwind Config Issue**: The `tailwind.config.js` references `./src/**/*.{html,js}` but the HTML files are in the root directory
- **Consistent Navigation**: All pages share the same navigation structure with name/logo and menu items
- **Color Scheme**: Uses a warm background (`rgb(250, 249, 246)`) with dark blue headings (`rgb(1, 35, 57)`)
- **Responsive**: Uses CSS media queries and flexible layouts for different screen sizes

## Deployment

This appears to be deployed as a static site (likely GitHub Pages based on git history showing CNAME and static.yml files).

## Common Tasks

Since this is a static HTML site, common development tasks would include:

- Edit HTML files directly for content changes
- Modify `index.css` for styling updates  
- Update the Tailwind config if adding component-based development
- Test locally by opening HTML files in browser
- Deploy by pushing to the main branch (if using GitHub Pages)