# Alteryx SDK Tool - File Copy and Move
Alteryx tool to copy or move files

##Options
Copies or moves files from source to destination. If the destination is a path the filenames will be unchanged, otherwise it will use the provised filename.

You can optionally create the detination path so it's possible to create dynamic destination directories using dates and times for example.

##Outputs
Sucessful operations will be out put to the O-Output, if a file cannot be moved or copied (due to file locking for example) then the row will be out put to the E-Error output.
