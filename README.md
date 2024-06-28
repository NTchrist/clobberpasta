# nanopasta
clobber a file and open nano, ready to accept a pasted new copy of that file.

Useful for ninja-replacing a file when you don't otherwise have a convinient way to replace that file.

Creates a backup every edit in ~/.nanopasta/PATH/TO/FILE/[DATESTAMP]_[FILE]

--

usage:

nanopasta /path/to/file

--

Install with (as root):

wget https://raw.githubusercontent.com/NTchrist/nanopasta/main/nanopasta -O /usr/bin/nanopasta; chmod +x /usr/bin/nanopasta
