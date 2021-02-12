# blogging-theme-adapt

This repo is an adaptation to the elegant hugo theme "hugo-primer" designed by Qiushi Pan, whose license has been attached. 

I made the following modifications to his design:

1. Added a google search functionality under the header 
2. Disabled the default math engine offered by hugo, and replaced it with mathjax 2.7 that offers auto line break, to circumvent the situation where the latex
rendered exceeds the margin
3. Other aesthetic modifications and changes to the default taxonomies to suit my own purposes 

## Details of the modifications

The modification relevant to point (1.) is shown in the last section of header.html, while that which is relevant to (2.) is shown in mathjax_support.html and header.html. Both modifications can be found in the layouts/partials. 
