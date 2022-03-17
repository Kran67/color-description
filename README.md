# color-description
Color-Description turns a technical color representation into a human readable description.

## Installation
`npm install color-description`
## Usage

```js
import ColorDescription from 'color-description/dist/index.esm';

console.log(ColorDescription)

const cd = new ColorDescription('#ffffff');

console.log(cd.getDescriptiveList())
/**
 * pale, light, faded, delicate, glistening, bleached, neutral colorless, bright, briliant and high
 **/

cd.color = 'red';

console.log(cd.getDescriptiveList())
/**
 * saturated, strong, lush, ablaze, beaming, bold, brilliant, flamboyant, vibrant, vivid, loud, very saturated, warm, mellow, red and reddish
 **/
```

## Data Sources

### Color Psychology

- [colorpsychology.org](https://www.colorpsychology.org/)
- [Color Poster](https://graf1x.com/color-psychology-emotion-meaning-poster/)
- [Wikipedia](https://en.wikipedia.org/wiki/Color_psychology#:~:text=Color%20psychology%20is%20the%20study,as%20the%20taste%20of%20food.&text=Colors%20can%20also%20enhance%20the,are%20generally%20used%20as%20stimulants.)
  
### Named Primary, Secondary and Tertiary Colors

- [Named color wheel](https://en.wikipedia.org/wiki/Hue#24_hues_of_HSL/HSV)
- [Named color wheel 2](https://www.color-meanings.com/primary-secondary-tertiary-colors/)

### Color Adjectives

- [Adjective List](https://grammar.yourdictionary.com/grammar/word-lists/list-of-words-to-describe-colors.html)
- [Human Colors](https://github.com/vasilisvg/human-colours/blob/master/js/human-colours-en-gb.js)

### Descriptions
- [color meanings](https://www.canva.com/colors/color-meanings/)