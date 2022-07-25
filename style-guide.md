# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Soft blue: hsl(215, 51%, 70%)
- Cyan: hsl(178, 100%, 50%)

### Neutral

                        - Very dark blue (main BG): hsl(217, 54%, 11%)
                        - Very dark blue (card BG): hsl(216, 50%, 16%)
- Very dark blue (line): hsl(215, 32%, 27%)
- White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size (paragraph): 18px

### Font

- Family: [Outfit](https://fonts.google.com/specimen/Outfit)
- Weights: 300, 400, 600



container {
    align-items: center;
    justify-content: center;
    display: flex;
    max-width: 360px;
    margin: 0 auto;
    
}
.card {
    background-color: hsl(216, 50%, 16%);
    padding: 18px;
    border-radius: 17px;
    text-align: center;
    margin: 01em;
    align-items: center;
    justify-self: center;
    display: flex;

}
.creator img {
    width: 20px;
    border-radius: 13px;
    display: flex;
    align-items: center;
}

.content {
    padding: 20px 10px;
}
.header-text h2 {
    color: white;
    padding-bottom: 16px;
}
.content-text p {
    color: hsl(220, 15%, 55%);
    Font-size: 18px;

}