# Find large files on disk

Find the 10 largest files in the current directory:

du -ah . | sort -rh | head -10

Useful when a disk is filling up and you don't know why.
