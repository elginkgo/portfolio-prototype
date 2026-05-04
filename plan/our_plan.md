# Plan: Sustainability Analyst Portfolio Website

This plan outlines the creation of a modern, multi-page portfolio website for **Chawapol Tang**, a Sustainability Analyst, designed for deployment on GitHub Pages.

## Objective
Create a professional, "modern white and rich green" themed portfolio that showcases expertise in sustainability through a multi-page structure.

## Key Files & Context
- **Colors:** Modern White (`#F8F9FA`), Rich Green (`#1B4332`), Text Ink (`#081C15`).
- **Typography:** DM Sans (Google Sans alternative).
- **Structure:**
    - `index.html`: Home page with hero and introduction.
    - `projects.html`: Overview of 3 core projects.
    - `contact.html`: Contact information and links.
    - `css/style.css`: Centralized styling.
    - `js/main.js`: Basic interactivity.

## Implementation Steps

### Phase 1: Foundation & Styling
1. **Create Directory Structure:** `css/`, `js/`, `assets/`.
2. **Setup `style.css`:**
    - Define CSS variables for the color palette.
    - Import "DM Sans" from Google Fonts.
    - Implement a responsive navigation bar (common across all pages).
    - Design a modern footer.

### Phase 2: Page Development
1. **Develop `index.html`:**
    - **Hero Section:** "Chawapol Tang" | "The one who cares for the world".
    - **Brief Bio:** Highlighting the role of a Sustainability Analyst.
2. **Develop `projects.html`:**
    - Create a grid layout for 3 projects:
        - **Project 1:** *RECs Tokenization Framework*
        - **Project 2:** *Sales Strategy Analytics Pipeline*
        - **Project 3:** *RECs Inventory Reconciliation*
    - Each project will have a title, brief description, and placeholder for an image.
3. **Develop `contact.html`:**
    - Modern layout with contact details (Email, LinkedIn, GitHub).
    - Simple "Get in Touch" call-to-action.

### Phase 3: Interactivity & Refinement
1. **Setup `main.js`:**
    - Implement a simple navigation toggle for mobile.
    - Add smooth transition animations between pages (optional/subtle).
2. **Final Polish:** Ensure accessibility (WCAG compliance) and mobile responsiveness.

## Verification & Testing
1. **Cross-browser check:** Verify rendering on Chrome, Firefox, and Safari.
2. **Mobile Responsiveness:** Use DevTools to check various screen sizes.
3. **Link Validation:** Ensure all internal navigation links work correctly.
4. **GitHub Pages Readiness:** Verify `index.html` is in the root and all asset paths are relative.
