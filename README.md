### Hey!

Im Felix, 21 from Austria 🇦🇹 and I study Software Development 🖥 at 42 Heilbronn 🇩🇪
!
- :telescope: I’m currently working on 42 projects :whale:
- ⌨️ I’m currently working on building the best possible layout for [my custom keyboard](https://github.com/FelixBrgm/goos)
- 🌱 I’m currently learning Rust ⚙️
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
