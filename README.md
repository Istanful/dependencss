# DependenCSS
## YOU are the designer
If you're like me you do not want the CSS library you're using to make any design decisions.
This library contains only a grid system and nothing else. If you're coming from bootstrap it is very straightforward to use.

## Getting started
Download the <a href="https://raw.githubusercontent.com/Istanful/dependencss/master/dependen.css" download>CSS file</a> and link it in your html file.

Done!

### Responsiveness
DependenCSS is made to work great on phones, which is why you can combine some classes with
screen size constraints.

**These are the available screen sizes**:
- small: 768px and upwards
- medium: 992px and upwards
- large: 1200px and upwards

If none is provided, medium is assumed.

### Container
A container is used to constrain centered content to a specific width.
It has one width for each screen size. When the screen is larger than the width
it will not become any larger.
```html
<div class="container">
</div>
```

### Row
A row spans across the entire viewport and serves as a container
for columns.
```html
<div class="row">
</div>
```

### Column
A column divides a row into several sections.
The width of a column is expressed in n of 12.
For example a class of `.column-6` depicts a column
which occupies half the width of a row.
```html
<div class="row">
  <div class="column-10">
  </div>
  <div class="column-2">
  </div>
</div>
```

You can combine columns which screen sizes.
If you define a screen size the column will occupy the
entire row once the screen becomes smaller.
