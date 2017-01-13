# Intro

## Benefits

- Faster to develop a prototype
- Simple to use yet complex to support large programs (cause of high level data types)
- Compact and readable
- Great native library
- Used as an extension language
- Extensible
- Named after the `Monty Ponty's Show`

---
# Interpreter

```
$ python3.6
Python 3.6 (default, Sep 16 2015, 09:25:04)
[GCC 4.8.2] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
After pressing ```Enter``` will interpret the line

```
>>> the_world_is_flat = True
>>> if the_world_is_flat:
...     print("Be careful not to fall off!")
...
Be careful not to fall off!
```

In case of multiline code, the whole block will be interpreted after you finish:

```
>>> for i in range(0, 5):
...     print(i+1)
...
1
2
3
4
5
```
