## Exercise 3

### Problem

For this third exercise, we want to manipulate dates in Python.

The program should read two dates in format `DD-MM-YYYY` and display the number of days between these two dates.
```bash
$ python delta.py "15-01-2011" "19-01-2011"
4
```

### Bonus

It may be interesting to display also some additional information regarding the two dates given as input, like the day of the week (*tuesday*), or the month name (*January*).

### Help

In Python, the `datetime` package is used to manipulate dates. More particularly, `datetime.strptime()` is very useful to parse dates with different formats...

