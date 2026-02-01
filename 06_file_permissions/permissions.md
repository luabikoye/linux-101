# File Permissions

## chmod
- `chmod u+rx file` → Give read & execute to owner
- `chmod g+rx file` → Give read & execute to group
- `chmod o-x file` → Remove execute for others
- Numeric: `chmod 640 file` → Owner=rw, Group=r, Others=none
- Recursive: `chmod -R 770 /dir`

## chown
- `chown user:group file` → Change owner/group
- `chown -R user:group /dir` → Recursive

## visudo
- Edit sudo permissions safely
