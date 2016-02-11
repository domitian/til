# VIM MARKS

Store a pointer to a certain location in the file by row and column and return to it using vim marks.

To mark the current location of cursor use `ma` to store the pointer in the mark register `a`. Registers for marks are available from [a-z,A-Z]. [a-z] are file specific, while their counterparts apply to all files.

To go to the mark location, use `'a'`, here in this case will go to location pointed by mark register `a`.
