# SSOS-Lab-Programs

SSOS Lab Programs VTU 6th Sem
***

### How to run programs in Windows OS:

- Follow [this video](https://www.youtube.com/watch?v=QbmRXJJKsvs) to download VirtualBox and Ubuntu ISO file

- Run, in Ubuntu VM : **sudo apt-get install flex bison** to install the required packages 

#### Compile Lex Programs :
```
gedit pgm.l
lex pgm.l
cc lex.yy.c
./a.out
```

#### Compile LEX & YACC both :
```
gedit pgm.l
gedit pgm.y
lex pgm.l
yacc -d pgm.y
cc lex.yy.c y.tab.c 
./a.out
```

#### Compile C Programs :
``` 
gedit pgm.c
cc pgm.c
./a.out
```
