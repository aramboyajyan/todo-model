# TODO Model

This is a brief set of instructions on how to manage your own `TODO` file using just a text editor.  
Guidelines are very very simple; after trying pretty much any other productivity tool from Trello to Evernote, this is what I keep coming back to. I recommend using it in a basic editor, such as Sublime Text, Vim, Gedit or Notepad++. Avoid regular Notepad on Windows, because it has a very limited "Undo" memory. Monospace font helps with readability.

## Symbols

#### -

Denotes a regular task that needs to be done. Most of the items on the list will use this.

#### >

Completed task. This of the symbol as rotated checkmark.

#### ?

Task that needs to be thought about (e.g. figure out a way how execute something), or simply something that might be removed from the list (e.g. not sure if it's really needed).

#### !

Important tasks; for example the ones that need extra attention, be completed first, etc.

#### ~

Postponed tasks; tasks that need some discussion.

#### x

Removed tasks; left for reference.

## Format

#### Date

If storing everything in the same file, date goes at the beginning of the file. Tasks are indented by one tab (2 spaces) to make the date stand out a bit. For example:

        2016.01.01.
          > task one
          > task two
          - task three
          - task four
          ? task five
          ~ task null

Use the following format: `YYYY.MM.DD.`.

#### Time

Sometimes it's good to leave a timestamp in the list; indent it with two tabs and place on a new line, right under the previous task or at the top of the list. Next tasks goes right under. For example:

        > task one
            14:00
        - task two

Use 24 hour format.
