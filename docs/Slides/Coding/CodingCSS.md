---
title: Coding CSS
version: 1.0.0
theme: mrdaviescs
footer: Coding - CSS
paginate: true
marp: true
size: 16:9
---

# Cascading Style Sheets
### **determining how a webpage looks**

---

## Linking a CSS file

creating a CSS file and linking this to your HTML

##### HTML file
```html
<link rel="stylesheet" href="mystyle.css">
```
##### CSS file
```css
body {
  background-color: lightblue;
}
```

---

## Basic CSS syntax

![bg right 90%  brightness:0.83 invert saturate:1.5 hue-rotate:230deg](https://www.w3schools.com/css/img_selector.gif)

``` css
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```
---

## Styling certain elements

We can give a certain tag an `id` in order to differentiate it from other tags of the same type like this: `id="para1"`

Then in our CSS code we can refer to this specific tag using the following selector:
```css
#para1 {
  text-align: center;
  color: red;
}
```
---

![bg 80%](https://static.docsity.com/documents_first_pages/2020/10/09/0ef0123fc8488fa7fada7afc1f327bf6.png)

