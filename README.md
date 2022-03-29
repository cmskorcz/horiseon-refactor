# Horiseon Social Solution Services
## Purpose
The purpose of this project was to take the code base of an already deployed application, and refactor its code into a more organized, accessable, and reusable format without altering the layout of the page. This was accomplished by replacing ambiguous elements, such as `<div>` for elements that were more specific to the content with which they were conveying (i.e. `<header>, <footer>`). These changes in sementics also improve accessablity for the site, as search engines and screen readers will be able to use these elements to provide more accurate information to the client. Images and icons within the application were also found to be without `alt` attributes, which could lead to screen reader being unable to explain important content to certain clients, as well as cause issues if images were unable to load. Because of this, `alt` tags were added to images and icons, with images being provided a brief description, and icons being left empty, as they did not provide much significance to the application's content. By providing an empty `alt` attribute, when a screen reader comes across an icon, it will simply skip to the meaningful content. 

## Changes
- Website `<title>` was changed to Horiseon Social Solution Services
- Semantic changes to `<div>` sections where they made sense (i.e. `<header>, <nav>, <section>, <article>, <footer>`).
- Added comments to break up HTML into sections.
- Added comments and reorganized stylesheet to a more logical flow.
- Updated stylesheet to account for changes in HTML semantics
  - `.header` and `.footer` classes were removed from both HTML and stylesheet, as `<header>` and `<footer>` tags were sufficient.
  - Removed unneccessary duplication from stylesheet for `<img>, <div>` and font color.
- Added `alt` attribute to images within `<article>` elements. Icons were given an `alt` attribute, but were left empty due to not bearing any real signifcance to the content.

## Deployed Application
The updated version of the application can be visited at the below link:
[Horiseon Social Solution Services](https://cmskorcz.github.io/horiseon-social-solution-services/).