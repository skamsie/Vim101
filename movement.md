## Movement (normal mode)

<kbd>h</kbd><kbd>j</kbd><kbd>k</kbd><kbd>l</kbd> ← ↓ ↑ →

`0` go to the beginning of line

`$` go to the end of line

`gg` go to first line

`3gg` go to third line

`G` go to last line

`w` word\* forward

`3w` words forward

`W` WORD\** forward

`b` word backward

`B` WORD backward

\* A **word** consists of a sequence of letters, digits and underscores, or a
sequence of other non-blank characters, separated with white space (spaces,
tabs, \<EOL\>).

\** A **WORD** consists of a sequence of non-blank characters, separated with white
space.

<hr />

#### motions using 'f' and 't'

`fm` jump forward to the first occurence of 'm' on the line

`Fm` jump backward to the first occurence of 'm' on the line

`tm` jump forward until the first occurence of 'm' on the line

`Tm` jump backward until the first occurence of 'm' on the line

The last `f` or `t` action can be repetead with ';'

<hr />

#### scroll / jump paragraphs

`H` jump to first line in current view  
`M` jump to middle line in current view  
`L` jump to last line in current view  

`Ctrl-e` scroll down line by line  
`Ctrl-y` scroll up line by line  

`Ctrl-d` scroll down half page  
`Ctrl-u` scroll up half page 

`{` paragraph up  
`}` paragraph down  
