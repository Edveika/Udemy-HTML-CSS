# 🪗 Accordion

![Screenshot_20231231_164845](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/43a63aad-0e6b-45ae-8e69-7a85584fc3c7)

# 📜 Description

* The accordion component is built using vertical Flexbox

```css
.accordion {
  width: 800px;
  margin: 100px auto;
  display: flex;
  flex-direction: column;
  gap: 32px;
}
```

* Title bar of the accordion is a CSS Grid that has 3 columns. Title bar text uses all empty space, number and the icon use only as much space as needed.

```css
.item {
  box-shadow: 0px 0px 32px rgba(0, 0, 0, 0.1);
  padding: 20px;
  display: grid;
  grid-template-columns: auto 1fr auto;
  column-gap: 24px;
  row-gap: 32px;
  align-items: center;
}
```

* Content that gets hidden by the accordion is placed at the 2nd column

```css
.hidden-box {
  grid-column: 2;
  display: none;
}
```

* If element has both `.item-open` and `.hidden-box` CSS rules, the content will be shown

```css
.item-open .hidden-box {
  display: block;
}
```

* If container has `.item-open` CSS rule, title and number will be green

```css
.item-open .title,
.item-open .number {
  color: green;
}
```
