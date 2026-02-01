# Filter & IO Redirection Commands

## Piping
- `ls | wc -l` → Count files in directory

## Redirect Output
- `>` → Overwrite
- `>>` → Append
- `cat file > /dev/null` → Discard output

## sed
- `sed -i 's/old/new/g' file` → Replace in file
- `:%s/old/new/g` → Replace in vim

## find
- `find /etc -name hosts` → Find file by name
- `find /var/log -size +100M` → Find large files

## less & more
- `less file.txt` → Scrollable read-only
- `more file.txt` → Page-by-page read-only
