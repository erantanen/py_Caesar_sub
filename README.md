## Synopsis

This is a simple Caesar cipher.

Caesar used a rotation of 13 with in the alphabet.


## Examples:
Shows an input and output.

```js
 gandalf  -> tnaqnys
 hello world ->  uryyb jbeyq
 this is a crazy world -> guvf vf n penml jbeyq
```


## Code Example
The unique thing about this approach is the mapping, it is intended for variations in shift
(once I have more time will continue on this variation)

```js
def alpha_mapping(shift):
    alfa_list = list(map( chr, range(97, 123)))
    num_list = list(range(97+shift, 123+shift))
    return list(zip( alfa_list, num_list))
```



## License

MIT -> use it have fun with it, learn from it