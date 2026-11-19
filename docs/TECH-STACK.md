# Technical Stack

## Core Technologies
- **HTML5** – The markup language for structuring the page. Chosen because the assignment focuses on mastering semantic elements.
- **CSS3** – Styling language to create the dark theme, layout, and responsive behavior. No preprocessors or frameworks are used to keep the project simple and portable.
- **No JavaScript** – The requirements explicitly forbid scripting; all interactions are achieved through CSS (e.g., hover effects).

## Asset Management
- **Local Image Assets** – All images (logo, product photos, icons, member avatars) are stored in the `assets/` folder. This avoids external network requests and ensures the page works offline, which is ideal for a classroom setting.

## Folder Structure
```
project-root/
├─ assets/          # images, icons
├─ docs/            # documentation (PRD, DESIGN, TECH-STACK, TASKS, etc.)
├─ index.html       # entry point (to be created later)
├─ style.css        # stylesheet (to be created later)
└─ README.md        # brief project summary
```

## Rationale
- Using only **HTML + CSS** keeps the learning curve low and aligns with the assignment’s goal of practicing semantic markup.
- A flat folder layout is easy for students to navigate and understand.
- No build tools or package managers are required, satisfying the constraint to avoid unnecessary dependencies.
