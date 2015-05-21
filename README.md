# Bootstrap-Button-Color-Schemer

I usually find myself tweaking the colors of bootstrap buttons to match the scheme of the rest of my site. So to save time here is a block of CSS for your `application.scss` file. You can set the base color of each button style and have the border colors and hover colors generated automatically thanks to Sass.

## 1. Copy accross the new CSS rules
1. Copy the contents of `application.scss` into your local `application.scss` file

## 2. Change your base colors
Each type of button has a Sass variable where you set base color. For example, `$button-success-base-color` is set to a shade of green. You can change these colors to anything you like to match your theme.

## 3. Tweak the styles (if you want)
I've set this up using Sass color functions so that the `border-color` of the button is 5% darker than the base color. Same kind of thing happens with the :hover attribute too. You might find that these percentages need tweaking depending on the colors you're using so feel free to do so.
