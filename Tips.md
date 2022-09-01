# HTML

## Customization
You can change the class of the dialogue's paragraph (underlined) `dia left` into something else, as long as that class is defined in CSS. For example, `dia2 left2`. For more, look at CSS section below. Keep in mind that the class in HTML and CSS must be the **same**.

# CSS

## Explanations

- **td:nth-child(1)** is the first data containing icons. May also contain **.name** if you put it in `<td>` containing icon.
- **td:nth-child(2)** is the second data containing **.name** and **.dia**. Changing the max-width will change the maximum width it can stretch to (and is applied to **.name** and **.dia**, however might not seem like it if the dialogue is too short). For me and my desktop, 950px is the sweet spot. Not 100%, but almost and good enough. I found that setting it to 100% or 1000px will squish the icons slightly. This is the only compromise I found for now.
- **.dia** stands for "dialogue", it is the box/speech bubble containing the characters' words. Used as a class for `<p>` (paragraph) so that the border wraps around the text instead of the whole table.
- **desc** stands for "description". It was originally called **stagedir** (stage direction), but I changed it because "desc" is easier to remember for me. Other than that, it's the same as the original. Version 3 added padding to make it look better.
  
 ## Notes
 - **dia left** and **diacb leftc**, **diab left** and **diac leftc** are actually the same thing, just with different colors, hence separate codes. The same goes for **dia2 left2** and **dia2c left2c**. If you want each character's speech bubble to have different colors, you'd have to do this as well.
- If you change the color of the background, make sure to set font color (color: #colorhexcode) like I did, or else it'll look different with different site skins, and that may cause problems.
  
 ## Which is Which?
  
 Confused on which **.dia** is which, and which **.left** is which in [basic CSS file](https://github.com/Clover-Zero/ao3-dialogue/blob/main/basic-css.css)? Here's a handy guide!
  
 **b**=**b**order (either borderless or bordered), **c**=**c**ustom color
  
  <img src="https://github.com/Clover-Zero/ao3-dialogue/blob/main/Explanation%20Image.png?raw=true">
  
 ## Customization
- Change **max-width** and **min-width** in **td:nth-child(1).** This means changing the icon's size. If you wish to make the icons smaller or bigger in smaller screens (but smaller than **max-width**), change **min-width**. I recommend having **max-width** at 128px as it's the sweet spot (for me, personally).
- Change the colors, such as border color, background color, and (font) color, as pointed by the comments in CSS.
- Change the name of the classes (such as **.dia** ) to your liking.
