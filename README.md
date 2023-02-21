# Hover-effect-navigation
Styling a navigation menu

This is an HTML and CSS code for a navigation bar with colored text effects on hover. The navigation bar is a vertical list of links, where each link is represented by an <li> element, containing an <a> element with an inline style that sets a custom property --clr to a specific color. The custom property is used to control the color of the text effect applied on hover.

The text effect is achieved by using the ::before pseudo-element on the <a> element. The content of the ::before element is set to the value of the data-text attribute of the <a> element, and the color is set to the value of the --clr custom property. The ::before element has a width of 0 and overflows the container. On hover, the width of the ::before element is set to 100% and a drop-shadow effect is applied to it using the filter property.

The HTML and CSS code is embedded in a single file, with the styles defined inside the <style> tags in the <head> section of the HTML document. The code uses the Poppins font, which needs to be imported separately.

Overall, this code demonstrates the use of custom properties, pseudo-elements, and transitions to create a visually appealing text effect on a navigation bar.



