# 📫 WebApp Layout

![Screenshot_20231231_172734](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/304bb0af-cd8a-46d2-a547-95ebea48b8f8)

# 📜 Description

* This can be used to move last element all the way to the right without creating containers and using flexbox.

```css
button:last-child {
  margin-left: auto;
}
```

* Layout is built using CSS Grid

```css
body {
  font-family: sans-serif;
  color: #343a40;
  font-size: 24px;
  display: grid;
  height: 100vh;
  grid-template-columns: 80px 400px 1fr 250px;
  grid-template-rows: 80px 1fr;
  text-align: center;
  font-weight: bold;
}
```

* `nav` element takes up all vertical space

```css
nav {
  background-color: #343a40;
  color: #fff;
  grid-row: 1/ -1;
}
```

* Menu(the component with the buttons) takes up all horizontal space from 2nd column at the top of the page

```css
menu {
  background-color: #7048e8;
  color: #fff;
  grid-column: 2/-1;
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 0 40px;
}
```

* Emails lits is a vertical Flexbox container that allows for scrolling when there is a lot of emails

```css
section {
  background-color: #e9ecef;
  padding: 40px;
  display: flex;
  flex-direction: column;
  gap: 40px;
  overflow: scroll;
}
```

NOTE: `overflow: scroll;` - if elements no longer fit, scrollbar will appear
