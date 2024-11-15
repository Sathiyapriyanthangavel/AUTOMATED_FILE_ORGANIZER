#File Organizer Script

A Python script to organize files in a directory into categorized subfolders based on their file extensions. This is particularly useful for decluttering directories and keeping files organized.

##Features

Automatically creates categorized directories (Videos, Audio, Images, Documents, Programs, Software) if they don't exist.
Moves files into respective folders based on their file extensions.
Handles case-insensitivity for file extensions (e.g., .MP4 and .mp4).
Skips hidden/system files and subdirectories.
Provides detailed logs for moved, skipped, and unhandled files.
Implements error handling to avoid issues like file permission problems or duplicate names.

#File Categories
##Category and Extensions_Handled

Videos (.mp4, .mov, .mkv, .webm), Audio	(.mp3, .aac, .m4a), Images (.png, .jpeg, .jpg), Documents (.pdf, .docx, .pptx, .doc), Programs (.py, .c, .cpp, .java), Software (.exe)

#Requirements

Python 3.6 or higher
Modules:
os
shutil
No external dependencies are required.

#Future Enhancements

Add support for more file types.
Provide a GUI for non-technical users.
Allow the user to define custom categories and extensions dynamically.

Author
Developed by CHANDRU R S and SATHIYAPRIYAN T.
