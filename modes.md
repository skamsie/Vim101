## Modes

#### Normal mode

For navigation and manipulation of text.  
The default mode. Otherwise can be accesed using `ESC`

`:help Normal-mode`

#### Insert mode

Inserting and replacing text.

`i` enter insert mode at cursor  
`I` enter insert mode at beginning of line  
`a` enter insert mode after cursor  
`A` enter insert mode at the end of line  
`o` enter insert mode on new line below  
`O` enter insert mode on new line above  
`S` delete line and enter insert mode

`:help Insert-mode`

#### Visual mode

Visually select a character, line or block.

`v` enter character visual mode  
`V` visual line mode  
`Ctrl-v` visual block mode  

`:help Visual-mode`

#### Replace mode

`R` enter replace mode

In Replace mode, one character in the line is deleted for every character you
type.  If there is no character to delete (at the end of the line), the
typed character is appended (as in Insert mode).

`:help Replace-mode`

#### Command line mode

Command-line mode is used to enter Ex commands, search patterns, and filter commands.

`:` start command line mode  
`/` start search forward  
`?` start search backward   

`:help Command-line-mode`



