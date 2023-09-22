# Photo Organization Guide #

Follow this order of operations to move, dedupe, rename and dedupe again all of your photos.


## PhotoMove2 ##
Use this app to bulk move photos from one folder to another and create new folders based on EXIF data separated by YR-MTH. Can also choose to move files without any EXIF data to a separate folder for manual editing of dates later. This works well as a quick method to bulk move many files at once to new folders, 10k plus files for example.

## AllDup ##
Use this tool to remove duplicate files.

Method 1
- Search method - Find similar pictures
- Match 91%
- Once this completes check several of the groups and determine that these are duplicates, then Select all files in each group other than largest file by size. 
- Delete all selected files
This should remove the smallest file size identified as a duplicate

## Bulk Renaming Utility ##
Rename files based on the EXIF data.
- Box 2 Name - Remove
- Box 8 Auto Date - Mode=Prefix, Type=Taken, Fmt=YMD HMS, Seg= - , Cent=ticked
FILENAME.jpg to 2006-01-24-08-58-22
If two files have the exact same EXIF data then a _1 will be appended to the name which can be removed during the AllDup section.


## AllDup ##
Use this tool to remove duplicate files.

Method 2 (Run after using the Bulk Renaming Utility)
- Search method - Find similar filenames
- Comparison - WordMatch
- Match 90%
- Delimiter _
- Comparison method - compare only characters at the end of the filename 2 characters selected

The above settings should find all files that are duplicates based on the previously completed task of renaming all files with the EXIF data using Bulk Rename Utility.

