# Basic Linux Commands

## Directory & Location
- `pwd` → Display current directory
- `ls` → List files
- `ls -l` → List files with details
- `ls -a` → List all files including hidden
- `ls -lt` → List files by timestamp
- `ls -ltr` → List files by timestamp reverse
- `ls -ld` → Show permissions of a directory
- `ln -s /source /link` → Create symbolic link

## Changing Directories
- `cd directory_name` → Relative path
- `cd /absolute/path` → Absolute path
- `cd ..` → Go up one level
- `cd ~` → Home directory
- `cd /` → Root directory

## File & Directory Management
- `mkdir folder` → Create directory
- `mkdir -p parent/child` → Nested directories
- `rmdir folder` → Remove empty directory
- `rm file` → Remove file
- `rm -r folder` → Remove directory recursively
- `rm -f file` → Force remove file
- `rm -rf folder` → Force remove directory recursively

## Viewing & Editing Files
- `cat file.txt` → Show content
- `less file.txt` → Scrollable view
- `more file.txt` → Page-by-page view
- `head file.txt` → First 10 lines
- `head -15 file.txt` → First 15 lines
- `tail file.txt` → Last 10 lines
- `tail -15 file.txt` → Last 15 lines
- `tail -f file.txt` → Dynamic log view

## Copy & Move
- `cp file1 file2` → Copy file
- `cp -r folder1 folder2` → Copy folder
- `mv old new` → Rename or move file/folder

## Search & Filters
- `grep word file.txt` → Case-sensitive search
- `grep -i word file.txt` → Case-insensitive
- `grep -R word *` → Recursive search
- `grep -vi word file.txt` → Exclude word
