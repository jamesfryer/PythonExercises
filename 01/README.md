## Exercise 1

### Problem

For this first exercise, we want to code a program `count.py` counting the words of a text file, without case.

The program should work as follow:
```bash
$ python count.py file.txt
```

If `file.txt` has those three lines:
```bash
$ cat file.txt
Salad
Apple banana
Banana
```

The program should give:
```bash
$ python count.py file.txt
salad   1
apple   1
banana  2
```

### Bonus

Write the words with a relevant order, for example in alphabetical order, or by frequency.

### Help

To access command-line arguments from Python:
```python
import sys
sys.argv
```
