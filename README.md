# Hi There! 👋

```c
#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>

typedef struct s_developer
{
    char    *name;
    char    *role;
    char    *languages[6];
    char    *interests[4];
    bool    loves_challenges;
}   t_developer;

int main(void)
{
    t_developer me = {
        .name = "Ruthler Louis",
        .role = "Software Engineer",
        .languages = {"C", "Python", "JavaScript", "HTML", "CSS", NULL},
        .interests = {
            "Low-level programming",
            "Algorithms & Data Structures",
            "System Architecture",
            NULL
        },
        .loves_challenges = true
    };

    printf("Building things, breaking things,\n");
    printf("and understanding why they work.\n");

    return (EXIT_SUCCESS);
}
```

### 🧠 About Me

```bash
$ whoami
> Software Engineer
> C enthusiast
> Problem solver
> Always learning

$ cat philosophy.txt
"Understand the machine.
 Master the fundamentals.
 Write code that matters."
```

### ⚙️ What I'm Into

- 🧠 **C Programming** — Pointers, memory management, and understanding what happens under the hood.
- 🛠️ **Software Engineering** — Writing clean, efficient, and maintainable code.
- 🧩 **Algorithms & Data Structures** — Solving problems one algorithm at a time.
- 🏗️ **System Design** — Understanding how complex systems fit together.
- 🚀 **Building Things** — Turning ideas into working software.

### 💻 Tech Stack

`C` · `Python` · `JavaScript` · `Git` · `Linux` · `Bash`

---

### 💭 Developer Philosophy

> "If you want to understand how software works, get closer to the hardware."

```c
while (alive)
{
    learn();
    build();
    debug();
    improve();
}
```

**Keep coding. Keep learning. Never stop being curious.** 🚀
