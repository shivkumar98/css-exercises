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

* This generates the following output:

![](2023-06-18-20-16-12.png)


* I then add an internal CSS rule for the `p` element:

```css
<style>
    p {
    background-color: green;
    color: white;
    font-size: 18px;
    }
</style>
```

* This generates the following output:

![](2023-06-18-20-18-14.png)

* I apply inline style to the button element:

```html
<button style="background-color: orange; font-size: 18px;">Inline Method</button>
```

* This generates the following output:

![](2023-06-18-20-19-55.png)

### 👨‍💻 Exercise 2: Class and ID Selectors 👨‍💻 

#### 📜 Instructions 📜

* There are several elements in the [HTML file](/foundations-solutions/02-class-id-selectors/index.html), which I will add either class/id attributes as noted in outcome image below:

![](/foundations-solutions/02-class-id-selectors/desired-outcome.png).

* The properties which I need to add to each element are:

1) All odd numbered elements: a light red/pink background, a list of fonts containing `Verdana`, `DejaVu Sans` with `sans-serif` as a fallback

2) The second element: blue text and a font-size of 36px

3) The third elemenent: in addition to first property, add a font-size of 24px

4) The fourth element: a light green background, font-size 24px and bold

