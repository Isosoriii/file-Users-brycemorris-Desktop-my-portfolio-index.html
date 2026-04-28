# GitHub Copilot Instructions

## Project Overview
This is a personal portfolio website built as a single-page static HTML application showcasing professional work and skills.

## Architecture
- **Single File Design**: Entire site contained in `index.html` with embedded CSS
- **Semantic Structure**: Organized into logical sections (header, hero, about, skills)
- **No Dependencies**: Pure HTML/CSS, no external libraries or frameworks
- **Static Hosting Ready**: Can be deployed to any static web host

## Key Components
- **Header**: Contains name and navigation menu with anchor links
- **Hero Section**: Welcome message and introduction
- **About Me**: Personal/professional background
- **Skills**: Technical competencies listed in bullet points

## Development Patterns
- **Inline Styling**: CSS defined in `<style>` tag within `<head>`
- **Semantic HTML**: Uses proper elements like `<header>`, `<section>`, `<nav>`
- **Anchor Navigation**: Internal links using `#id` for smooth scrolling
- **Responsive Design**: Basic viewport meta tag for mobile compatibility

## Workflows
- **Editing**: Modify `index.html` directly in VS Code
- **Preview**: Open `index.html` in browser (double-click file or use `open index.html`)
- **No Build Process**: Changes reflect immediately upon saving
- **Customization**: Update name, content, and styles as needed

## Common Tasks
- **Update Name**: Change text in `<h1>` within `<header>`
- **Add Skills**: Append `<li>` items to `<ul>` in `#skills` section
- **Modify Styling**: Edit CSS rules in `<style>` tag
- **Add Sections**: Insert new `<section>` elements with corresponding nav links

## File Structure
```
my-portfolio/
├── index.html          # Main portfolio page
└── .github/
    └── copilot-instructions.md
```