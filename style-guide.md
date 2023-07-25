# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Violet: hsl(257, 40%, 49%)
- Soft Magenta: hsl(300, 69%, 71%)

## Typography

### Headings

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 400, 600

### Body

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400

## Icons

For the social icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)
* {
    box-sizing: border-box;
    /* border: 1px solid white; */
}

*:hover {
    /* border: 1px solid white; */
}

body {
    margin: 0%;
    min-height: 100vh;
    background: hsl(257, 40%, 49%);
    border: 1px solid white;
    padding: 2em 0;
    color: white;
    font-family: 'Open Sans', sans-serif;
}

header {
    /* border: 1px solid white; */
    padding: 0% 10% 0 6%;
    margin-bottom: 3em;
}

header > svg {
    width: 10em;
}

h1 {
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
}

.desktop-bg {
    position: absolute;
    top: 0%;
    left: 5%;
    height: 100%;
    width: 095%;
    z-index: -9999999;
}

main {
    display: flex;
    justify-content: space-between;
    /* border: 1px solid white; */
    height: 40%;
    width: 100%;
    padding: 0% 15% 0 6%;
}

.first-flex {
    height: 070%;
    width: 50%;
}

.text-flex {
    width: 45%;
    padding: 3% 0;
    /* align-self: center; */
}

p {
    line-height: 1.5em;
    margin-bottom: 1.8em;
}

img {
    width: 100%;
    height: 100%;
    /* object-fit: contain; */
}

footer {
    display: flex;
    justify-content: flex-end;
    gap: 1.5em;
    padding: 0% 14% 0% 0%;
}

.socials {
    width: 2.5em;
    height: 2.5em;
    border: 1px solid white;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: .5em;
    cursor: pointer;
    transition: .5s ease-in-out;
}

.socials:hover {
    scale: 123%;
border: 1px solid hsl(300, 69%, 71%);
}

.socials:hover path {
    /* scale: 123%; */
    fill: hsl(300, 69%, 71%);
}

a {
    color: hsl(300, 69%, 71%);
    background: white;
    text-decoration: none;
    padding: .9em 3em;
    /* width: 100%; */
    border-radius: 25em;
    font-size: 0.9rem;
}

/* .illustration {
    background: white;
    border-radius: .5em;
    /* height: 30em; 
    width: 070%;
}

path {
    fill: white;
}

.black-top {
    width: 100%;
    height: 10%;
    position: absolute;
    top: 0%;
    left: 0%;
    right: 100%;
    background-color: black;
    z-index: 5;
    opacity: 0.5;
}

div.first-flex {
    position: relative;
    border: 1px solid white;
    width: 60%;

} */
* {
    box-sizing: border-box;
    /* border: 1px solid white; */
}

*:hover {
    border: 1px solid white;
}

body {
    margin: 0%;
    min-height: 100vh;
    background: hsl(257, 40%, 49%);
    border: 1px solid white;
    padding: 2em 0;
    color: white;
    font-family: 'Open Sans', sans-serif;
}

header {
    /* border: 1px solid white; */
    padding: 0% 10% 0 6%;
    margin-bottom: 3em;
}

header > svg {
    width: 10em;
}

h1 {
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
}

.desktop-bg {
    position: absolute;
    top: 0%;
    left: 10%;
    height: 100%;
    width: 090%;
    z-index: -9999999;
}

main {
    display: flex;
    justify-content: space-between;
    /* border: 1px solid white; */
    height: 40%;
    width: 100%;
    padding: 0% 15% 0 6%;
}

.first-flex {
    height: 070%;
    width: 50%;
}

.text-flex {
    width: 40%;
    padding: 3% 0;
    /* align-self: center; */
}

p {
    line-height: 1.5em;
    margin-bottom: 1.5em;
}

img {
    width: 100%;
    height: 100%;
    /* object-fit: contain; */
}

footer {
    display: flex;
    justify-content: flex-end;
    gap: 1.5em;
    padding: 0% 14% 0% 0%;
}

.socials {
    width: 2.5em;
    height: 2.5em;
    border: 1px solid white;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: .5em;
    cursor: pointer;
}

/* a {
    color: * {
    box-sizing: border-box;
    /* border: 1px solid white; 
} */
a {
    color: hsl(300, 69%, 71%);
    background: white;
    text-decoration: none;
    padding: .9em 3em;
    /* width: 100%; */
    border-radius: 25em;
    font-size: 0.9rem;
}

/* .illustration {
    background: white;
    border-radius: .5em;
    /* height: 30em; 
    width: 070%;
}

path {
    fill: white;
}

.black-top {
    width: 100%;
    height: 10%;
    position: absolute;
    top: 0%;
    left: 0%;
    right: 100%;
    background-color: black;
    z-index: 5;
    opacity: 0.5;
}

div.first-flex {
    position: relative;
    border: 1px solid white;
    width: 60%;

} */;


/* .illustration {
    background: white;
    border-radius: .5em;
    /* height: 30em; 
    width: 070%;
}

path {
    fill: white;
}

.black-top {
    width: 100%;
    height: 10%;
    position: absolute;
    top: 0%;
    left: 0%;
    right: 100%;
    background-color: black;
    z-index: 5;
    opacity: 0.5;
}

div.first-flex {
    position: relative;
    border: 1px solid white;
    width: 60%;

} */
