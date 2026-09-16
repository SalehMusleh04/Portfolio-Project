# Saleh Portfolio

Portfolio website developed with HTML, CSS, and Bootstrap 5.

---

## Colors & Variables

The stylesheet defines the following CSS variables in `:root`:

* `--color-primary`: `#FF6B2B`
* `--color-bg`: `#FAFAFA`
* `--color-surface`: `#FEFEFE`
* `--color-surface-warm`: `#FFF7ED`
* `--color-text-main`: `#18181B`
* `--color-text-muted`: `#71718B`
* `--color-border`: `#E4E4E7`
* `--color-dark-surface`: `#27272A`
* `--color-dark-bg`: `#18181B`
* `--color-light-bg`: `#ffff`
* `--p-1`: `10px`, `--p-2`: `16px`, `--p-3`: `22px`, `--p-4`: `32px`
* `--m-1`: `10px`, `--m-2`: `16px`, `--m-3`: `22px`, `--m-4`: `32px`

---

## Sections & Content

### 1. Header
* **Logo**: `saleh` (with `leh` highlighted using `--color-primary`).
* **Navigation Links**:
  * Home (`#hero-section`)
  * Projects (`#my-projects`)
  * About (`#about-me`)
  * Contact (`#contact-section`)
* **Call to Action**: `Hire me` button linking to `#contact-section`.

### 2. Hero Section (`#hero-section`)
* **Tag**: "Available for work".
* **Title**: "Hi, I'm Saleh".
* **Description**: "Frontend web & Flutter Developer. I Focusing on building responsive web experiences and intuitive mobile apps - fast,clean, and accessible."
* **Buttons**:
  * "View my Projects" (links to `#my-projects`).
  * "Download CV" (downloads `./assets/cv/Saleh-CV.pdf`).
* **Stats**:
  * `5+` Projects done
  * `1y` Experience
* **Profile Image**: `./assets/imgs/profile-img.jpeg`.

### 3. Projects Section (`#my-projects`)
* **Heading**: "Portfolio" / "My Projects".
* **Projects**:
  1. **Youtube - Home Page**
     * **Image**: `./assets/imgs/youtube-page.png`
     * **Technologies**: `HTML`, `CSS`
     * **Source Code**: [https://github.com/SalehMusleh04/Youtube_HP](https://github.com/SalehMusleh04/Youtube_HP)
  2. **GradJob - My Graduation Project**
     * **Image**: `./assets/imgs/job-finder.jpg`
     * **Technologies**: `HTML`, `CSS`, `JS`, `React.js`, `Node.js`, `React Native`, `PostgreSQL`
     * **Source Code**: [https://github.com/QX-Devs/job-finder](https://github.com/QX-Devs/job-finder)
  3. **Food Delivery - Mobile App**
     * **Image**: `https://s3-figma-hubfile-images-production-cdn-cgi.figma.com/cdn-cgi/image/format=auto,quality=85,width=1600/hub/file/carousel/img/5c2dd049775555d2d4093e0c2dfeae5dce619d8d`
     * **Technologies**: `Dart`, `Flutter`
     * **Source Code**: [https://github.com/SalehMusleh04/Food-Delivery-App](https://github.com/SalehMusleh04/Food-Delivery-App)

### 4. About Me Section (`#about-me`)
* **Profile Image**: `./assets/imgs/profile-img.jpeg`.
* **Title**: "About Me" / "A bit about who I am".
* **Bio**: "I'm Saleh, a frontend developer and computer science graduate passionate about turning ideas into clean, functional digital products.I specialize in building responsive web interfaces and cross-platform mobile apps with a strong focus on clean code, seamless interactions, and performance.When I'm not writing code, I enjoy exploring new tech stacks and solving algorithmic challenges."
* **Stack & Tools**: `HTML`, `CSS`, `JS`, `DART`, `REACT`, `FLUTTER`, `BOOTSTRAP`.

### 5. Contact Section (`#contact-section`)
* **Heading**: "Get In Touch" / "Let's Work together".
* **Paragraph**: "I'm open to frontend and mobile development opportunities, freelance projects, or full-time roles. Whether building a responsive web app from scratch, crafting an intuitive mobile interface, or refining an existing codebase — let's connect."
* **Contact Information**:
  * **Email**: [saleh04.musleh@gmail.com](mailto:saleh04.musleh@gmail.com)
  * **LinkedIn**: [Saleh Musleh](https://linkedin.com/in/salehmusleh)
  * **GitHub**: [SalehMusleh04](https://github.com/SalehMusleh04)
* **Form Fields**:
  * Name (required)
  * Email (required)
  * Subject
  * Message (textarea, required)
  * Submit Button ("Send message →")

### 6. Footer
* `&copy; Saleh. All rights reserved. 2026`
* `Built with HTML & CSS`

---

## Dependencies & External Assets

* **CSS Framework**: Bootstrap `5.3.3` (`bootstrap.min.css`)
* **Icons**:
  * Google Material Symbols Outlined
  * Font Awesome `6.5.1`
* **Fonts**: Comic Relief, Source Sans 3 (via Google Fonts)

---

## Responsive Breakpoints in `style.css`

* **`@media (max-width: 992px)`**:
  * `.hero-section` and `.about-me-section` display in `column-reverse` with centered text.
  * `.my-projects` switches to single-column grid (`grid-template-columns: 1fr`).
  * `.contact-article` displays as a column with `40px 20px` padding.
* **`@media (max-width: 576px)`**:
  * `header` and `.main-btns` set to `column` direction.
  * `.profile-img` resizes to `250px` width and height.
  * `.form-row` shifts to a vertical layout (`flex-direction: column`) with inputs taking `100%` width.
  * `footer` displays in `column` layout with centered text.