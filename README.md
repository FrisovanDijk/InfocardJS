# InfocardJS - easy infocards

**Version:** 1.0
**License:** MIT

InfocardJS allows you to create easy infocards within your main body of content. For the default setting, you type {!text}[text] to get an infocard.
The infocard can be expanded and collapsed by clicking on it.

The library was written because I needed a cross-CMS solution to create infocards.

## Set-up
Just place infocard.min.js or infocard.js in your project and it's ready to use.

## Customizing
There are several variables to customise:

* regex: Change the pattern used to identify the infocard.
* arrow_style: Change the arrow styling. It supports both size and colour changes.
* divname: Choose which divs need to be scanned for infocards

## Example
The infocard collapsed:

<img src="https://www.frisovandijk.com/public/git/infocardjs/infocard_collapse.PNG" alt="Collapsed infocard" />

The infocard expanded:

<img src="https://www.frisovandijk.com/public/git/infocardjs/infocard_expand.PNG" alt="Expanded infocard" />

For a working example, see [this demo](https://www.frisovandijk.com/public/git/infocardjs/demo.html).

## What can't I do?
As far as I know, the only limitation is nesting infocards. Other than that, all HTML code should be accepted.

Oh, and it doesn't work on Internet Explorer.