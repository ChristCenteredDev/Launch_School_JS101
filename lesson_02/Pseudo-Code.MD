# Psuedo-Code Problems
1. a function that returns the sum of two numbers
2. a function that takes an array of strings, and returns a string that is all those strings concatenated together
3. a function that takes an array of integers, and returns a new array with every other element

## Formal Psuedo-Code Keys
### Keyword //	Meaning
START	start of the program <br>
SET	set a variable that we can use for later <br>
GET	retrieve input from user <br>
PRINT	display output to user <br>
READ	retrieve a value from a variable <br>
IF/ELSE IF/ELSE	show conditional branches in logic <br>
WHILE	show looping logic <br>
END	end of the program <br>

### Psuedo-Code Problem #1
```
Declare a function with two arguments
return arg1 + arg2
```

### Formal Psuedo-Code Problem #1
```
START
SET function getSum with arg1 & arg2
PRINT arg1 + arg2
END
```

### Psuedo-Code Problem #2
```
Declare a function with argument arrayOfStrings
Join arrayOfStrings together
return newString
```

### Formal Psuedo-Code Problem #2
```
START
SET function joinStrings with argument arrayOfStrings
SET newString equal to arrayOfStrings joined
PRINT newString
END
```

### Psuedo-Code Problem #3
```
Declare an empty array named newArray
Declare a function with argument arrayIntegers
Declare a WHILE loop to loop over arrayIntegers
IF index is even number then push arrayInteger[index] to newArray
Return newArray once For Loop is completed
```

### Formal Psuedo-Code Problem #3
```
START
SET newArray to empty array
SET function getEvenArray with arrayIntegers parameter
SET index = 0

WHILE index < length of arrayIntegers
  IF index % 2 === 0
    newArray.push(arrayIntegers[index])

  index = index + 1

PRINT newArray
END
```