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

### To update exhibition files two options:

1. use git (single command, < minute per update)
2. download full folder, unzip, and replace original folder (depends on wifi speed)

#### Because updates will be distributed, it is better to grab all files, but should you want to only update specifics (after a clean install), you can see what has changed by exploring the commits. 
* Per commit, it will show the files & lines that have changed. 
* Figure out what was last updated (by date) and find commits after that date.
* Note, in each commit, the changed files. 
* Really, it's easier to just bulk download everything, unzip and replace only the changed files.


### As the download option is easy, but time consuming, the following guides non-git users through git based updating:
* download and install git on each machine (do this only once) from [the git site](https://git-scm.com/) or for more ui options [the github site](http://windows.github.com)
* instead of downloading a zip, navigate to where you want the files to sit on your desktop and right click for the option 'open git bash here'
* with git bash's command line interface open type in (for cloning this respositiory) 'git clone https://github.com/siteations/newberry4'
* this will download the folder of materials for you, akin to the manual zip download, so this only needs to be done once
* after the folder is downloaded, using git bash, navigate inside by typing 'cd newberry4' and notice the hidden '.git' folder
* at this point you should be parallel to the main 'index.html' file
* this is where you will want to be for updates. . . (so when updating, navigate here through your normal graphic user interface and right click, open git bash)
* to update with git bash, simply type 'git pull origin master'
* this command checks in with the git repository, looks at the commit history, and automatically downloads anything that has been updated

the original install is around 10 minutes, 
the clone is maybe 10-20 minutes akin to the typical download, 
the pull for updating usually takes less than 30 seconds to update materials

#### that's it - download git, clone the repository once, and continually update with 'git pull origin master'

* for addition git commands, see the cheatsheet and docs at https://git-scm.com/docs

  


