# X (Twitter) UI Clone

[![Live Demo](https://img.shields.io/badge/demo-online-green.svg?style=for-the-badge&logo=appveyor)](https://x-clone-tailwind.vercel.app/)

A frontend clone of the X web interface built from scratch. I created this project to get hands-on practice with building complex, highly responsive layouts using Tailwind CSS.

## 🛠️ Tech Stack
* **HTML5:** Semantic structure
* **TailwindCSS v4.2:** For all styling, hover states, and responsive breakpoints
* **Deployed on:** Vercel

## 💡 Features
* **Pixel-Perfect Desktop Layout:** Replicates the specific fractional column widths similar to real X desktop app.
* **Fully Responsive:** The layout completely changes based on screen size (the right sidebar disappears on smaller screens, and the left navigation collapses into an icon-only menu).
* **Sticky Navigation:** Sidebars stay fixed while the main middle feed scrolls naturally.

## 🧠 What I Learned
Building this was a massive exercise in CSS Flexbox and responsive design. Some specific challenges I tackled:
* Managing layout shifts across `sm`, `md`, `lg`, and `xl` breakpoints without breaking the internal padding of elements.
* Mixing fixed pixel widths with fluid percentages to prevent the main content feed from getting "squished" on smaller laptops.
* Using Tailwind's configuration to manage state changes (like showing/hiding specific text spans on different devices).

## 💻 Running it locally

1. Clone this repo:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/x-clone-tailwind.git](https://github.com/YOUR_USERNAME/x-clone-tailwind.git)

## 🪞Screenshots of Project

![alt text](/screenshots/image.png)

![alt text](/screenshots/image-1.png)

![alt text](/screenshots/image-2.png)
