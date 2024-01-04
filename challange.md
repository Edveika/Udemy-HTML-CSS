# 👟 Shoe site challange

![Screenshot_20231229_154622](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/6079109e-94c5-4888-9884-3f7a4202a29a)

# 📜 Description

* Layout is built using CSS Grid

```css
.flex-container {
  display: flex;
  gap: 40px;
  justify-items: center;
}
```

* Price component is built using Flexbox

```css
.flex-price {
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
  align-items: center;
  flex: 1;
  margin-bottom: 10px;
}
```

* Color picker component is built using Flexbox.

```css
.color-picker {
  margin-top: 20px;
  display: flex;
  gap: 10px;
}
```

* Sale component is a pseudo element positioned using absolute positioning.

```css
h1::before {
  content: "SALE";
  left: -35px;
  top: -20px;
  color: white;
  background-color: red;
  position: absolute;
  font-size: 18px;
  padding: 6px 5px;
  letter-spacing: 3px;
  width: 60px;
}
```

# 🕰️ Older versions

Initial/Flexbox Challange code can be found via commit history or Sections 2 and 3.
