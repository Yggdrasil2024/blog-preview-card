# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View a blog preview card with an illustration, publication date, title, summary and author information
- See the card styled with a bold yellow background, dark border, and offset shadow
- Experience a clean and readable layout that works well on mobile and desktop
- Notice subtle hover feedback on the article title and image

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/Yggdrasil2024/blog-preview-card)
- Live Site URL: Not deployed yet — open `index.html` locally in a browser to preview the project

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive layout styling
- Custom typography with the Figtree font family

### What I learned

This project helped me practice the basics of building a polished card component from a design mockup. I learned how to structure content with semantic HTML and how to use CSS variables to keep spacing and colors consistent.

I also improved my understanding of how layout details like borders, shadows, and rounded corners work together to create a more realistic UI. The hover effect on the title and image was a good reminder that small visual details can make a design feel more complete.

```html
<article class="card">
  <div class="card-img">
    <img src="./assets/images/illustration-article.svg" alt="Article illustration" />
  </div>
  <div class="card-body">
    <span class="card-badge">Learning</span>
    <h1 class="card-title">HTML &amp; CSS foundations</h1>
  </div>
</article>
```

```css
.card {
  width: 350px;
  background-color: white;
  border: 2px solid hsl(0, 0%, 7%);
  border-radius: 16px;
  box-shadow: 8px 8px 0 hsl(0, 0%, 7%);
}
```

### Continued development

In future projects, I want to keep improving my ability to:

- build responsive layouts with confidence
- create more refined hover and focus states
- work with typography and spacing to make designs feel balanced
- structure CSS in a cleaner and more reusable way

### Useful resources

- [Frontend Mentor Challenge](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS) - The original design and requirements
- [MDN Flexbox Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Helpful explanation of layout behavior and alignment
- [CSS-Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - A clear visual reference for common flexbox patterns

### AI Collaboration

I used GitHub Copilot during this project to help review the structure, suggest cleaner CSS patterns, and check that the implementation matched the challenge design. It was especially useful for refining the card layout, naming conventions, and small styling improvements. The tool helped speed up the process without replacing the actual learning and design decisions.

## Author

- GitHub - [Yggdrasil2024](https://github.com/Yggdrasil2024)
- Frontend Mentor - [@Yggdrasil2024](https://www.frontendmentor.io/profile/Yggdrasil2024)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenge and design. It was a great beginner-friendly exercise to practice HTML, CSS, and component styling.
