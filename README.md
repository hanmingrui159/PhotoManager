# PhotoManager
This is a photo management program implemented through Java and JavaFX for CSC207 2017Fall<br /> <br /> 

FEATURES<br /> 
-User can manage photos by tags<br /> 
-Add/delete tags to each photo and the name changes are recorded automatically. <br /> 
-Filter photos by their tags, view the log history of name changes, and revert a photo back to its past tags. <br /> 
-Open a root directory to scan in the tags associated with the photos under the directory, and view the photos under the directory
<br /><br />  

SET-UP<br /> 
-1. uncompress the zip file<br />
-2. open the new project folder "photomanager" in an IDE, run "Main" class; or cd into the "src" directory of the project folder, enter "javac Main.java" to compile the program, this should create a "Main.class" file, enter "java Main to run the program"
<br /><br />

USAGE<br />
- "File" button provides options for opening a new photo, view log history, and select a directory to view and include tags of the photos into tag list(on the right)<br />
- "Create Tag" button creates a tag which can be applied to photos<br />
- "Add selected tags" button add selected tags from tag list (on the right) to the current photo's tags<br />
- "Remove selected tags" button removes selected tags (on the left) from the photo<br />
- "Delete selected tags" button deletes selected tags (on the right) from the available tags list<br />
- "More Picture" button provides the options of moving a picture to a different directory, change the picture back to its old names(which possibly changes the directory of the photo), and open the parent directory of the current photo<br />
- "More Tag" button provides the option of filtering photos by their tags<br />
