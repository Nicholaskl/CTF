# Buffer Overflow Methodology

## Python Method

Somtimes its easier to use python to pipe information to find the exact number of characters to break the program. Done like the following
```python
python -c "print 'A'*30" | ./program
```

