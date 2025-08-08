# Amazon KDP Landing Page System

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white)

## Preview
<img src="https://github.com/YisusDU/ebac-practice-m37/blob/main/assets/img/preview-AMZ.webp">

---

## 📋 Purpose and Scope

This project is a static **Landing Page** system in HTML for an Amazon Kindle Direct Publishing (KDP) course, built with a **modular SCSS architecture** and optimized for converting visitors into students.  

The page is designed as a **marketing funnel** with educational content, social proof, visual elements, and strategically placed Call-To-Actions (CTAs).

Includes:

- **Modular structure** separating HTML, styles, and assets.
- **Performance optimization** for faster loading times.
- **Consistent typography and styles** aligned with the course branding.
- **Compatibility and accessibility** through semantic HTML5.

---

## 🏗 System Architecture Overview

The system follows a **modular architecture** that separates:

1. **Content Structure** – Semantic HTML with defined sections.
2. **Visual Presentation** – SCSS styles compiled into a single CSS file.
3. **Static Assets** – Images, videos, and fonts.

**Key files:**

- `index.html` → Structure and content.
- `css/main.css.map` → Compiled style map for debugging.

---

## 📑 Content Structure and User Journey

The conversion funnel is composed of **8 main sections**:

| Section           | Main Objective                          |
|-------------------|------------------------------------------|
| `firstScreen`     | Hero + Primary CTA                      |
| `guarantee`       | Build trust with video                  |
| `collab`          | Display partnerships and credibility    |
| `additionalInfo`  | Benefits and support                    |
| `qualification`   | Social proof                            |
| `product`         | Course preview                          |
| `lastCall`        | Final CTA                               |

---

## 🎨 SCSS Architecture and Build System

The style system is built with **modular SCSS** and compiled into a single CSS file for better performance.

**SCSS Modules:**

| Component         | Purpose                                 | Location         |
|-------------------|-----------------------------------------|------------------|
| Color variables   | Brand consistency                       | `_vars.scss`     |
| Layout mixins     | Responsive structure                    | `_mixins.scss`   |
| Section styles    | Component-specific styling              | `_components.scss` |
| Base layout       | Global structure                        | `_layout.scss`   |

**Brand colors:**
- **Primary**: `#dc7900` (orange)
- **Secondary**: `#c08200` (gold)
- **Tertiary**: `#e12d00` (red)

---

## 🔤 Typography

The system integrates **4 Google Font families** for visual hierarchy and readability, using **CDN preconnect** to improve loading times.

---

## 🖼 Asset Integration Pattern

File structure in `assets/`:

- **Images** → `assets/img/` (PNG, SVG, WebP)
- **Videos** → `assets/videos/` (MP4 with autoplay)
- Semantic and descriptive naming conventions (e.g., `amz-poster-img.png`, `amz-edit-garanty.mp4`).

---

## 🔌 System Integration Points

**External services:**

| Service         | Purpose              | Implementation                   |
|-----------------|----------------------|-----------------------------------|
| Google Fonts    | Typography           | CDN preconnect + stylesheet       |
| HTML5 Video     | Media playback       | `<video>` element with fallback   |
| Semantic HTML   | Accessibility        | ARIA + semantic structure         |

**Performance optimizations:**
- Font preconnection.
- Video compression and autoplay optimization.
- CSS source mapping for debugging.
- Semantic HTML5 for SEO.

---

## 🚀 Development and Deployment

1. Edit SCSS in the `scss/` folder.
2. Compile SCSS into optimized CSS.
3. Ensure assets and fonts are loaded correctly.
4. Deploy to a static server or GitHub Pages.

---

## 📂 Relevant Source Files

- `index.html` – [Lines 1–235]
- `css/main.css.map` – [Line 1]

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

> [!Note]
> You can check the full documentation <a href="https://deepwiki.com/YisusDU/ebac-practice-m37">-here-</a>
