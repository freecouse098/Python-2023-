# Chapter 3 : Python Data Types

Built-in Data Types

* In programming, data type is an important concept.

* Variables can store data of different types, and different types can do different things.

* Python has the following data types built-in by default, in these categories:

```bash
1. Text Type: 	str

2. Numeric Types: 	int, float, complex

3. Sequence Types: 	list, tuple, range

4. Mapping Type: 	dict

5. Set Types: 	set , frozenset

6. Boolean Type: 	bool

7. Binary Types: 	bytes, bytearray, memoryview

8. None Type: 	NoneType
```



# Getting the Data Type

You can get the data type of any object by using the type() function:

* Example
 
 ```bash
  Print the data type of the variable x:

x = 5

print(type(x))
```

# Setting the Data Type

Setting the Specific Data Type

If you want to specify the data type, you can use the following constructor functions:
Example 	

```bash

  Data Type 	

Try it

* x = str("Hello World") 	str 	
* x = int(20) 	int 	
* x = float(20.5) 	float 	
* x = complex(1j) 	complex 	
* x = list(("apple", "banana", "cherry")) 	list 	
* x = tuple(("apple", "banana", "cherry")) 	tuple 	
* x = range(6) 	range 	
* x = dict(name="John", age=36) 	dict 	
* x = set(("apple", "banana", "cherry")) 	set 	
* x = frozenset(("apple", "banana", "cherry")) 	frozenset 	
* x = bool(5) 	bool 	
* x = bytes(5) 	bytes 	
* x = bytearray(5) 	bytearray 	
x = memoryview(bytes(5)) 	memoryview
```

