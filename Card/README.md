Card is a template for generating cards in a grid or row layout on a page. Works well with the Citizen skin.


# Parameters

## Formatting parameters
count
- The number of cards generated
  
column
- The number of cards on a single row (max 6)
  
wide
- Allows the grid to extend beyond page width in widescreen (yes or no)
  

## Content parameters
title(n)
- The title text on card (n)
text(n)
- The content text on card (n)
bottom(n)
- The text on the bottom section of card (n). Usually used for actionable items like links.
page(n)
- The page linked by the button on card (n). Only use it when there is only one action.
pagetext(n)
- The text displayed on the button on card (n)
bylinetop(n)
- The byline text above the title on card (n)
bylinebottom(n)
- The byline text below the title on card (n)

## Styling parameters
colorbg(n)
- The background color of card (n)
colortext(n)
- The text color of card (n)
colorbyline(n)
- The color of the byline on card (n)
colortitle(n)
- The color of the title on card (n)
colorbgbottom(n)
- The background color of the bottom section of card (n)
colorbottom(n)
- The text color in the bottom section of card (n)
colorbgbutton(n)
- The background color of the button on card (n), note that due to templating restrictions, the button text will always be grey. Please ensure there is enough contrast between the background color and the text.
