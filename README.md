🚀 Button Library (HTML + CSS)

Site is live at : https://gaurav-wb.github.io/Button-Library-HTML-CSS-/
Hover cursor on buttons to see animations


A modular and reusable CSS button library built using pure HTML and CSS.
Designed for scalability, consistency, and easy integration into any front-end project.

📌 Overview

This project provides a collection of customizable button styles, including:

Basic buttons
Outline buttons
Glow effects
Rounded buttons
Gradient styles
Neon & glass effects
Animated buttons (pulse, 3D press, rotate)

No JavaScript. No frameworks. Just clean CSS.



Standard UI buttons with predefined color themes:

Primary
Secondary
Danger
Light
Dark

2. Outline Buttons

Minimalist buttons with border-only styling and hover fill effects.

3. Glow Buttons

Hover-based glow effects using box-shadow.

4. Rounded Buttons

Fully rounded pill-style buttons.

5. Gradient Buttons

Modern gradient backgrounds using linear-gradient().

Includes:

Multiple gradient presets
Neon glow button
Glass (frosted) button using backdrop-filter
6. Animated Buttons

Interactive buttons with motion:

Pulse animation
3D press effect
Rotating icon button
🧠 Design System

The project uses CSS variables for consistency:

:root {
  --primary: rgb(0,120,255);
  --secondary: rgb(100,100,100);
  --danger: rgb(220,50,50);
  --radius: 8px;
}

👉 This allows easy global customization of colors and border radius.


⚠️ Issues & Limitations (Read This)

This project is functional, but not perfect. Here’s what needs improvement:

❌ Inconsistent class naming (gradient-1, glow-blue, etc.)
❌ Repeated button styling (button {} defined twice)
❌ Some color conflicts (e.g. outline-light)
❌ No responsive layout system (no grid/flex alignment for sections)
❌ No component abstraction (not scalable yet)

👉 If you plan to use this in production, refactor it into a proper design system.

🔧 Future Improvements
Convert to a utility-based system
Add size variants (sm, md, lg)
Improve naming convention (BEM or Tailwind-style)
Add accessibility (ARIA, focus states)
Create a React / Vue version

💡 Why This Project Exists

This is not just a UI collection.
It’s a foundation for building a scalable design system.

If you don’t fix structure early, your CSS becomes unmaintainable fast.

👤 Author

Gaurav Neermul
Frontend Developer (in progress)

📜 License

Free to use, modify, and improve.

