# iterating for loops in dictionary 

```


dictionary = {
    "key1": "value",
    "key2": "value2",
    "key3": "value3",
    "key4": "value4",
    "key5": "value5",
    "key6": "value6",

}

for x in dictionary:
    print(x)  # this prints only keys

for item in dictionary.values():  # this prints only values
    print(item)

for key in dictionary:
    print(key, " : ", dictionary[key]) # this prints key and value pairs

```
the output is:

![image](https://user-images.githubusercontent.com/110176257/182580191-7d2153c2-5834-436d-b81f-68088165f6f3.png)
