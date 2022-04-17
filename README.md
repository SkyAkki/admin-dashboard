# admin-dashboard
1. Tip
https://discuss.codecademy.com/t/can-you-apply-multiple-stylesheets-to-a-single-page/369792/8
It is better to combine all CSS files into one rather than having multiple CSS files.
{
    When linking multiple CSS files, the styles are applied in the order that they are linked in the HTML document.This can cause similar rules to overwrite the rules from the previously linked files.
}
{
    How CSS cascade depend on when they are called, and where they are called. CSS can be in five places; external, (called from the <link> element), internal, (within the <style> element), in-line, (within the actual content), render agent, (declared by ones browser, such as Firefox or Chrome), or user defined, (created by the end user).

    The first style to cascade, is the user agent. In the absence of any other style-sheet, the user agent defines how things will appear.

    Second will be internal & external style-sheets. They will override the user agent, (and each other). The order of cascade, will be the order of appearance in the <head> element, the last one having final override.

    Third will be inline styles.

    Finally, whatever CSS the end-user has decided is best for themselves, (usually because of accessibility concerns), will override all that came before.
}


2. Question
Which is a better practice, using <img> in list item for icons or giving a class to list item and and change list-style-image in the CSS?