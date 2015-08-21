C file struture for C projects


## USAGE

```bash
bash c-scaffold.sh <project-name> <module-name> 
```

Example 
```bash
bash c-scaffold.sh nyancat rainbow

Happy Coding!

/Users/matiskay/lncc/courses/data-structures/scripts/nyancat
├── Makefile
├── README.mkd
├── main.c
├── minunit.h
├── rainbow.c
├── rainbow.h
└── test_rainbow.c

0 directories, 7 files
```

```bash
make test
```

```
rm *.out || exit 0
rm: *.out: No such file or directory
gcc -c rainbow.c
gcc -c test_rainbow.c
gcc -o test_rainbow rainbow.o test_rainbow.o
./test_rainbow
-_-_-_-_-_-_-_,------,      o
_-_-_-_-_-_-_-|   /\_/\
-_-_-_-_-_-_-~|__( ^ .^)  +     +
_-_-_-_-_-_-_-  ""  ""
 ✓ ALL TESTS PASSED
 Tests run: 1
```

## Links

- http://www.jera.com/techinfo/jtns/jtn002.html
