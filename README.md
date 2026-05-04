# Chawapol Tang | Sustainability Analyst Portfolio

This is a modern, multi-page portfolio website for **Chawapol Tang**, a Sustainability Analyst. The site is designed to showcase expertise in sustainability through a "Cream & Deep Forest" theme, hosted on GitHub Pages.

## 🌿 Project Vision
To provide a professional platform highlighting data-driven insights and strategic ESG reporting aimed at building a greener, more resilient future.

## 🚀 Features
- **Modern Design:** Responsive layout with a professional Cream, Deep Forest, and Sand color palette.
- **Markdown-based Blog:** 
    - Dynamic post rendering without a backend.
    - Categorized topics: **Sustainability**, **Business**, and **Self Improvement**.
    - "Latest Writing" section integrated into the Home page.
- **Project Showcase:** Grid-based display of key professional projects with category tagging.
- **Interactive Elements:**
    - Dark mode toggle for accessibility.
    - Client-side Markdown rendering using `marked.js`.
- **Tech Stack:** HTML5, Vanilla CSS3, JavaScript (ES6+), and Marked.js.

## ✍️ How to Add a New Blog Post
1. **Write:** Create a `.md` file in `docs/content/posts/` (e.g., `my-new-post.md`).
2. **Images:** Place any post images in `docs/assets/blog/`.
3. **Register:** Add the post metadata to the top of `docs/content/posts.json`:
   ```json
   {
     "title": "Your Post Title",
     "slug": "my-new-post",
     "category": "Sustainability",
     "date": "2026-05-04",
     "excerpt": "Brief summary of the post...",
     "thumbnail": "assets/blog/your-image.jpg"
   }
   ```
4. **Publish:** Push your changes to GitHub.

## 📂 Project Structure
```text
├── docs/               # Web Content (GitHub Pages source)
│   ├── index.html      # Home Page (Latest Posts)
│   ├── blog.html       # Blog Index (Filtering)
│   ├── post.html       # Dynamic Post Template
│   ├── projects.html   # Portfolio of Work
│   ├── contact.html    # Contact Page
│   ├── content/
│   │   ├── posts/      # Markdown (.md) files
│   │   └── posts.json  # Post Registry
│   ├── assets/
│   │   └── blog/       # Blog Images
│   ├── css/
│   │   └── style.css   # Theme & Layout
│   └── js/
│       └── main.js     # Shared Interactivity
├── README.md           # Project Overview
└── plan/
    └── our_plan.md     # Development History
```

## 📄 License
© 2026 Chawapol Tang. All rights reserved.
