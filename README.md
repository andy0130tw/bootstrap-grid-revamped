# Bootstrap Grid System Revamped

Customize the grids according to [Material Design](https://material.google.com/) spec -- The very first step to start a CSS framework.

This grid system is based on [Bootstrap v4.0.0 Alpha 3](https://github.com/twbs/bootstrap/releases/tag/v4.0.0-alpha.3) and aimed to fit the guidelines of [Material Design](https://material.google.com/). The class names are identical and the exprience should be smooth if you used to be familiar with Bootstrap.

# Breakpoints

According to [the spec](https://www.google.com/design/spec/layout/responsive-ui.html):

> For optimal user experience, material design user interfaces should adapt layouts for the following breakpoint widths: 480, 600, 840, 960, 1280, 1440, and 1600dp.

Breakpoints picked up in this project are: **480 (xs), 600 (sm), 840 (md), 1280 (lg), 1440px (xl)**. Why we dropped some of the values ? Simply because that setting up too many breakpoints distracts the developers. The actual breakpoints is 20~30px *above* the values to accommodate different window border thicknesses like scrolls.
