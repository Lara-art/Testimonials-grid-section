# Frontend Mentor - Product preview card component solution

This is my solution to the <a href="https://www.frontendmentor.io/learning-paths/building-responsive-layouts--z1qCXVqkD/steps/669b079685c991733471a1bd/challenge/start"> Product preview card component on Frontend Mentor</a>.<br> Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview

### 💻 Screenshot

<table>
  <tr>
    <td style="width: 75%;"><img src="https://github.com/Lara-art/Recipe-page/blob/main/screenshots/Desktop.PNG" alt="Vista de Escritorio" style="width: 100%;"/></td>
    <td style="width: 25%;"><img src="https://github.com/Lara-art/Recipe-page/blob/main/screenshots/mobile.PNG"  alt="Vista Móvil" style="width: 100%;"/></td>
  </tr>
</table>

### 🔗 Links

- Solution URL: [Github](https://github.com/Lara-art/Product-preview-card-component)
- Live Site URL: [Deployed](https://lara-art.github.io/Recipe-page/)

## My process

### 👩‍💻 Built with

- Web font import
- CSS custom properties
- Basic CSS reset
- Base typography settings
- Image styling
- Use of Flexbox
- Mobile-first design


### 📚 What I learned

With this exercise, I learned something I had never done before: changing the color of the list item markers.


```css
li {
        list-style-type: inherit var(--color-Dark-Raspberry);
    }

    & ::marker {
        color: var(--color-Dark-Raspberry);
    }
}


```
I also had to set the image to position: absolute in media, so that it wouldn't be affected by the div it was placed in.

```css
@media screen and (min-device-width: 325px) and (max-device-width: 600px) {

    .card {
        border-radius: 0px;
        margin: 150px auto 0px auto;

        & img {
            position: absolute;
            top: 0;
            left: 0;
        }
    }
```


## ✨ Author

- Github - [Lara](https://github.com/Lara-art)
- Frontend Mentor - [@Lara-art](https://www.frontendmentor.io/profile/Lara-art)

## 📂 Repository

- All the challenges done: [Github](https://github.com/Lara-art/My-Frontend-Mentor-Repository)
