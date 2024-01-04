# 🪑 Chair shop homepage

![Screenshot_20231229_154401](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/6b0dd229-a838-4581-a843-a193fcfbf524)
![Screenshot_20231229_154433](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/b6438321-9763-48f1-a079-60a7c0f00854)

# 📜 Description

* Each section is built using a CSS Grid that has 3 columns.

```css
.grid-3-cols {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 80px;
}
```

* Testimonials text box uses 2 Grid cells, 1 is left for the image

```css
.testimonial-box {
  grid-column: 2 / -1;
  align-self: center;
}
```

* The icons at the top have a round shape with light background around them. This is something I decided to add myself, think it looks clean.

```css
.feature-icon {
  stroke: #087f5b;
  width: 32px;
  height: 32px;
  margin-bottom: 24px;
  border-radius: 100%;
  background-color: rgba(156, 255, 194, 0.5);
  padding: 10px;
  align-content: center;
  justify-content: center;
}
```
