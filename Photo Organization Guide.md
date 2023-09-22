# Photo Organization Guide #

## PhotoMove2 ##
Use this app to bulk move photos from one folder to another and create new folders based on EXIF data separated by YR-MTH. Can also choose to move files without any EXIF data to a separate folder for manual editing of dates later. This works well as a quick method to bulk move many files at once to new folders, 10k plus files for example.


## Bulk Renaming Utility ##
Rename files based on the EXIF data.
Box 2 Name - Remove
Box 8 Auto Date - Mode=Prefix, Type=Taken, Fmt=YMD HMS, Seg= - , Cent=ticked
FILENAME.jpg to 2006-01-24-08-58-22
If two files have the exact same EXIF data then a _1 will be appended to the name which can be removed during the AllDup section.


## AllDup ##
Use this tool to remove duplicate files. There will be two methods listed below, one searches for images and then I remove the smallest files from each group. The second method uses filenames to remove duplicates.


Search method - Find similar filenames
Comparison - WordMatch
Match 90%
Delimiter _
Comparison method - compare only characters at the end of the filename 2 characters selected

The above settings should find all files that are duplicates based on the previously completed task of renaming all files with the EXIF data as per Task 1. Any file renamed using Task 1 and having the exact same EXIF data will have an appended _1 to the filename.

