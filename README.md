# Frontend Mentor - Four card feature section solution

This is my solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).

## 📸 Screenshots

### Desktop
![Desktop Screenshot](images/desktop-screenshot.png)

### Mobile
![Mobile Screenshot](images/mobile-screenshot.png)

## 🔗 Links

- Solution URL: [My solution repo link](https://github.com/carodg09/four-card-feature-section-master)
- Live Site URL: [My live site link](https://carodg09.github.io/four-card-feature-section-master)

## 🛠️ Built with

- Semantic HTML5
- CSS Grid
- Flexbox
- Mobile-first workflow

## ✨ What I learned

This project helped me understand how to use `grid-template-areas` to build a cross-like layout. I also practiced combining Flexbox and Grid for responsive design.

```css
.grid-container {
    display: grid;
    grid-template-areas:
        ". team-builder ."
        "supervisor team-builder calculator"
        "supervisor karma calculator"
        ". karma .";
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: auto auto auto;
    column-gap: 2rem;
    row-gap: 0.5rem;
}