## windows / buffers / tabs

Summary:  
 - A buffer is the in-memory text of a file.  
 - A window is a viewport on a buffer.  
 - A tab page is a collection of windows.  

A window is a viewport onto a buffer.  You can use multiple windows on one
buffer, or several windows on different buffers.
A buffer is a file loaded into memory for editing.  The original file remains
unchanged until you write the buffer to the file.

<hr />

#### buffers

`:ls` list buffers    
`:ls!` list **all** buffers (even unlisted ones, like help files)  
`:b3` go to buffer 3  
`:bd` delete current buffer  
`:bd3` delete buffer 3
`:bn` go to next buffer 
`:bp` go to previous buffer  

#### tabs

`:tabe` open a new tab  
`gt` go to next tab (cycles when reaches last tab)  

#### windows

`:sp` or `Ctrl-s` open new window in horizontal split  
`:vsp` or `Ctrl-w v` open new window in vertical split  
`Ctrl-w` + `h` or `j` or `k` or `l` move to window  
