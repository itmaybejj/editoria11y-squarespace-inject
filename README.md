# Editoria11y Accessibility Checker for SquareSpace
Code that can be added to a SquareSpace site to enable [Editoria11y](https://github.com/itmaybejj/editoria11y) for site editors.

Note that code injection is a premium feature on SquareSpace. As of my last check, this requires being at the "Commerce" or "Business" tier.

This script checks to make sure the person viewing the page can edit the page, then calls Editoria11y from the JSDelivr CDN. It includes some basic config to ignore alerts for blank alts on background images, and to disable the "Mark as OK" button (as there is no cloud backend to sync with on SquareSpace). Feel free to add your own config using any of the variables from the library itself.

## To use 
* Open the "Settings > Advanced > Code Injection" page in your site configuration.
* Paste the *entire contents* (including the "script" tags) of [code.html](https://github.com/itmaybejj/editoria11y-squarespace-inject/blob/main/code.html) into the "Footer" field.
* Press "Save" at the top left of the page. The preview will reload, and hopefully the Editoria11y toggle will appear.
