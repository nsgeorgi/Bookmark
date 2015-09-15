#Implement moving an item of a bookmark bar.
Works with every browser.

Rules that i strictly followed during my implementation.


+ The bookmark bar shows the items horizontally.

+ Each item has a favicon and a text label.

+ The text label can be empty.

+ The width of each item is given by its favicon and text label, but cannot exceed a given maximum.

+ The items can be rearranged on the bar via drag and drop.

+ If the mouse cursor moves vertically within a given threshold, the dragged item can only be moved horizontally inside the bar.

+ If the mouse cursor moves vertically beyond the given threshold, the dragged item can be moved freely in both directions outside of the bar.

+ When moving an item inside the bar, a gap with the width of the dragged item shows its current target position.

+ If the position of the gap needs to be updated, the other items move to their updated position.

+ If the dragged item is moved outside of the bar, the gap collapses and the positions of the other items are updated.

+ If the item is moved back to the bar, the placeholder is inserted at the correct position and the item can again only be dragged horizontally.

+ If the user releases the item outside of the bar, the gap is inserted at the previous position, and the item moves back to that position.

+ Smooth animations to update the positions of the other items.

+ All the interactions should feel natural.

+ I used HTML, CSS, DOM and JS for this task because i didnt want to rely on any 3rd party library.
