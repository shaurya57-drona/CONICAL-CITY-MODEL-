# CONICAL-CITY-MODEL-
FOR a school &amp; college project in which we use conical shapes properties in architecture to create a High strength structures, it's for knowledge purpose 
<br>
You are an expert frontend engineer, UI/UX designer, and Three.js developer. Create a highly polished, professional educational website called “Conic City: Geometry in Architecture”.

PROJECT VISION
This website explains conic sections through architecture and futuristic city design. It must feel like a premium student project, but still be clean, practical, and easy to understand. The website should be interactive, smooth, and visually strong, with no clutter.

ABSOLUTE REQUIREMENTS
- Homepage must route to four separate shape pages:
  - Circle
  - Parabola
  - Ellipse
  - Hyperbola
- Use real Three.js for mini 3D map visualization.
- Website must be mobile-friendly, but do not reduce features or content quality.
- Add a language switcher.
- Add Compare buttons on every structure card.
- Compare button should open a dedicated compare page when two structures are selected.
- Follow all UX, accessibility, and responsiveness best practices.
- Every page should look professional and feel finished.

SITE STRUCTURE

1. HOMEPAGE
Purpose:
The homepage must act only as the entry point and shape selector. It should not overload the user.

Homepage sections:
- Sticky header with logo, nav, and language switcher.
- Hero section with project title and concise tagline.
- Four large shape cards:
  - Circle
  - Parabola
  - Ellipse
  - Hyperbola
- Short “How it works” section.
- Mini 3D map preview area.
- City scorecard preview.
- Footer.

Homepage behavior:
- Clicking a shape card opens its dedicated shape page.
- Homepage should clearly explain that each shape leads to its own city zone.
- Keep the homepage clean, balanced, and easy to scan.

2. SHAPE PAGES
Create four separate pages:
- circle.html
- parabola.html
- ellipse.html
- hyperbola.html

Each shape page must include:
- Back button to homepage.
- Shape title and short introduction.
- Real Three.js mini 3D city/structure cluster.
- At least 4 structures for that shape.
- Each structure card must have:
  - name
  - short explanation
  - shape relation
  - compare button
- Hover labels.
- Color-coded design.
- A small scorecard.
- A real architecture inspiration section.
- Smooth but lightweight mini animations.

3. COMPARE PAGE
Create compare.html.

Compare page behavior:
- User clicks Compare on one structure.
- Then clicks Compare on another structure.
- The site opens compare.html automatically.
- Compare page must show both structures side-by-side.
- Explain:
  - shape type
  - architectural function
  - visual style
  - engineering meaning
  - equation reference
  - which context each structure is best for
- Clear conclusion box at the end.
- Support language switcher here too.

UI/UX GOALS
- Clean, futuristic, academic look.
- Premium but not flashy.
- Strong visual hierarchy.
- Spacious layout.
- Readable typography.
- Rounded corners.
- Soft shadows.
- Smooth hover states.
- Consistent spacing.
- No visual clutter.
- Clear CTAs and navigation.
- Use accessible contrast.
- Avoid using color alone to convey meaning.

RESPONSIVE DESIGN GOALS
- Mobile-first design, but equally polished on desktop.
- No horizontal scrolling.
- Flexible grid layout.
- Typography should scale with rem/em units.
- Buttons and cards should be easy to tap on mobile.
- Content should stack naturally on smaller screens.
- Three.js canvas must resize properly and stay sharp on mobile.
- If needed, reduce scene complexity on smaller devices instead of removing features.

LANGUAGE SWITCHER
- Add a language switcher in the header.
- Support English and Hindi/Hinglish.
- Use text-based language labels, not flags.
- Make it accessible and keyboard-friendly.
- Save selected language in localStorage.
- Update visible UI text immediately when language changes.

THREE.JS REQUIREMENTS
- Use real Three.js for the mini city/map preview.
- Make it lightweight and responsive.
- Build an isometric-style or mini 3D structure cluster.
- Include basic lighting and camera setup.
- Add subtle rotation or hover effects.
- Resize renderer and camera on window resize.
- Limit complexity on mobile for performance.
- If necessary, use a simplified mobile version of the scene rather than removing it.
- Ensure the canvas does not blur or distort.

COLOR SYSTEM
Use consistent shape-specific colors:
- Circle = blue
- Parabola = orange
- Ellipse = green
- Hyperbola = purple

Use these colors consistently in:
- cards
- labels
- scorecards
- buttons
- highlights
- compare indicators

INTERACTION RULES
- Each structure card must have a Compare button.
- Compare selection should be stored in sessionStorage or localStorage.
- First selection stores Structure A.
- Second selection stores Structure B.
- After second selection, open compare page automatically.
- Add a way to reset compare selection.
- Include hover feedback and active states.

CONTENT REQUIREMENTS
- Keep all explanations simple, educational, and professional.
- Use architecture language that a school audience can understand.
- Each shape page should have at least 4 distinct structures.
- Include equations for the conic section where relevant.
- Add short, original descriptions instead of copied text.
- Explain why each shape matters in architecture.

ACCESSIBILITY REQUIREMENTS
- Use semantic HTML.
- Proper heading hierarchy.
- Accessible buttons and links.
- Visible focus states.
- Good contrast ratios.
- Support keyboard navigation.
- Add alt-like text or labels for non-text UI.
- Do not use animation in a way that harms readability or accessibility.

FILE STRUCTURE
Provide the project in a modular way:
- index.html
- circle.html
- parabola.html
- ellipse.html
- hyperbola.html
- compare.html
- styles.css
- app.js
- data.js
- three-scene.js

IMPLEMENTATION ORDER
1. Define the data model for shapes and structures.
2. Build HTML structure for homepage and pages.
3. Create CSS system and responsive layout.
4. Implement language switcher.
5. Implement compare selection logic.
6. Implement Three.js scenes.
7. Add hover labels and scorecards.
8. Add mobile optimization.
9. Final polish.

OUTPUT FORMAT
Before writing code:
- Briefly explain the website architecture.
- Explain which parts belong in HTML, CSS, JavaScript, and Three.js.
- Mention any assumptions.
Then provide the full code in a clean, organized manner.

IMPORTANT DESIGN PRINCIPLES
- Homepage must be a clean gateway, not a crowded dashboard.
- Shape pages must be the main learning experience.
- Compare page must clearly help users understand differences.
- Mobile support must be high quality, not a fallback.
- Every feature should feel intentional and polished.
- The final result should feel professional, smooth, and ready for presentation.