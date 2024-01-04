# 🎠 Carousel

![Screenshot_20231231_165135](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/8c76983f-1f51-4da0-9927-4bb312d05fbc)

# 📜 Description

* The component is built using Flexbox

```css
.carousel {
  background-color: #087f5b;
  width: 800px;
  margin: 100px auto;
  border-radius: 8px;
  padding: 32px 48px 32px 86px;
  display: flex;
  align-items: center;
  gap: 86px;
  position: relative;
}
```

* Padding shorthand: goes from TOP to LEFT
```css
padding: 32px 48px 32px 86px;
```

* Left and right buttons are placed using absolute positioning

```css
.btn {
  border: none;
  background-color: #fff;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  position: absolute;
  box-shadow: 0 12px 24px rgba(0,0,0,0.2);
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  top: 50%;
}
```

NOTE: top: 50% places the element at the center of parent element. Meaning top of the element will be at the center of the container.

```css
.btn-left {
  left: 0;
  transform: translate(-50%, -50%);
}
```

```css
.btn-right {
  right: 0;
  transform: translate(50%, -50%);
}
```

NOTE: transform: translateY(-50%) will move the element up by 50% based on the element itself. Meaning center of the element will be at the center of the container.

* To make the image bigger than the container scale is used

```css
img {
  height: 200px;
  border-radius: 8px;
  transform: scale(1.6);
  box-shadow: 0px 12px 24px rgba(0,0,0,0.1);
}
```

* Page navigation buttons are placed using absolute positioning

```css
.nav {
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translate(-50%, 32px);
  display: flex;
  gap: 8px;
}
```

NOTE: `transform: translate(-50%, 32px);` moves the component down by 32 pixels from the buttom and -50% centers it horizontally because left: 50% puts the left corner at the center of the container.
