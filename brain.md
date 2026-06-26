# Project Brain: Priyanshu Singh Resume Portfolio

This file serves as a knowledge base and update log for the **Priyanshu Singh Resume Portfolio Website**.

## 🧠 Project Architecture & Design System
- **Core Technology**: Static HTML5 page (`index.html`) using Vanilla CSS and Vanilla JavaScript.
- **Design Aesthetic**: Ultra-premium minimalist grayscale/silver glassmorphic layout.
  - **Color Palette**: A professional, neutral grayscale system:
    - Pure White (`#ffffff`): Main accent, silver highlights, primary loader indicators.
    - Silver/Light Gray (`#cccccc`): Section headings, subheadings, labels.
    - Slate/Medium Gray (`#a1a1a6` & `#86868b`): Muted copy, metadata, secondary elements.
    - Deep Charcoal (`#0a0a0c` to `#0f0f12`): Matte black and charcoal backdrops.
  - **Aesthetics**: Custom Outfit, Space Grotesk, and JetBrains Mono typography.
  - **Background**: Animated CSS gradient floating neutral blobs providing smooth glowing backdrops.
  - **Interactions**:
    - Custom Javascript-powered 3D Tilt effect on cards.
    - Smooth interactive **Mouse Glow** soft white cursor spotlight follower.
    - Custom interactive **Pixel Canvas Engine** rendered in grayscale shades (white/gray pixels) inside the sidebar.
  - **Navigation**: Glassmorphic scroll-spy navigation bar at the top of the screen.

## 🛠️ Layout & Content Updates
The following changes have been implemented:

1. **LinkedIn Profile Link**:
   - Linked the LinkedIn contact chip to the user's actual profile: [LinkedIn Profile](https://www.linkedin.com/in/priyanshu-singh-616318417/)

2. **More Segments in Experience Tiles**:
   - Added descriptive achievement bullet points (segments) to the **TATA Data Analytics Mini Internship** and **FORAGE Data Visualization Micro Internship** tiles.

3. **Bento Grid Layout (Desktop)**:
   - Converted `.sections-grid` from a simple flexbox column to a 2-column CSS Grid.
   - Allowed tiles like **Education** and **Certifications** to sit side-by-side as distinct grid segments on desktop.
   - Retained responsive single-column layout on mobile devices (< 768px).

4. **Advanced Preloading Screen**:
   - Built a custom text-reveal loader featuring a silver-white glowing progress bar.
   - Implemented a smooth cubic-bezier exit fade when page finishes loading.
