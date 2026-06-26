# Project Brain: Priyanshu Singh Resume Portfolio

This file serves as a knowledge base and update log for the **Priyanshu Singh Resume Portfolio Website**.

## 🧠 Project Architecture & Design System
- **Core Technology**: Static HTML5 page (`index.html`) using Vanilla CSS and Vanilla JavaScript.
- **Design Aesthetic**: Premium dark mode glassmorphism layout with high-end micro-interactions.
  - **Color Palette**: A curated theme featuring vibrant accents:
    - Purple (`#8B7CF7`): Scrollbar, highlights, TATA section theme.
    - Teal/Cyan (`#2EE8E3`): School labels, skills label, FORAGE section theme.
    - Pink (`#FF8FB8`): Technical skills & tools theme.
    - Amber/Gold (`#F5B041`): Education section theme.
  - **Aesthetics**: Custom Outfit, Space Grotesk, and JetBrains Mono typography.
  - **Background**: Faint overlay grids and animated CSS gradient floating blobs providing smooth glowing backdrops behind glass cards.
  - **Interactions**:
    - Custom Javascript-powered 3D Tilt effect on cards.
    - Smooth interactive **Mouse Glow** cursor follower.
    - Custom interactive **Pixel Canvas Engine** rendered inside the sidebar.
  - **Navigation**: Glassmorphic scroll-spy navigation bar at the top of the screen.

## 🛠️ Layout & Content Updates
The following changes have been implemented:

1. **LinkedIn Profile Link**:
   - Linked the LinkedIn contact chip to the user's actual profile: [LinkedIn Profile](https://www.linkedin.com/in/priyanshu-singh-616318417/)

2. **More Segments in Experience Tiles**:
   - Added descriptive achievement bullet points (segments) to the **TATA Data Analytics Mini Internship** and **FORAGE Data Visualization Micro Internship** tiles.

3. **Bento Grid Layout (Desktop)**:
   - Converted `.sections-grid` from a simple flexbox column to a 2-column CSS Grid.
   - Allowed tiles like **Education** and **Certifications** to sit side-by-side as distinct grid segments on desktop, improving space efficiency and creating a premium layout.
   - Retained responsive single-column layout on mobile devices (< 768px).

4. **Advanced Preloading Screen**:
   - Built a custom text-reveal loader featuring a glowing neon load progress bar using a linear gradient transition.
   - Implemented a smooth cubic-bezier exit fade when the page finishes loading.
