# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 🧭 Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [🧭 Table of contents](#-table-of-contents)
  - [🪄 Overview](#-overview)
    - [The challenge](#the-challenge)
    - [🖼️ Screenshot](#️-screenshot)
    - [🔗 Links](#-links)
  - [🧱 My process](#-my-process)
    - [Built with](#built-with)
    - [💡 What I learned](#-what-i-learned)

---

## 🪄 Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- View the optimal layout depending on their device’s screen size (mobile and desktop)
- Read the blog preview content clearly with good visual hierarchy

---

### 🖼️ Screenshot

![Blog preview card screenshot](/design/active-states.jpg)

---

### 🔗 Links

- Solution URL: [Add your solution URL here](#)
- Live Site URL: [Add your live site URL here](#)

---

## 🧱 My process

### Built with

- Semantic **HTML5** markup
- **CSS3** custom properties
- **Flexbox** for layout
- **Mobile-first workflow**
- **Google Fonts (Figtree)**

---

### 💡 What I learned

Through this project, I practiced creating a **responsive card component** using clean, semantic HTML and CSS. I learned how to:

- Apply consistent spacing and typography using CSS variables.
- Add hover and active states for accessibility and interaction.
- Create responsive layouts that adapt from mobile (375px) to desktop (1440px) screens.
- Use shadows and borders to create depth and visual contrast.

Here’s a snippet I’m proud of:

```css
.card {
  background-color: var(--white);
  border: 1px solid var(--gray-950);
  border-radius: 1rem;
  box-shadow: 8px 8px 0 var(--gray-950);
  transition: transform 0.2s ease;
}
.card:hover {
  transform: translateY(-4px);
}

🚀 Continued development

In the future, I’d like to:

Add a dark mode toggle.

Implement this component using React or Tailwind CSS.

Experiment with CSS Grid to create a more modular card layout.


---

Would you like me to tailor the **author section** with your name (“Nthabiseng Moloi”) and your links (GitHub, LinkedIn, etc.) so it’s ready to publish?
```
