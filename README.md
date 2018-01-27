# Canitia Jr.

A [Ghost](http://github.com/tryghost/ghost/) theme based on the Canitia theme (for Wordpress). It has the same look-n-feel but some feature differences due to their platform.

# Main Features
- Slider that shows featured posts (need the API to be enabled in Ghost Dashboard -> Labs -> API).
- UI optimised for different form factors (phone/tablet/pc)
- Ability to set your own publication icon and publication logo.
- Cover- and featured-post images for tags, author and single post pages.
- Navigation confgurable via navigation-section in Ghost panel.
- Responsive sidebar with Recent posts, Most used tags, Related posts which shows up on high-res (tablet+) displays.
- Author section at the bottom of each post includes avatar and user bio.
- Set social media links through Ghost settings panel (they will show in the footer)
- Translation support!
- Custom AMP, tag, author and error page designs.

![Canitia Jr. Theme](https://github.com/boumannm/canitia-jr/blob/master/canitiajr.png)

# Stuff used
Canitia Jr. uses the following libraries;
- Font Awesome 4.7.0
- Bootstrap v4 (beta)
- JQuery (3.1.x)

# Tested
This theme was used and tested on Ghost 1.0 using Chrome, Firefox and Edge as test browsers. Ofcourse i might still have missed some bugs so please report them through the issue tracker. 

# Release
This theme is currently marked 'stable'. Unless a new Ghost update introduces major new features or rewrites it's about as stable as can be ;).

# Use
- Download the package from the releases page and extract in your Ghost' 'content/theme' folder
- Restart your Ghost instance to see the new theme and apply it.

# Theme requirements
- Canitia Jr **requires** Ghost version **1.20.0** to install and work as intended. 
- Enable the Ghost API in the Ghost settings panel -> Labs -> Ghost API for the full featureset.

# Tested on:
The theme is tested on Microsoft Edge <Creators Update>, Microsoft Edge <Creators Update> (Mobile), Chrome 58 (mobile), Firefox 53.0.2 and Internet Explorer 11.

# Customization

## Google Analytics
To use Google Analytics, please parse the analytics code through Ghost's dashboard -> 'code injection'.

## Social
I've added the ability to add social links to the footer. You can include Facebook and Twitter profiles from the Ghost admin page (website-wide) and enter Twitter and Facebook urls for specific user profiles
