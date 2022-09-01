# CSS

- **td:nth-child(1)** is the first data containing icons. May also contain **.name** if you put it in <td> containing icon.
- **td:nth-child(2)** is the second data containing **.name** and **.dia**. Changing the max-width will change the maximum width it can stretch to (and is applied to **.name** and **.dia**, however might not seem like it if the dialogue is too short). For me and my desktop, 950px is the sweet spot. Not 100%, but almost and good enough. I found that setting it to 100% or 1000px will squish the icons slightly. This is the only compromise I found for now.
- **.dia** stands for "dialog/dialogue", it is the box/speech bubble containing the characters' words. Used as a class for `<p>` (paragraph) so that the border wraps around the text instead of the whole table.
- **desc** stands for "description". It was originally called **stagedir** (stage direction), but I changed it because "desc" is easier to remember for me. Other than that, it's the same as the original. Version 3 added padding to make it look better.
  
 ## In the Basic CSS File
  
 Confused on which **.dia** is which, and which **.left** is which? Here's a handy guide!
  
 **b**=**b**order (either borderless or bordered), **c**=**c**ustom color
  
  <img src="https://github.com/Clover-Zero/ao3-dialogue/blob/main/Explanation%20Image.png?raw=true">
