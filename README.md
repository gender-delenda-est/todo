# todo
a simple todo list in bash

## installation

put the todo script in your path somewhere (e.g. `~/.local/bin`)
when you run the script for the first time it will attempt to create a .csv for the list in ~/.local/share; make sure this directory exists first.

## usage

usage:
	todo -> print list
	todo add TITLE [DESCRIPTION] [DATE/TIME] -> add entry
		remember to put "quotes" around multi-word entries
		for just TITLE and [TIME] add "" in place of the description
	todo remove NUMBER -> remove entry at specified number
