# 🦸 HeroSection

![Screenshot_20231231_165428](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/b75dd0e2-d0fb-47a8-8c81-f321535c9204)

# 📜 Description

* Headerbar navigation bar is built using flexbox

```css
nav {
  display: flex;
  justify-content: space-between;
  font-size: 20px;
  font-weight: 700;
  padding-top: 32px;
}
```

NOTE: padding-top is used to avoid whitespace above image

* Header text container is placed using absolute positioning at the center left of the page

```css
.header-container {
  width: 1200px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```

* Background image is made darker using a grey gradient

```css
header {
  background-image: linear-gradient(rgba(34,34,34,0.6), rgba(34,34,34,0.6)), url(img/hero.jpg);
  background-size: cover;
}
```

`background-size: cover;` - The image covers the entire container, doesnt get cropped out
