### Servus!
I'm Felix, 21 from Austria 🇦🇹 and I build things and communities at 42 Vienna as Pedagogy Co-Lead

**I love complex systems which brought me to create:**
- ⚙️ a [kernel in rust](https://github.com/kfs)
- ⌨️ a [custom keyboard with custom layout](https://github.com/FelixBrgm/goos)
- 🚀 [Coding Challengase](https://github.com/42-Dash)
- 🎛 This is my .bashrc: 
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
// It's a super short version of get_next_line in C.
char *get_next_line(int fd)
{
  char *s = malloc(10000), *c = s;
  while (read(fd, c, 1) > 0 && *c++ != '\n');
  return c > s ? (*c = '\0', s) : (free(s), NULL);
}
```
