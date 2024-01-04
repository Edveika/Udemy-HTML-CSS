# 📄 Pagination

![Screenshot_20231231_170617](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/105900d8-bfb9-4326-9ed7-ddc4fe127aa4)

# 📜 Description

* Component is built using Flexbox

```css
.pagination {
  display: flex;
  gap: 16px;
  justify-content: center;
  margin-top: 100px;
  align-items: center;
}
```

* Pages container is built using Flexbox

```css
.pages {
  display: flex;
  gap: 16px;
}
```

* Page elements are built using flexbox to center them

```css
.page {
  border: none;
  width: 30px;
  height: 30px;
  background-color: #fff;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  text-decoration: none;
  color: #343a40;
}
```

* When navigation button is hovered the icon turns white

```css
.nav:hover .nav-icon {
  stroke: white;
}
```
