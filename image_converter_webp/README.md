# 🖼️ Image Converter to WEBP (Web Edition)

A powerful and intuitive **browser-based** image converter that transforms images into the modern **WebP** format with real-time preview and quality adjustment.

---

## 🚀 Features
- 🖼️ Side-by-side comparison of original and converted images  
- ⚡ Real-time conversion with FPS counter  
- 🎚️ Adjustable quality slider (0–100%)  
- 🧩 Lossless compression option  
- 🔍 Synchronized zoom and pan controls  
- 📏 File size comparison  
- 🌗 Multiple dark themes and light mode  
- 🖥️ Fullscreen mode support  
- 📱 Responsive and adaptive layout  

---

## 🧠 AI Involvement
Developed collaboratively with **Claude Sonnet 4.5 (Anthropic)** to design UI, implement the Canvas-based conversion logic, and refine user interactions.

**Initial prompt:**
## 🧠 Prompt Used for Generation

This application was created as part of the *Vibe Projects* collection using AI-assisted development.  
Below is the complete prompt (updated from the original version) that led to the final version of the app.  
It can be reused or adapted to generate similar projects.

---

### 🏗️ Project Goal
Create a fully functional, single-page **HTML** application that converts standard browser-supported image formats  
(**JPG, PNG, BMP, GIF, TIFF, SVG, ICO**, etc.) into the modern **WEBP** format directly in the browser using  
**JavaScript (Canvas API)** — no backend.

---

### ⚙️ Functional Requirements

1. **Theme System**
   - Support multiple dark themes and one light theme.
   - Include a dropdown menu to switch themes: *Dark Blue, Dark Purple, Dark Green, Dark Amber, Light*.
   - Colors and transitions must look modern and pleasant.

2. **Overall Design**
   - Use clean, modern **CSS3** (no frameworks).
   - The layout should be **responsive** and visually balanced.
   - Smooth transitions for hover, zoom, and theme changes.
   - Font: `Segoe UI`, `Tahoma`, or system UI.

3. **Layout Structure**
   - **Top section:**
     - App title — `Image Converter to WEBP`.
     - Right side: theme selector and **Fullscreen** button.
   - **Below title:**
     - Filename of the loaded image (updates dynamically).
   - **Main content area:**
     - Two equal rectangular panels:
       - Left → original image  
       - Right → converted WEBP image  
     - A **vertical toolbar** between them with:
       ```
       + (Zoom In)
       [Zoom % label]
       - (Zoom Out)
       ? (Info button)
       ```
     - The zoom percentage label updates dynamically (e.g., `150%`).
     - Zooming and panning must be synchronized across both images.

4. **Image Interaction**
   - Zoom in/out by ±10%, reset to 100%.
   - Zoom affects image scaling, not container size.
   - Drag (pan) the image to explore details — both sides move synchronously.
   - Keep zoom and pan state when converting with new settings.

5. **Below the Viewer**
   - A single info row showing:
     - Original file size (left)
     - `Lossless` checkbox (center)
     - Converted file size (right)
   - These values must update automatically after conversion.

6. **Quality Control**
   - A horizontal **slider (0–100%)** with:
     - Label `Quality:`
     - Current value (e.g., `80%`)
   - When changed, re-convert the image instantly while maintaining current zoom/pan.

7. **Action Buttons**
   - **📁 Load Image** — opens file picker  
   - **💾 Save Image** — downloads converted WEBP (disabled until conversion is ready)

8. **Information Modal**
   - Opens via `?` button.
   - Contains:
     - App overview and features list
     - Supported formats
     - Usage guide
     - “Why WEBP?” explanation
     - Footer with:
       ```
       Created by: Osidach Vitaliy
       AI Assistant: Claude Sonnet 4.5 (Anthropic)
       Year: 2025
       Technology: Pure HTML5, CSS3, JavaScript (Canvas API)
       ```

9. **Behavior**
   - FPS counter during conversion.
   - Fullscreen toggle (`⛶` button).
   - Smooth pan, zoom, and theme transitions.
   - Auto-refresh conversion when quality or lossless options change.

10. **Language and Code Style**
    - All UI elements, text, and code comments in **English only**.
    - Entirely self-contained file: `index.html`.
    - Structured and commented JavaScript.

---

### 🧩 Technologies
- **HTML5**, **CSS3**, **JavaScript**
- **Canvas API** for image processing
- No external libraries or frameworks

---

### 🪄 Example Prompt Summary
> Build a **fully self-contained single-page HTML app** that converts images (JPG, PNG, BMP, etc.)  
> to WEBP format using JavaScript and the Canvas API.  
> The app must feature:
> - Modern theme system (dark/light)
> - Side-by-side original and converted preview
> - Zoom and synchronized pan
> - File size comparison
> - Adjustable quality slider
> - Lossless mode
> - Fullscreen and theme controls
> - Info modal with detailed instructions and “Why WEBP?” explanation  
>
> Use only HTML5, CSS3, and JS (no frameworks).  
> All text and comments must be **in English**.  
> Produce clean, production-ready, visually appealing code.

---

### 📜 Metadata
| Field | Value |
|--------|--------|
| **App Name** | Image Converter to WEBP |
| **Tech Stack** | HTML5, CSS3, JS (Canvas API) |
| **Created by** | Osidach Vitaliy |
| **AI Assistant** | Claude Sonnet 4.5 |
| **License** | MIT |
| **Year** | 2025 |

---
