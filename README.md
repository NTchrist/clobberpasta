# clobberpasta
clobber a file and open [nano] > [vim] > [vi], ready to accept a pasted new copy of that file.

Useful for ninja-replacing a file when you don't otherwise have a convinient way to replace that file.

Creates a backup every edit in ~/.clobberpasta/PATH/TO/FILE/[DATESTAMP]_[FILE]

If the resulting file is functionally empty (defined as not existing, containing only blank spaces, or a single empty line), will automatically restore from backup.  This is useful if you include clobberpasta as a manual command centipede but don't always need to update that file.

--

usage:

clobberpasta /path/to/file

--

Install with (as root):
```
wget https://raw.githubusercontent.com/NTchrist/clobberpasta/main/clobberpasta -O /usr/bin/clobberpasta; chmod +x /usr/bin/clobberpasta
```
