## nruneprog

### Instructions

Write a function that returns the nth `rune` of a `string`.

### Expected output :

```console
student@ubuntu:~/piscine-go/nruneprog$ ./nruneprog "hello" 2
e
student@ubuntu:~/piscine-go/nruneprog$ ./nruneprog "hello" 4 | cat -e
l$
student@ubuntu:~/piscine-go/nruneprog$ ./nruneprog "hello" 5
o
student@ubuntu:~/piscine-go/nruneprog$ ./nruneprog "hello"
student@ubuntu:~/piscine-go/nruneprog$ ./nruneprog "hello" f | cat -e
"f" is not an integer value$
student@ubuntu:~/piscine-go/nruneprog$ ./nruneprog "hello" 9
Invalid position: "9" in "hello"
student@ubuntu:~/piscine-go/nruneprog$
```
