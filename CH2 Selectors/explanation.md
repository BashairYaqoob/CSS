we can style paragraphs, phrases etc using selectors

1) if we select body, style applies everywhere
2) if we use *{}, its is universal selector and it selects everything.
3) if we select paragraph, style applies to all paragraphs
4) if we define a paragraph as a class, and we select that class using .classname{--code--}, style applies in that class
5) if we define a paragraph using id, and we select the id by #idname{--code--}, style applies in that para.
PROTIP: Use classes instead of ids in css

if we apply red to purple paragraph, it turns red.
BUT if we apply red to a CLASS that has grey elements, it won't turn red
BECAUSE CLASS HAS MORE SPECIFICITY THAN ELEMENT
you can check this using the inspect button in browser, the colors being overwritten would be cut.

some features of the body are inherited(fontsize) in the paragraphs, while others are not(like borders)

Specifity (low to high): elements like body, para---> class and attributes ----> ids
