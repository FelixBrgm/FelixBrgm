### Hey!

Im Felix, 21 from Austria 🇦🇹 and I study Software Development 🖥 at 42 Heilbronn 🇩🇪
!
- 🔭 I’m currently working on [ft_transendence](https://github.com/FelixBrgm/42-ft_transendence) 🐳
- ⌨️ I’m currently working on building the best possible layout for [my custom heyboard](https://github.com/FelixBrgm/rae-dux)
- 🌱 I’m currently learning Rust ⚙️
- 🎛 This is my .bashrc: 
```
// .bashrc from FelixBrgm
export PS1="\W> "
alias ll="ls -la"
alias ld="echo && ls | cat && echo"

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
  return s > c ? (*c = '\0') : (free(s), NULL);
}
```
