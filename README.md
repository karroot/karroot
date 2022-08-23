### 👋 おはよう世界！

```C
#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>

typedef struct {
    char *name;
    char *born_date;
    char *title;
    char *university[2];
    char *work_experience[2];
    char *interest[3];
} Human;

int main(void) {

   Human *Karroot = malloc(sizeof(*Karroot));

   Karroot->name = "Gabriele Gallotti";
   Karroot->born_date = "23/09/1997";
   Karroot->title = "Cybersecurity Auditor";
   Karroot->university[0] = "Polytechnic of Milan";
   Karroot->university[1] = "Boccony University";
   Karroot->work_experience[0] = "Cefriel"; // as ICT security analyst & developer 
   Karroot->work_experience[1] = "Unicredit"; // as Cybersecurity Auditor
   Karroot->interest[0] = "Cybersecurity risk";
   Karroot->interest[1] = "Network security";
   Karroot->interest[2] = "Computer ethics";
   
   printf("\n %s can be defined as:\n\n", Karroot->name);
   printf("A funny guy born in %s, currently a %s at %s and he graduated at both %s and %s while working as intern at %s and
   he is currently interested in %s, %s and %s.",
   Karroot->born_date, Karroot->title, Karroot->work_experience[1], Karroot->university[0], Karroot->university[1],
   Karroot->work_experience[0], Karroot->interest[0], Karroot->interest[1], Karroot->interest[2]);

    return 0;
}

```

---

### 🧐 About me

<img align='center' src="https://i.kym-cdn.com/photos/images/original/000/948/102/01a.gif" width="420" height="300">
Currently cybersecurity auditor at Unicredit S.p.a. 
I deal with digital ethics whenever possible.

Alumnus of Bocconi University and Politecnico di Milano.

Member of [EticaDigitale](https://t.me/EticaDigitaleChannel) where we publish relevant computer ethics news for the italian community.

Passionate about IT, cyber security and the impacts of new technologies on society.
Now I'm studying for the Cisco CCNA routing and switching certification (200-301) and I keep myself informed on cyber developments in the world.
Among other things I am passionate about anime/manga, fighting sports and theology.

---

### 🕹️ My projects

---

### 🔦 Find me on
- [My website](https://karroot.github.io);
- [Linkedin](https://www.linkedin.com/in/gabriele-gallotti/);

<!---
karroot/karroot is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
--->
