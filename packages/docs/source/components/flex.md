# Flex

A one-dimensional layout component for arranging items in rows or columns.
Items flex to fill additional space and shrink to fit into smaller spaces.

## Direction

* row
* column
* row-reverse
* column-reverse

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <div class="ods-flex ods-flex--row">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
    <hr>
    <div class="ods-flex ods-flex--column">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
    <hr>
    <div class="ods-flex ods-flex--row-reverse">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
    <hr>
    <div class="ods-flex ods-flex--column-reverse">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
  </div>

  ```html
    <div class="ods-flex ods-flex--row">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
    <hr>
    <div class="ods-flex ods-flex--column">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
    <hr>
    <div class="ods-flex ods-flex--row-reverse">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
    <hr>
    <div class="ods-flex ods-flex--column-reverse">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
  ```
</figure>

## Align Items

* start
* end
* center
* stretch

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <div class="ods-flex ods-flex--column ods-flex--align-items-end">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item ods-flex-item--align-start">Three</div>
    </div>
  </div>

  ```html
    <div class="ods-flex ods-flex--column ods-flex--align-items-end">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item ods-flex-item--align-start">Three</div>
    </div>
  ```
</figure>

## Justify Content

* start
* end
* center
* space-around
* space-between

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <div class="ods-flex ods-flex--justify-items-center">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
  </div>

  ```html
    <div class="ods-flex ods-flex--justify-items-center">
      <div class="ods-flex-item">One</div>
      <div class="ods-flex-item">Two</div>
      <div class="ods-flex-item">Three</div>
    </div>
  ```
</figure>

## Wrap

## Shrink & Grow

## Reference

### Further reading

<ul>
  <li>
    <a href="https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox">
      MDN - Flexbox
    </a>
  </li>
</ul>
