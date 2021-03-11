### Hola, Yo soy Kevin 👋


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


<!--
**krios-fu/krios-fu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
