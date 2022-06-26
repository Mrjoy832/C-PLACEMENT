# Identifier and Keywords

- **KEYWORDS**->predefined words those have special meaning to compiler(int,switch,if ,else,struct)
- **32** keywords in C. All are written in lower case
- **Identifer**->elements choosen by user (int val, char name, sum()).
it contains 'a'-'z' or 'A'-'Z' or 0-9, ''



# Tokens:
- Building BLock of Code. It can be keyword ,Identifier, constant value,symbols etc.
```c
//How many tokens are present here??
//Ans=5
int a=5;
```

![image](https://user-images.githubusercontent.com/77873383/174835889-527c06b3-0ab2-4e00-ab4b-9246e1c3c310.png)


---
<br>

# Comments in C
- // single line command
```c
// Single Line Comment

#include<stdio.h>
```
- /* */ Multiple line command
```c
/*Multiple line
command*/
#include<stdio.h>

```

# MACROS:
> it's basically a single line/simple-instruction/file by which large part of code can be implemented. 

```c
#include<stdio.h>
#define pi 3.14
#define AREA(r) (pi*r*r)
int main(){
    printf()
    area=AREA(5)
}
how we know "How printf()" works..that is known by stdio.h 

```

- **Preprocessors*->any thing above main except part related to main code.
