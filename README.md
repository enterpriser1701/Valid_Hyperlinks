Valid_Hyperlinks
================
This python script is written for ArcGIS and will check to see if your geodatabase contains valid hyperlinks.

When working with a large number of records, it is easiest to just calculate a field with the path to files you are trying to link.  The problem when doing this is you will generate some links that are broken because the files do not exist.

This script serves two purposes.
  
  1.  If you expect there to be a file for every record, this script will help identify missing files.  Be it a missed spelled file or be it missing completely.
  
  2.  If you know that all the records do not have an associated file, this script can identify those missing files and you could add an "Unavailable File" place holder so the user knows it does not exist, and won't see and error message saying it can't find the file.
  
To use the script, you will need to modify the path to the feature class you want to run it on, and change the field names to match your specific needs.

I plan to add parameters that would allow you to select the path and fields.
