# Development-strategy

### Interface: Cli Section

<`ABU`

As a user, I should see a `container` with 2 `div`s
### `HTML`
 - There must be 1 `section` and its `class` is "cli"
 - There must be 1 `div` and its `class` is "container"
 - There must be a `grid`
 - There must be a `img` related to code.
 - Under that `container`, 2 `div`s.
 - Each `div` should have `h3` text and its `class` is "card"


### `CSS`
- `grid`
   >grid-template-columns: repeat(3, 1fr);

   >grid-template-rows: repeat(2, 1fr);


- `grid > *:first-chil`d
   >grid-column: 1 / span 2;

   >grid-row: 1 / span 2;
