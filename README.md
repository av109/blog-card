
## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [What I learned](#what-i-learned)




## Overview


### Screenshot

![](/assets/images/screenshot.png)


### What I learned

### What I learned

During this project, I learned several important concepts and techniques:

1. **CSS Flexbox**: I used Flexbox to create a responsive layout for the blog preview card. This allowed me to easily align and distribute space among the elements within the card.

```css
.user {
    display: flex;
    align-items: center;
    margin-top: 1em;
    gap: 10px;
}
```

2. **CSS Variables**: I utilized CSS variables to manage colors consistently throughout the project. This made it easier to maintain and update the color scheme.

```css
:root {
    --yellow: hsl(47, 88%, 63%);
    --white: hsl(0, 0%, 100%);
    --grey500: hsl(0, 0%, 42%);
    --grey900: hsl(0, 0%, 7%);
}
```

3. **Media Queries**: I implemented media queries to ensure the card is responsive and looks good on smaller screens. This involved adjusting the size of elements and font sizes.

```css
@media screen and (max-width: 420px) {
    article {
        max-width: 300px;
        height: 450px;
    }

    .but, p, h3, h3 + p, .user {
        font-size: 0.9em;
    }

    .user img {
        width: 30px;
        height: 30px;
    }
}
```

4. **Custom Fonts**: I learned how to include and use custom fonts in a project. I used the Figtree font for this project.

```css
@font-face {
    font-family: Figtree;
    src: url(assets/fonts/Figtree-VariableFont_wght.ttf);
}

body {
    font-family: "Figtree", sans-serif;
}
```

These learnings have helped me improve my CSS skills and better understand how to create responsive and visually appealing web components.
