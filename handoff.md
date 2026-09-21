# Typography & Font Choices

**Heading Font:** Import and apply a bold, playful display serif/sans font (such as Abril Fatface or Syne) to mirror Yukai Du’s animated, high-impact header style. Set heading sizes to 3.5rem (56px) on desktop and 2.25rem (36px) on mobile, with a bold weight (700 or 800).

**Body Font:** Use a vibrant, clean geometric sans-serif (such as Plus Jakarta Sans or Outfit) to blend the structural headers of Yukai Du and Dopple Creative Studio. Set base body text to 1rem (16px) with a line height of 1.6.

# Color Palette & Moving Background

**Base Background:** Cream white (#FDFBF7).

**Animated Background Effect:** Apply a continuous, slow gradient CSS background animation (background-size: 400% 400%) shifting subtly between cream white (#FDFBF7), soft pale yellow (#FFF9E6), and warm blush (#FFF0F3). Set the animation loop duration to 12s with an ease timing function to match a medium transition speed.

**Text Colors:** Primary body text set to #1A1A1A for legibility, with heading and list titles rendered in vibrant high-contrast accents (such as #E63946, #457B9D, and #F4A261).

**Accent Color (#2E9B4F):** Use strictly for links, borders, filled buttons, focus rings, hover underlines, and for interactive UI tags/pills (such as assignment category labels and active navigation highlights).

# Layout, Breakpoints & Grid System

**Laptop Layout (Desktop ≥ 1024px):** Render the work list grid in a strict 3 x 3 layout using CSS Grid (grid-template-columns: repeat(3, 1fr)), with a grid gap of 2rem (32px).

**Phone Layout (Mobile < 768px):** Collapse the work list grid into a single column (grid-template-columns: 1fr) with a 1.25rem (20px) vertical gap. Set tablet devices (768px to 1023px) to a 2-column grid.

**Hero Image:** Span the full width of the main content container directly below the primary header block, maintaining a responsive height (40vh to 50vh) with object-fit: cover.

**Name Placement:** Position the author name prominently inside the hero section, left-aligned over the hero layout with a high-contrast heading treatment.

# Work List Cards & Interactive Hover States

**Button & Link Styling:** Render assignment links as solid, filled buttons using the #2E9B4F accent color with white text (#FFFFFF), standard padding of 0.75rem 1.5rem (12px 24px), and sharp 0px border-radius (square corners).

**Grid Item Hover Behavior:** Display an overlay on card hover showing the title of the assignment and the type/kind of work (e.g., "Assignment 1 — HTML/CSS").

**Hover Micro-interaction:** On link hover, retain the square button shape and trigger an animated underline effect (text-decoration: underline or an expanding border-bottom: 2px solid) beneath the button text.

# Page Structure & Spacing Rules

Set global page margins using a maximum content width of 1200px, centered with margin: 0 auto and horizontal padding of 2rem (32px) on desktop and 1rem (16px) on mobile.

Enforce a vertical rhythm with 4rem (64px) spacing between the header, hero section, and assignment grid.
