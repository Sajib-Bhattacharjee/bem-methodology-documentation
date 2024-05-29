<p align="center">
  <img src="images/logo__image.png" alt="BEM-Methodology logo image" title="BEM-Methodology logo image" width="100%" height="100%" />
</p>

<div align="center">

### `BEM Methodology`

</div>

### `Introduction`

```javascript
BEM stands for Block, Element, Modifier, and it is a methodology
for naming and structuring CSS classes ina clear and consistent
manner.

BEM helps in creating maintainable and modular code by providing a
naming convention that reflects the relationshipand purpose of
different parts of the code.
```

### `Why BEM?`

- It is a methodology helps
- to organize large CSS codes.
- It helps to avoid CSS class clashes
- A common rules for classes naming

### `Why BEM over the others?`

```javascript
No matter what methodology you choose to use in your
projects, you will benefit from the advantages of more
structured CSS and UI. Some styles are less strict and
more flexible, while others are easier to understand and
adapt in a team.

The reason I choose BEM over other methodologies comes
down to this: it is less confusing than the other methods
(i.e. SMACSS) but still provides us the good architecture
we want (i.e. OOCSS) and with a recognizable terminology.
```

### `Block`

```js
Standalone entity that is meaningful on its own.

The main component or module that represents a standalone
entity on the page. Blocks are    defined by a unique class
name that describes their purpose.
```

#### `Examples`

```
- header,
- container,
- menu,
- checkbox
- input
```

```js
.block {
  /* styles for the block */
}
```

### `Element`

```Js
A part of a block that has no standalone meaning and is
semantically tied to its block.

Parts of a block that have no standalone meaning and are
semantically tied to the block. Elements are indicated by
two underscores following the block name.

```

#### `Examples`

```
- menu item,
- list item,
- checkbox caption,
- header title

```

```js
.block__element {
/* styles for the element */
}
```

### `Modifier`

```js
A flag on a block or element. Use them to change
appearance or behavior.

Flags on blocks or elements that modify their
appearance or behavior. Modifiers are indicated
by two hyphens following the block or element name.
```

#### `Examples`

```
- disabled,
- highghted,
- checked,
- fixed,
- size big,
- color yellow

```

```js
.block--modifier {
  /* styles for the block modifier */
}

.block__element--modifier {
  /* styles for the element modifier */
}
```

### `BEM-Methodology Resources`

> **Reference**: https://docs.acfviews.com/templates/bem-methodology

> **Reference**: https://getbem.com/introduction/

##### `Collected By` - _`Sajib Bhattacharjee`_

---

<div 
align="center">

##### `All rights reserved by Sajib Bhattacharjee @2024`

#### `Created By-->`

**&copy;`-Sajib Bhattacharjee`**

**`Dedicated for 💕"Zahan" 💕`**

> > > > #### Thanks A Lot For Visiting...!!!

</div>
