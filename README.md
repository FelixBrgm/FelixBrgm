### Servus!
I'm Felix, 21 from Austria 🇦🇹 and I build things and communities at 42 Vienna as Pedagogy Co-Lead

**I love complex systems which brought me to create:**
- ⚙️ a [kernel in rust](https://github.com/kfs)
- ⌨️ a [custom keyboard with custom layout](https://github.com/FelixBrgm/goos)

**🎛 minimal .bashrc so that I can copy it when i need it:**
```
// .bashrc from FelixBrgm
export PS1="\W> "
alias ll="ls -la"

# To kill a process that uses a port
kp(){ 
kill $(lsof -ti tcp:$1);
}
```
- ⚡ Favorite bit of code: 
```
// It's a super short version to get a line from a fd per function call in C.
char *get_next_line(int fd)
{
  char *s = malloc(10000), *c = s;
  while (read(fd, c, 1) > 0 && *c++ != '\n');
  return c > s ? (*c = '\0', s) : (free(s), NULL);
}
```
