# gryd (barebones grid framework)

**12 column grid layout inspired by Bootstrap**

## features

a **12 column grid** css framework using grid layout and contains classes for spacing (similar to Bootstrap spacing classes)

## utilites

### spacing

- **margin**

  - **m-[0 | 1 | 2 | 3 | 4 | 5]**: setting margin to 0rem, 0.25rem, 0.5rem, 1rem, 1.5rem, and 3rem respectfully
  
  - **m[t | r | b | l]-[0 | 1 | 2 | 3 | 4 | 5]**: setting margin top, left, bottom, and right to 0rem, 0.25rem, 0.5rem, 1rem, 1.5rem, and 3rem respectfully
    
- **padding**

  - **p-[1 | 2 | 3 | 4 | 5]**: setting padding 0rem, 0.25rem, 0.5rem, 1rem, 1.5rem, and 3rem respectfully

  - **p[t | r | b | l]-[0 | 1 | 2 | 3 | 4 | 5]**: setting padding top, left, bottom, and right to 0rem, 0.25rem, 0.5rem, 1rem, 1.5rem, and 3rem respectfully

### Containers

- **container**

  - **container**: Has max width set to 95% with auto margins on the sides

  - **container-fluid**: Has a max width set to 100% with no margins

- **row and cols**

  - **row**: Declares a new row in whatever container its in. Has display set to flex and justify-content to space-between. This will set the "grid-gap" to 10px.

  - **col-[xs | s | md | lg | xl]-[1 / 12]**: declares a column in a row. The size values are for working with smaller screens. The numerical size is for how many columns the element should take up based on a 12 column grid.