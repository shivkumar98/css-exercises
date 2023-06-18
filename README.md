# 🟪 CSS Exercises

* This is a fork created while I work through The Odin Project. I created this fork on 18/06/2023

## 🧠 CSS Foundations

### 👨‍💻 Exercise 1: CSS Methods 👨‍💻 

#### 📜 Instructions 📜

* In this exercise, I'll practice adding CSS to HTML files using external, internal and inline CSS.

* I should only use type selectors for this exercise and use keywords for specifying colors.

* The properties I need to add to each element are:

1) `div`: a red background, white text, 32px font-size, center aligned, and bold

2) `p`: a green background, white text, and a 18px font-size

3) `button`: orange background and 18px font-size

* The desired outcome is:

![](/foundations/01-css-methods/desired-outcome.png)

#### 🟦 Commentatry

* I start working on exercise 1 [here](/foundations-solutions/01-css-methods/) 

* It starts off looking like:

![](2023-06-18-20-07-57.png)

* I create a CSS file ([styles.css](/foundations-solutions/01-css-methods/styles.css))

* I write the following CSS:

```css
div {
    background-color: red;
    font-size: 32px;
    color: white;
    text-align: center;
    font-weight: bold;
}
```

* I create the link to the CSS file in the HTML!

* I then write some internal CSS within the HTML file:

