# Round Progress Bar
A SCSS file for creating a round progress bar.

![](https://user-images.githubusercontent.com/6899797/80809181-69e84480-8bc1-11ea-8b25-cd925cc76d68.png)	

## Usage
Just compile the `progress-bar.scss` and add the resultant `.css` file to your project, using the following markup to create a Round Progress Bar:

For a 20% completed (with value inside):
```html
<div class="p20 progress-container">
  <div class="progress-bar"></div>
  <div class="progress-value">20%</div>
</div>
```

For a 45% completed (without value inside):
```html
<div class="p45 progress-container">
  <div class="progress-bar"></div>
</div>
```

Changing the number in `.p(number)` class for a value from 1 to 100 will change the completed percentage.

The provided SCSS file contains 5 variables at the top to customize the colors and the size of the Round Progress Bar:

```scss
$progress-bar-size
$progress-bar-bar-size
$progress-bar-color
$progress-bar-bar-color
$progress-bar-inner-color
```

## Playground
https://jsfiddle.net/ericscode/ne79tp0g/

## License
[The MIT License](https://github.com/erics-code/round-progress-bar/blob/master/LICENSE)
