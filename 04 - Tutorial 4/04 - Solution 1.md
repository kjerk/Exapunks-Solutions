```
LINK 800
GRAB 200
COPY F X
WIPE
LINK 800
MAKE
COPY X F
MARK LOOP
ADDI X -1 X
COPY X F
TEST X = 0
FJMP LOOP
```

![Solution 1](https://github.com/kjerk/Exapunks-Solutions/blob/master/04%20-%20Tutorial%204/images/04%20-%20Solution%201.gif?raw=true)
