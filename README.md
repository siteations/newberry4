# newberry4
Religious Change - Exhibit Selections - Tablet 4

These are cached files from the main exhibit, including the main sections:
⋅⋅* Divines and Natural Theologians
⋅⋅* Clergy and Laity
⋅⋅* Saints and Sinners
⋅⋅* Looking Forward

This includes the core pages (4-5 per section) and all enlarged image pages.

For local prep, the following has been done:

1. GENERAL REFERENCES
all general links/references files (css, jquery, etc.) have been collated into the 'public/common_ex' folder to avoid massive duplicates.
given that there have been two general find/replace actions run on all html files:
..* first all link for those references '[whatever the page_files]/stylesheets etc.' has been updated to ../public/common_ex
..* a few background images should have their 'http://publications.newberry.org/rcp-files/images/[files]' replaces with ../public/media

2. CSS
  The class 'viewmore' has been set to visibility: hidden is the file public/common_ex/common.css. This remove view of catalog links.
  
3. PER PAGE INTERNAL LINKS
  Links to enlarged images will be coded to link to the media folder (relative links) and the desired file.
  Link to neighboring pages will likewise be recoded to relative links.
  
4. NAVIGATION
  The local site will not include the book search option (as it relied on the mySQL database).
  All general links to the Newberry or Religious Change will redirect to the local index.
  All other index lists are being edited to match tablet contents, with relative local links.
  
5. MINOR EDITS -
  pdf readers, etc.
  


