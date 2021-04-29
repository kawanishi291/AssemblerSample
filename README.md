# AssemblerSample

```
$ docker build -t assemblersample .
$ docker run -it -v $(pwd):/work assemblersample bash

$ cd work
$ nasm -felf64 hello.asm -o hello.o
$ ld -o hello hello.o
$ ./hello
```