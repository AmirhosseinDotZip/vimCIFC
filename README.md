You can run the following command in Vim to count the number of occurrences of "git" in the current file:
```
:%s/git//gn
```
This command uses Vim's ```:substitute``` command with the ```g``` global flag and the ```n``` option that prevents actual substitution but shows the count of matches. The ```:%``` range specifies the whole file, and ```//``` indicates an empty search pattern since we're repeating the same string searched for.
