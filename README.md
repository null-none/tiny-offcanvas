# tiny-offcanvas
Tiny and simple javascript offcanvas.

## Options
Option | Type | Default | Description 
------ | ---- | ------- | ----------- 
id | string |  | id DOM element 
data-position | string | left | special class can be added 
data-size | string | small | special class can be added 
data-transition | int | 300ms | opening and closing animation speed 

## Usage example

### Script
```javascript
var offcanvas = new Offcanvas;
```

### View
```html
<!-- Button trigger offcanvas -->
<button 
    class="offcanvas-btn"
    data-target="#offcanvas-left"
>
Default
</button>

<!-- Offcanvas -->
<div
    class="offcanvas-container"
    id="offcanvas-left"
    data-position="left"
    data-size="medium"
    data-transition="300"
    >
    <div class="offcanvas-wrapper">
        <i class="offcanvas-close"></i>
        ...
    </div>
</div>
```