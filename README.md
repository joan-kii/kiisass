## kiisass a simple layout grid framework)

**12 column grid**

## features

a basic **12 column grid** framework based on [960 Grid System](https://960.gs/).
**inspired by [tailwindcss](https://tailwindcss.com/)**.

## how to use

### display properties

- **[hidden | block | flex ]**: to specify display property.

### grid properties (continuar aquí)

- grid columns
  - **col-1** to **col-12** : to specify your column width. (how many column to span).
  - **col-[sm | md | lg | xl]-\***: specify the column width. based on the devise width \*(from 1 to 12).
  * column-order
    - **order-0 | .order-1 to .order-12**: will reorder your column based on the chosen index.
    - **order-[sm | md | lg | xl]-\***: specify the order based on the device width \*(from 1 to 12).
  * offset-column
    - **offset-0 | .offset-1 to .offset-12**: offset a column by (the index) number of column.
    - **offset-[sm | md | lg | xl]-\***: offset the column based on the device width \*(from 1 to 12).

### flex box properties

- flex-direction
  - **flex-[row | col ]**: change flex-direction property.
  - **[xs | sm | md | lg | xl]-[row | col ]**: change flex-direction property based on the device width.
- flex-wrap
  - **flex-[nowrap | wrap ]**: change flex-wrap property.
- justify-content
  - **justify-[start | end | center | between | around ]**: change justify-content property.
- align-[items | self]
  - **items-[start | end | center]**: change align-items.
  - **self-[start | end | center | auto]**: change align-self property based.
- align-content
  - **content-[start | end | center | between | around]**: change align-content property.

### padding and margin utilities

- padding

  - **p-1** to **p-16**: change the padding property.
  - **p[x | y]-\***: change the padding property on the desired axis.
  - **p[t | r | b | l]-\***: change the padding property on the desired side.

- margin

  - **m[x | y]-\***: change the margin property on the desired axis.
  - **m[t | r | b | l]-\***: change the margin property on the desired side.

### text utilities

- text colors
  - **text-[white | grey | secondary ]**: change text color property based on a predefined colors theme.
- text position
  - **text-[center | left | right ]**: change text-align property.

### background colors

- **bg-[primary-color | secondary-color | white | black | grey | dark-grey ]**: change background-color property based on a predefined colors theme.

### borders

- **border-none**: set border property to none.
- **border**: set border property to 1px solid #ccc
- **border-t**: set the border-top property.
- **rounded**: set border-radius property to 0.25rem.

## Built With

- [Sass](https://sass-lang.com/)

## Demo

> - [Cloning Farnam Street](https://joan-kii.github.io/kiisass/)

