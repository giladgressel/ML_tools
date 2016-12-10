# A Guide to Jupyter Notebooks
#### [Hotkeys](https://www.cheatography.com/weidadeyue/cheat-sheets/jupyter-notebook/)
#### [Markdown Help](https://athena.brynmawr.edu/jupyter/hub/dblank/public/Jupyter%20Notebook%20Users%20Manual.ipynb)

## Cells
Every cell can be either Code or Markdown, `shift-enter` will execute the cells.

## Shortcuts

If you look at help >> keyboard shortcuts, you will get all the shortcuts.

![shortcuts](imgs/keyboard_shortcuts.png)

#### Whenever you are in jupyter, you are always in one of two modes, `Command` or `Edit`

#### `Edit` Mode - Green
![Green Mode](imgs/green-command.png)

#### `Command` Mode - Blue
![Blue mode](imgs/blue-command.png)

Command mode is always in blue around the cell.  Note the pencil is missing also.  You can get to command mode by pressing "esc"

## Jupyter is running a live python intrepreter. 



## You can also interact with your OS, as if it was a terminal session
`ls` 

![ls](imgs/ls.png)

`pwd`

![pwd](imgs/pwd.png)

## Tab
Tab provides us with autocomplete! Try it out, you can use it almost everywhere.
Here we see tab giving us methods and attributes for an object.

![tab-attr](imgs/tab.png)

But tab can also be used for imports

![tab-imports](imgs/tab_imports.png)

Or completing variable names that you've type out before

![tab-variable-names](imgs/tab_variables.png)

Note, I only typed the first two letters so there was ambiguity, hence the drop down menu for me.  But if you type enough, it will just autocomplete it.

## Shift-tab
This will show you the documentation for whatever data type are you working with.  Example:

![shift-tab](imgs/shift-tab.png)

If we are looking at a method, it will tell the doc string for the method.

![methods](imgs/shift-tab-methods.png)

This gets really useful when we starting using complicated API that has lots of inputs or parameters.

![apis](imgs/shift-tab-params.png)

Oh, but I know there is more than that!  So.. let me just press shift-tab another time and it will give me more information

![more](imgs/shift-tab-more.png)

Note that the above picture has a scroll bar, which means we can scroll on that documentation!
Wait, now when I want to type in my arguments, I can't remember what they refer to.  I want the documentation to stay for me, so I can refer to it as I type in my arguments. Guess what? You guess!
Hit shift-tab three times in a row until you see the clock!  The clock will keep it popped it out even as you type

![three](imgs/shift-tab-three-times.png)

Sigh, still not enough?  Fine, just hit shift-tab 4 times and it will pop out at the bottom of your screen, in a semi-separate window

![four](imgs/shift-tab-4times.png)

I've highlighted the controls for this pop out.  You can raise and lower it by dragging on the middle button.  You can close the window or pop it out with the controls in the upper right corner.

## Something Totally Crazy – Copy Pasting Code Examples
So you are reading some documentation, and want to follow along with their example. Like this one.

![code-sample](imgs/copy-paste-code-samples.png)

But you really don't wanna type out all those pandas initialization.. No problem you can literally copy paste it!

![itworks](imgs/itworks.png)

This doesn't always work perfectly, but generally it's worth trying.

##  Magic ipython commands
So, you've been hacking at this script for awhile and you need to use some variables you iniatilized awhile ago, but you can't remember what it's called.  Sick of scrolling up?

![whos](imgs/whos.png)

Note:  `whos` only works when it's the only command in the cell block.

You can also add modifiers to Whos.  Here I search for DataFrames only.

![whos-obj](imgs/whos_dataframe.png)

### A Useful Trick to Hide Memory Locations

![memory-hide](img/hide_memory.png)
