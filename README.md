# Le App Frame

Attempts at perfecting the "app frame" look.

### Examples

- <a href="http://eddywashere.github.com/le-app-frame/fluid/content.html">Fluid</a>
- <a href="http://eddywashere.github.com/le-app-frame/fixed/content.html">Fixed Width</a>
- <a href="http://eddywashere.github.com/le-app-frame/max-width/content.html">Max-Width / Responsive</a>

### Features

- Fixed Header/Footer <small>*1</small>
- Proper 100% width row sections
- Scrollable content area
- Media query for max height to reset header/footer (footer is still sticky<small>*2</small>)
- Uses [hide-address-bar](https://github.com/scottjehl/Hide-Address-Bar) to normalize app frame in mobile browsers <small>*3</small>

<small>

 1. Fixed header/footer: Header and Footer both require their height to be set in the css.
 2. Sticky Footer: Footer will stay at the bottom of the screen if the page does not have enough content to push it lower. Footer requires its height to be set in the css.
 3. hide-address-bar is used because the app frame header and footer are not fixed on the initial scroll. After the first scroll, the header and footer css works as it should. By triggering this initial scroll event, we get the expected css behavior.

</small>

### Todo

- Remove [hide-address-bar](https://github.com/scottjehl/Hide-Address-Bar) hack
- Document the .l-body and .l-header height/padding magic

<hr>

<p>* Got something better? Fork it!</p>
