# todo
a simple todo list in bash

## installation

Put the todo script in your path somewhere (e.g. `~/.local/bin`)
when you run the script for the first time it will attempt to create a .csv for the list in `~/.local/share`: if the directory does not exist it will be created the first time you run the program.

To install the man page provided (todo.1), copy it to your local man directory and refresh the database triggers as follows:

```
$ sudo cp todo.1 /usr/share/man/man1/

$ sudo mandb
```

assuming no problems occur, you should now be able to access the manpage with `man todo`.

## usage
```
	todo -> print list
	todo add TITLE [DESCRIPTION] [DATE/TIME] -> add entry
		remember to put "quotes" around multi-word entries
		for just TITLE and [TIME] add "" in place of the description
	todo remove NUMBER -> remove entry at specified number
```
