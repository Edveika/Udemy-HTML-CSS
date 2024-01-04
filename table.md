# 📈 Table

![Screenshot_20231231_172435](https://github.com/Edveika/Udemy-HTML-CSS/assets/113787144/92c4f385-7cda-42d8-8241-2d7450e59038)

# 📜 Description

* Built using `table` element

```HTML
<table>
      <thead>
        <tr>
          <th>Chair</th>
          <th>The Laid Back</th>
          <th>The Worker Bee</th>
          <th>The Chair 4/2</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>Width</th>
          <td>80 cm</td>
          <td>60 cm</td>
          <td>220 cm</td>
        </tr>
        <tr>
          <th>Height</th>
          <td>100 cm</td>
          <td>110 cm</td>
          <td>90 cm</td>
        </tr>
        <tr>
          <th>Depth</th>
          <td>70 cm</td>
          <td>65 cm</td>
          <td>80 cm</td>
        </tr>
        <tr>
          <th>Weight</th>
          <td>16 kg</td>
          <td>22 kg</td>
          <td>80 kg</td>
        </tr>
      </tbody>
    </table>
```

* `<th>` - table head, makes the text bold

* `<td>` - table data, normal text

* `thead th` elements are styled to be green, not thead itself

```css
thead th {
  background-color: #087f5b;
  color: #e6fcf5;
  width: 25%;
}
```

* Odd and Even table rows have different colors

```css
tbody tr:nth-child(odd){
  background-color: #f8f9fa;
}
```

```css
tbody tr:nth-child(even) {
  background-color: #e9ecef;
}
```

* Border collapse disables gaps between borders

```css
table {
  border-collapse: collapse;
}
```
