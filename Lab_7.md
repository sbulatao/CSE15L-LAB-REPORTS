# Part 1

cd week6-skill-demo1/
vim DocSearchServer.java
/start+enter replace it with base
n+e+a+esc to find the start, go to the end of the word, insert and replace it with base
:wq+enter to save the changes

## Task: **Changing the name of the** `start` **parameter and its uses to** `base`

`cd week6-skill-demo1/` `<Enter>`

> This changes the current directory to `week6-skill-demo1/`.

`vim DocSearchServer.java` `<Enter>`

> Using `vim` to edit the text file `DocSearchServer.java`.

`/start` `<Enter>`

> The `/` searches for the word after it. Here we clearly see that `start` is the word we are trying to search for.

`dw` `<Enter>`

> This command `dw` deletes the word from the cursor. So here we are deleting the word `start`.

`i` `base` `<Esc>`

> This command `i` inserts the text before the current cursor position and we are in insert mode. So here we are inserting the word `base` and pressing the `Esc` button to exit out of the inserting mode.

`n` `dw`

> This command `n` repeats the latest pattern that we last entered. The latest patterned we last entered was `/start`, which we are able to find the other words that we are looking for to replace `start` with `base`. Then the next command `dw` delets the word from the cursor and we replace `start` with `base`.

***
> Repeated commands:

`i` `base` `<Esc>`

`n` `dw`

`i` `base` `<Esc>`

`n` `dw`

`i` `base` `<Esc>`

> Here we repeated the commands we previously used to keep replacing the `start` with `base` until there are no more words that starts with `start` and are completely replaced with `base`. 
***

`:wq` `<Enter>`

> This command `:wd` is an exit command that writes the file to the disk and quits the editor.

**Total keys pressed after** `vim DocSearchServer.java`**: 30 total keys pressed** 


# Part 2

#### How long it took to makee edits in both styles? Any difficulties or details that came up in doing so?


#### Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?


#### What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why?)







