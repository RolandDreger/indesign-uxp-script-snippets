# InDesign UXP Scripting Snippets
Some InDesign uxp scripting samples.

## [Dialog](https://github.com/RolandDreger/indesign-uxp-script-snippets/tree/main/Dialog)
- [Alert Dialog](https://github.com/RolandDreger/indesign-uxp-script-snippets/blob/main/Dialog/alert.idjs)

&nbsp;
# Resources

## Adobe
- [JavaScript Reference](https://developer.adobe.com/indesign/uxp/uxp/reference-js/)
- [UXP Scripting Samples](https://github.com/AdobeDocs/uxp-indesign/tree/main/src/pages/reference/uxp-scripting-samples)
- [Spectrum UXP Reference](https://developer.adobe.com/indesign/uxp/uxp/reference-spectrum/)
- [Spectrum Web Components](https://opensource.adobe.com/spectrum-web-components/)
- [Spectrum Web Components (Storybook)](https://opensource.adobe.com/spectrum-web-components/storybook/)

&nbsp;
# Articles
- [InDesign v. 18 Ships with Scripting Powered by UXP](https://blog.developer.adobe.com/indesign-v-18-ships-with-scripting-powered-by-uxp-53e5dc008f17)

&nbsp;
# Community
- [Adobe Support Community](https://community.adobe.com/t5/indesign/ct-p/ct-indesign?page=1&sort=latest_replies&lang=all&tabid=all&topics=label-uxpscripting)

&nbsp;
# Tutorials
## indesignblog.com (Gregor Fellenz)
- [Quickstart UXP Scripting](https://www.indesignblog.com/2022/11/quickstart-uxp-scripting/)

&nbsp;
# What not works
A incomplete list of what is not yet possible with UXP scripting (at the moment) and has already caused me headaches so far. 🤕
## HTML
- `template` element

## CSS

## JavaScript

- Assign a value to custom property: `Element.style.setProperty('--custom-property', 'value')`
- Get content from template element: `Template.content.cloneNode(true)`
- `new DOMParser()` nope (DOMParser is not defined)