# newberry4
Religious Change - Exhibit Selections - Tablet 4

These are cached files from the main exhibit, including the main sections:
* Divines and Natural Theologians - 11 files
* Clergy and Laity - 22 files
* Saints and Sinners - 13 files
* Looking Forward - 13 files

This includes the core pages (4-5 per section) and all enlarged image pages, 59 pages total + new index.

For local prep, the following has been done:

1. GENERAL REFERENCES
all general links/references files (css, jquery, etc.) have been collated into the 'public/common_ex' folder to avoid massive duplicates.
* given that there have been two general find/replace actions run on all html files:
* first all link for those references '[whatever the page_files]/stylesheets etc.' has been updated to ../public/common_ex
* a few background images should have their 'http://publications.newberry.org/rcp-files/images/[files]' replaces with ../public/media

2. CSS
* The class 'viewmore' has been set to 'visibility: hidden' in the file public/common_ex/common.css.
* Any additional classes to adjust nav/menu options are at the end of the common.css file.
  
3. PER PAGE INTERNAL LINKS
* Links to enlarged images will be coded to link to the media folder (relative links) and the desired file.
* Link to neighboring pages will likewise be recoded to relative links.
  
4. NAVIGATION
* The local site will not include the book search option (as it relies on the mySQL database).
* All general links to the Newberry or Religious Change will redirect to the local index.
* All other index lists are being edited to match tablet contents, with relative local links.
* The image pages have an additional 'back' link to return to the narrative page and are styled to match the other breadcrumb links.

Each folder (for each tablet) will include a 'savedElements' folder that holds the navigation structures and consistently edit components for easy find/replace editing.
  
5. MINOR EDITS -
* pdf readers, etc. to be determined.

  


