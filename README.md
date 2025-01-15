# myportfolio.github.io:

INDEX.HTML-----------
This port-folio was made to represent my ideas and knowledge on the application of web development

index.html:

This file consist of all the elements of the website , besides broiler plate , opensans-serrif for text styling was imported from google fonts,
The header tag consists elements for creating menu option for user navigation with "a" function "onclick" which shall be described later 

Header:it consists of logo-text class and logo inside class logo-holder or "a" tags ,"a" tags accompanied by nav tag also named as class menu consisting of ul tags that contain inside the li tags , each li tags cosists of "a" tags links to their respective category , after that we have "a" tag named as mobile-toggle("a" tag class name) which we if peak into its javascript function 'onclick' we find it that changes 
the hamburger menu which was previously assigned via using svg changes to dot menu when media decreases down.

After that we have Section tag class named "hero container" consisting of two further divisions "hero-blue" and "hero-yellow" . The "hero-blue" class consist info about my experiences and skills and knowledge whereas "hero-yellow" consist of the slide show animation or the marquee animation.

After that we have "holder-blue" class displaying skills consisting of "right column" and "left-column" class

Proceeding we have section tag with id "projects" showcasing my recent works with embeded link in each image via using "a" tags.

STYLE SHEETS----------

Customized color variables were used the style sheets , initially the margin and padding for the context was set to zero , while styling it was kept in mind 
that when the width gets changed each of the html elements adjusts accordingly
by using "@media" method.

For animating the the slide show of icons "@keyframes" was used with transform for smooth slide show.

For displaying each context , "Flex", "centre" etc properties were used to make sure that each element of the html adjust with provided dimensions 

CSS NESTING was also used in the css sheet to carry out effective styling and increase code readiblity

In the class "bento-grid" "grid"  display property was used with nth childs for accessing each node to improve customisability.

JAVASCRIPT----------------

javascript was used to change the menu icon from hamburger to dots using class list property on "ul" list
