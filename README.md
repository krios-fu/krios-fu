
```c
#include <stdio.h>

typedef struct s_profile
{
    char    *name;
    char    *lastName;
    char    *profession;
    char    *from;
    char    *live;
    int     age;
}           t_profile;

int		main(int argc, char **argv)
{
    t_profile me;

    me.name = "Kevin Amin";
    me.lastName = "Rios Fuentes";
    me.profession = "Estudiante de programación en 42 madrid fundacion Telefonica";
    me.from = "Colombia";
    me.live = "España";
    me.age = 28;

    printf("👨Yo soy %s %s\n💻Actualmente soy %s\n🇨🇴Soy de %s\n🇪🇸Vivo actualmente en: %s\n 📆Tengo %d años\n",
            me.name, me.lastName, me.profession, me.from, me.live, me.age);

    return (0);
}

```
```sh
c1r5s6% gcc profile.c -o profile
c1r5s6% ./profile 
👨 Yo soy Kevin Amin Rios Fuentes
💻 Actualmente soy Estudiante de programación en 42 madrid fundacion Telefonica
🇨🇴 Soy de Colombia
🇪🇸 Vivo actualmente en: España
📆 Tengo 28 años 
```
