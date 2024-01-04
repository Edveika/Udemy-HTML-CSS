# 📘 HTML Blog site

![Screenshot_20231229_152337](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/d89f498c-bfaf-4110-8218-1eb93a6a070f)
![Screenshot_20231229_152451](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/91d23eb7-24f9-421b-a111-7f44045c2dcb)

# 📜 Description

* Navigation bar in the header is built using Flexbox.

```css
.main-header {
  background-color: #f7f7f7;
  padding: 20px;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
```

* Yellow TOP sign is a pseudo element with absolute positioning

```css
h2::after {
  content: "TOP";
  background-color: #ffe70e;
  color: black;
  font-size: 16px;
  font-weight: bold;
  display: inline-block;
  padding: 5px 10px;
  position: absolute;
  right: -30px;
  top: -10px;
}
```

* Author component is built using Flexbox

```css
.author-container {
  display: flex;
  align-items: center;
  margin-bottom: 30px;
}
```

* Layout is built using CSS Grid. Recommended articles container size is 300 pixels, the main page takes the rest of the empty space.

```css
.container {
  display: grid;
  grid-template-columns: 1fr 300px;
  column-gap: 75px;
  row-gap: 60px;
}
```

* Like button is a button that uses absolute positioning.

```css
.like-button {
  font-size: 22px;
  padding: 20px;
  cursor: pointer;
  position: absolute;
  bottom: 50px;
  right: 50px;
}
```

