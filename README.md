# Custom CSS Styles Overview

This Markdown file provides an overview of the custom CSS styles defined in the provided CSS code.

## Resetting Default CSS

The following code resets the default CSS styles applied by the browser:

```css
/* Resetting default CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
/* Setting base font size */
html {
    font-size: 62.5%;
}
/* Navigation bar styling */
.navbar-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 0;
    width: 100%;
    margin: auto;
}

.list {
    display: flex;
}

.list li {
    list-style: none;
    font-size: 1.8rem;
}

/* Hero container styling */
.hero-container {
    display: flex;
    height: 500px;
    flex-wrap: wrap;
    position: relative;
}

.hero-container-left {
    flex: 1 1 500px;
    z-index: 1;
}

.hero-container-right {
    flex: 1 1 500px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.image {
    width: 350px;
    display: block;
    max-width: 100%;
    object-fit: cover;
    object-position: right;
}

/* Contact section styling */
.contact-heading {
    font-weight: 400;
}

.contact {
    text-align: center;
    font-size: 1.8rem;
    font-weight: 200;
}

.icons {
    display: flex;
    gap: 15px;
}
