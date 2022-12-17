### Hey!

Im Felix, 20 from Austria 🇦🇹 and I study Software Development 🖥 at 42 Heilbronn 🇩🇪
!
- 🔭 I’m currently working on my startup 🚀
- 🌱 I’m currently learning Flutter 🧢
- 🎛 This is my .bashrc: 
```
// .bashrc from FelixBrgm
export PS1="\W> "
alias ll="ls -la"
alias ld="echo && ls | cat && echo"
```
- ⚡ Favorite bit of code: 
```
// It's a super short version of get_next_line in C
char *get_next_line(int fd)
{
  char *s = malloc(10000), *c = s;
  while (read(fd, c, 1) > 0 && *c++ != '\n');
  return s > c ? (*c = '\0') : (free(s), NULL);
}
```
