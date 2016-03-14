# Reveal_Test
this is a redeploy of some IPython Slideshows to test the new format.

To change the slide widths the reveal.js file needs to be edited in the config section (about line 38).

To add verticle scrolling the reveal.css file needs to be edited in the .reveal .slides section (about line 309).  

Delete the line that says overflow: hidden;

Add the following two lines.

    overflow-x: hidden; 
    overflow-y: auto;

The verticle scroll bar may be present for all the slides up to the last one that needs verticle scrolling, after that it disapears.
