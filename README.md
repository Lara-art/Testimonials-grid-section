# Frontend Mentor - Testimonials-grid-section solution

This is my solution to the <a href="https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7"> Testimonials grid section on Frontend Mentor</a>.<br> Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview

### 💻 Screenshot

<table>
  <tr>
    <td style="width: 75%;"><img src="https://github.com/Lara-art/Testimonials-grid-section/blob/main/screenshot/Desktop.png" alt="Vista de Escritorio" style="width: 100%;"/></td>
    <td style="width: 25%;"><img src="https://github.com/Lara-art/Testimonials-grid-section/blob/main/screenshot/Mobile.png"  alt="Vista Móvil" style="width: 100%;"/></td>
  </tr>
</table>

### 🔗 Links

- Solution URL: [Github](https://github.com/Lara-art/Testimonials-grid-section)
- Live Site URL: [Deployed](https://lara-art.github.io/Testimonials-grid-section)

## My process

### 👩‍💻 Built with

- Web font import
- CSS custom properties
- Basic CSS reset
- Base typography settings
- Image styling
- Use of Flexbox
- Use of Grid -> And Grid-area-template
- Mobile-first design


### 📚 What I learned

With this exercise, I learned about the grid area and how do it in @media.


```css

.grid {
    display: grid;
    padding: 2rem;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
    gap: 1.8rem;
    grid-template-areas:
        "a a b e"
        "c d d e";
}

.item1 {
    grid-area: a;
}

.item2 {
    grid-area: b;
}

.item3 {
    grid-area: c;
}

.item4 {
    grid-area: d;
}

.item5 {
    grid-area: e;
}


@media (max-width:1000px) {
    .grid {
        grid-template-columns: 1fr;
        grid-template-rows: auto;
        gap: 1.8rem;
        grid-template-areas:
            "a"
            "b"
            "c"
            "d"
            "e";
    }
}

```
The strangest thing was the image position: absolute and his @media.

```css

.comillas {
    width: 115px;
    z-index: 1;
    position: absolute;
    right: 100px;
    top: 0px;
}


@media (max-width:1000px) {
    .comillas {
        width: 115px;
        right: 30px;
    }
}

```


## ✨ Author

- Github - [Lara](https://github.com/Lara-art)
- Frontend Mentor - [@Lara-art](https://www.frontendmentor.io/profile/Lara-art)

## 📂 Repository

- All the challenges done: [Github](https://github.com/Lara-art/My-Frontend-Mentor-Repository)
