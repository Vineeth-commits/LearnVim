#Vim Operations
---
* Difference between vim and vi - vim is almost a proper superset of vi
* Features on vim -
    * Support for several programming languages.
    * It can be used to edit files using network protocols like SSH and HTTP
    * It can edit files inside a compressed archieve like gzip,tar
    * It has a built in diff tool (vimdiff)
    * It includes multilevel undo/redo
* Vim has two mode - insert mode where you write text like on a normal text editor and normal mode which provides efficient ways to navigate and manipulate the file.
* To enter insert mode, enter 'i' and to go back to normal mode enter 'ESC'
* One can use h(left), j(top), k(down) and l(right) as an alternative to arrow keys.
* To navigate in the text in terms of words, w, b and e.
* 'w' moves to the start of the next word; 'e' moves to the end of the word and 'b' moves to beginning of the previous word.
* One can combine movement keys with numbers to move faster like 3e is equal to pressing e three times.
* One can insert text multiple times repeatedly like '10iyo' will insert 'yo' 10 times in the file.
* With 'f' one can find the next occurrence of a character and 'F' finds the previous occurrence of a character,
* In text that is structured in parathesis or brackets, {, [ and (, use % to jump to the matching parathesis.
* To reach the beginning of the line press '0' and to reach the end of the line press '$'.
* To find the next occurrence of the word under cursor press '*' and the previous with '#'.
* 'gg' takes you to the beginning of the file and 'G' take you to the end of the file.
* To move to a particular line press '[LineNumber]G' like 7G moves to the beginning of the 7th line.
* Searching a text can be done by press '/' followed by the text to be searched. One can repeat the search for next and previous occurrences with n and N respectively.
* To insert a line after the cursor press 'o' and to insert a line before the cursor press 'O'
* x and X delete the character under the cursor and to the left of the cursor.
* When you need to replace only one character under your cursor, without changing to insert mode, use 'r'.
* 'd' is the delete command. This can be combines with other movement keys like 'dw' to delete the word and 'dd' to delete a line. It also copies content so you can paste it using 'p'  
* To repeat the previous command, just press '.'
* In visual mode(press 'v'), you can select text using movement keys before you decide what to do with it.
* :w to save the file; :q to quit and :q! to quit without saving.
* Use 'u' to undo and ctrl + R to redo
* Finally, :help if you want to learn more.