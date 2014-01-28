todolist
===========

Simple command-line todo list

Enter items you'd like to add as command line arguments enclosed in quotes and separated by spaces.
The most recent item always goes on top of the list.

If you want to remove entries, enter either the same text as the entry (case-insensitive) or just the number of the entry as an argument.
You can remove an arbitrary number of entries simultaneously, just separate the removal arguments with spaces.

Example use:
```
./main "Third thing I want to get done"
1: Third thing I want to get done

./main "Second thing I want to get done" "First thing I want to get done"
1: First thing I want to get done
2: Second thing I want to get done
3: Third thing I want to get done

./main 1 3
1: Second thing I want to get done

./main 'second thing i want to get done'
Todo list is empty!
```
