## Editing

#### delete / copy / paste

`y`  copy selection  
`yy` copy line  

`p`  paste before the cursor  
`P`  paste after the cursor  

`x`  delete character after the cursor  
`X`  delete character before the cursor  

`d`  delete (followed by movement)  
`dd` delete line  
`u`  undo  
`Ctrl-r` redo  

#### d combinations

`4dd` delete next four lines  
`dG`  delete from cursor until the end of file  
`dgg` delete from cursor until the beginning of file  
`dtr` delete from cursor until the first occurence of 'r' on the line  
`dfr` delete from cursor until the first occurence of 'r' on the line, including the 'r'  
`diw` delete (inner) word  
`daw` delete around word (including white spaces)  
`dw`  delete from cursor until the end of word  
`D`   delete from cursor until the end of line

#### c combinations

Very similar to the `d` combinations, but also enters insert mode.  
Same combinations as above apply. Eg:    

`C`   change until the end of line (delete and enter insert mode)  
`ci'` change inside ''  

#### others

`r` replace character under cursor  
`R` enter Replace mode  
`~` change case  
`.` repeat last action  

