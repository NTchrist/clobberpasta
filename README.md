# clobberpasta
clobber a file and open nano, ready to accept a pasted new copy of that file.

Useful for ninja-replacing a file when you don't otherwise have a convinient way to replace that file.

Creates a backup every edit in ~/.nanopasta/PATH/TO/FILE/[DATESTAMP]_[FILE]

--

usage:

clobberpasta /path/to/file

--

Install with (as root):

wget https://raw.githubusercontent.com/NTchrist/clobberpasta/main/clobberpasta -O /usr/bin/clobberpasta; chmod +x /usr/bin/clobberpasta
