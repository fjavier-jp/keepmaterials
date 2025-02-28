# KeepComponents
Small project for the HTML KeepCoding module.

## File Structure
CSS files are stored in the css folder and consists of:
1. Components.
2. Main views and layouts.
3. Reset file.
4. Variables.

HTML files are stored in the root folder.

I include SVG files as a way of preserving svg tags, as well as prototype files which include preliminar drafts of the design.

## Base layout
I distinguised four screen sizes:
- xs (0-575px)
- sm (577-767px)
- md (768-1023px)
- lg (>1024px)

The base layout works as a grid with two columns where left navbar has a fixed width and header and footer fixed heights. The remaining space is filled by the main area where views are displayed.

## Sticky components
The left navbar, the whole header menu and the low header menu (under lg size) are positioned as sticky in order to always have access to them.

## Left navbar
Removes menu entries below lg size using display: none.

## Search icon in Search input
The only way I found to do this was adding both elements into one component and adjusting the icon's margins to place it over the textbox.

## SVGs
I optimized the page by adding only the needed icons directly as svg tags, not loading a whole kit from fontawesome.

## Form
Here I took a classic bootstrap approach. Since the form must be responsive, I used a container divided by rows and 12 columns in which every input group (label+input) occupies a cell in the wrapping/flexing/responsive grid.
I did not keep the original design, but it could be easily achieved with other col classes. Right now I only make use of 3, 4, 6, and 12 sizes.

## Images
For this preview all the images are loaded from https://placehold.co
A nice optimization in the topbar menu includes the alterning of images according to the screen size. For small screens I use the smaller image. For large screens, the larger.


# Conclusion
There are more details that I won't write about. Hope you enjoy this visual ASMR that is Responsive web design.
