## kiisass a simple layout grid framework

**12 column grid**

## features

a basic **12 column grid** framework based on [960 Grid System](https://960.gs/).
**inspired by [tailwindcss](https://tailwindcss.com/)**.

## how to use

### display properties

- **[hidden | block | flex ]**: to specify display property.
- **fluid-container**: to specify display to full width.
- **container**: to specify display to responsive width.

### grid properties 

- grid columns
  - **grid-1** to **grid-12** : to specify your column width. (how many column to span).
  - **[xs-w-full | sm-w-full | md-w-full | lg-w-full | xl-w-full]**: to specify display to grid responsive.
  - **[xs | sm | md | lg | xl]-grid-[1 - 12]**: specify the column width. based on the device width.

### flex box properties

- flex-direction
  - **flex-[row | col ]**: change flex-direction property.
  - **[xs | sm | md | lg | xl]-[row | col ]**: change flex-direction property based on the device width.
  - **[xs | sm | md | lg | xl]-flex-[row | col ]**: toggle flex-direction property based on the device width.
- flex-wrap
  - **flex-[nowrap | wrap ]**: change flex-wrap property.
- justify-content
  - **justify-[start | end | center | between | around ]**: change justify-content property.
- align-[items | self]
  - **items-[start | end | center]**: change align-items.
  - **self-[start | end | center | auto]**: change align-self property based.
- align-content
  - **content-[start | end | center | between | around]**: change align-content property.

### positioning

- **[top | left | bottom | right]-[1 - 32]**: change position property in 0.5rem steps.

### padding and margin utilities

- padding

  - **p-1** to **p-16**: change the padding property.
  - **p[x | y]-[1 - 16]**: change the padding property on the desired axis.
  - **p[t | r | b | l]-[1 - 16]**: change the padding property on the desired side.

- margin

  - **m[x | y]-[1 - 16]**: change the margin property on the desired axis.
  - **m[t | r | b | l]-[1 - 16]**: change the margin property on the desired side.

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

## Original Site

> - [Farnam Street](https://fs.blog/)
