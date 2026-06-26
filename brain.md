# Project Brain: Priyanshu Singh Resume Portfolio

This file serves as a knowledge base and update log for the **Priyanshu Singh Resume Portfolio Website**.

## 🧠 Project Architecture & Design System
- **Core Technology**: Static HTML5 page (`index.html`) using Vanilla CSS and Vanilla JavaScript.
- **Design Aesthetic**: Premium dark mode glassmorphism layout. It includes:
  - **Aesthetics**: Custom Outfit, Space Grotesk, and JetBrains Mono typography.
  - **Background**: Animated CSS gradient floating blobs and micro-particles.
  - **Interactions**: Custom Javascript-powered 3D Tilt effect on cards, Mouse Glow follower, and a custom interactive **Pixel Canvas Engine** rendered in the sidebar.
  - **Navigation**: Glassmorphic scroll-spy navigation bar at the top of the screen.

## 🛠️ Layout & Content Updates
The following changes are being implemented based on requested updates:

1. **LinkedIn Profile Link**:
   - Linked the LinkedIn contact chip to the user's actual profile: [LinkedIn Profile](https://www.linkedin.com/in/priyanshu-singh-616318417/)

2. **More Segments in Experience Tiles**:
   - Added descriptive achievement bullet points (segments) to the **TATA Data Analytics Mini Internship** and **FORAGE Data Visualization Micro Internship** tiles. This matches the detail level of the other experience cards.

3. **Bento Grid Layout (Desktop)**:
   - Converted `.sections-grid` from a simple flexbox column to a 2-column CSS Grid.
   - Allows tiles like **Education** and **Certifications** to sit side-by-side as distinct grid segments on desktop, improving space efficiency and creating a premium layout.
   - Retains a responsive single-column layout on mobile devices (< 768px).
