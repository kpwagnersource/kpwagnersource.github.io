# Perks Flipper Demo for SAI Website

[Live Demo on Github](https://kpwagnersource.github.io/)

This layout uses nested lists styled as flexboxes. There ends up being a lot of markup with this method--may not be the best. The images are set within the list-item elements, and those list-item elements are styled with overflow:hidden.

The animation is incomplete. The overflow:hidden property is not functioning correctly with the rotateY animation (i.e. the part of the image that should be hidden show while the image is rotating.) Also, the "flip card" should have a 3d effect to it, which is currently not working.

[Flip Card Tutorial on W3 Schools](https://www.w3schools.com/howto/howto_css_flip_card.asp)

[This grid layout](https://www.w3schools.com/howto/howto_js_image_grid.asp) and its [responsive counterpart](https://www.w3schools.com/howto/howto_css_image_grid_responsive.asp) would require less markup. But these layouts would not have equal height for each column, and some additional markup is required for the flipper effect.
