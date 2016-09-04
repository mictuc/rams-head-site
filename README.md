Ram's Head Website v3.0

This is the repository for the Ram's Head Theatrical Society's website.
Version 3.0 was created by Michael Tucker Class of '18, Garrick Fernandez Class
of '19, and Rachel Gianforte Class of '18.

Table of contents:
1. Contact Information
2. Instructions to close repository
3. Instructions to edit website
4. Instructions to upload website
5. Instructions to give a user admin privledges

1. For information about the Ram's Head website, feel free to email Ram's Head's
current executive producer, webmaster, or Michael Tucker, mictuc@stanford.edu,
609-672-9724.

2. To clone this repository, open up terminal on your computer. If you do not
have git on your computer yet, you can install git by typing in the following
commands:
$ install git
..... add username?

To clone this repository, first change directories to the desired directory,
then clone the repository. Your commands will look like this:

$ cd /Users/your_account_name/some_file
$ git clone

Once cloned, you will find a rams-head-site folder in your specified directory.

3. To edit the website, you will need your favorite text editor. If you don't
have a specialized text editor installed already, you can use textedit (Mac) or
notepad (Windows), but they are not recommended. Instead, spend a minute to
install either Atom (atom.io) or SublimeText (sublimetext.com). These are great
free code editors and will make editing the site easy.

To open and edit files, you will need to go to the rams-head-site folder, and
right click (or control click) on the files you wish to edit, then select open
with, then choose your desired text editor. The file will open in the editor
and like word or pages, you can edit the text.

CHANGING INFORMATION
To make most information changes to the website, such as update show information
go into the js folder, and open up variables.js. This file is a condensed list
of the most commonly changed information on the site and updates the specified
information throughout the website. Find the values you want to change based on
the name of the variable, then just change the value inside the "". Note that
you can also add html code in these variables for more advanced formatting.
Once you make the appropriate changes, save the file, then open up the pages
that would display the changed information to make sure that the information is
correct.

CHANGING PICTURES
To change out pictures on the website, go into the rams-head-site folder, then
open up includes, then open up images. In here you will find all the pictures
used in the website. Once you find the picture you want to replace and have a
picture to replace it with, change the name of the new picture to match that of
the existing picture, and move the new picture into the appropriate folder. You
can replace/delete the old picture, or you can change the name of that picture
and leave it in the folder. Once the new picture with the correct name is in the
correct folder, open up the pages that include that picture in your browser to
check to make sure the picture updated correctly.

ADDING ROWS TO PAST SHOWS PAGE
This is the most complicated, relatively common change.
To add last season's shows to the past shows page open up past-shows.html, then
go down to line 99 where it says to "Copy and paste this section below, get rid
of the <!- and change the necessary information." Copy the code from lines 100
to 142, and paste it in line 143. Uncomment the code by getting rid of the <!-
and -> at the beginning and end of the code block, then change the information
you wish to change, save the file, then open the file in your browser to check
that the changes were saved.

MORE ADVANCED EDITS
If you wish to change text that isn't in the variables.js file, feel free to
open up the correct web page files and search for the text you wish to replace.
If you wish to make changes to a page's formatting or style, good luck! If you
know HTML and css you'll be fine. Feel free to reach out to the webmaster,
Michael Tucker or any other friend with HTML/CSS experience.

IMPORTANT: COMMIT AND PUSH CHANGES
Once you changes to the site, make sure you commit and push your changes back to
the repository. To do this go back to terminal and paste in the following
commands:

$ cd filepath_for_rams-head-site
$ git add -A
$ git commit -m "Enter a message here saying what you updated"
$ git push

The owner of the repository will have the ability to merge your commit to the
repo if they see fit. This will allow us to keep an up to date backup of the
website in case something goes wrong.

4. To upload the website to be seen online...

5. To give someone admin privledges to access the site and upload changes...
