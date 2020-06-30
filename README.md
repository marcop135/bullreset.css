# bullreset.css

A _bulldozer_ CSS file that first resets, than normalizes, and finally makes responsive all the properties for all the elements within an HTML page.

When `!important` is not enough to survive in the cascade, you may use this project to have peace of mind :)

## How to use it

### Soft reset

1. Replace references to .bullreset with the name of your favourite class
2. Append your favourite class to HTML element
3. Write your styles safely

### Hard reset

1. Replace references to .bullreset with the name of your favourite class
2. Append your favourite class to HTML element
3. Overwrite all `;` with `!important;` and write all your CSS using `!important` for each property.

## When to use it

- Reset all styles very quickly
- Reset external plugin styles
- Reset external libraries styles (e.g. Bootstrap)
- Reset styles inside a container
- Start from stratch when touching legacy code

## Modern browsers (No IE)

Just use `all: initial`

Read more on [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/all)

## License

The MIT License (MIT) - [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT "The MIT License")

## Todos

- Add CodePens
- Add some screenshots
- Use Autoprefixer
- Use Sass modules
- Add browser compatibility list
- Add extensive CSS form elements support
- Add logo
- Add npm
- Add JSDelivr
