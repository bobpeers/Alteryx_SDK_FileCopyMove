# Alteryx SDK Tool - File Copy and Move
Alteryx tool to copy or move files


## Installation
Download the yxi file and double click to install in Alteyrx. The tool will be installed in a new Category called __File System__

![alt text](https://github.com/bobpeers/Alteryx_SDK_FileCopyMove/blob/master/images/AlteryxCategory.png "Alteryx File system Category")

## Usage
Copies or moves files from source to destination. If the destination is a path the filenames will be unchanged, otherwise it will use the provided filename.

__Exisitng files with the same name will be overwritten.__

You can optionally create the detination path so it's possible to create dynamic destination directories using dates and times for example.

## Outputs
Sucessful operations will be out put to the O-Output, if a file cannot be moved or copied (due to file locking for example) then the row will be out put to the E-Error output.
