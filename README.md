### Hey!

Im Felix, 20 from Austria š¦š¹ and I study Software Development š„ at 42 Heilbronn š©šŖ
!
- š­ Iām currently working on my startup š
- š± Iām currently learning Flutter š¦
- š This is my .bashrc: 
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
- ā” Favorite bit of code: 
```
// It's a super short version of get_next_line in C.
char *get_next_line(int fd)
{
  char *s = malloc(10000), *c = s;
  while (read(fd, c, 1) > 0 && *c++ != '\n');
  return s > c ? (*c = '\0') : (free(s), NULL);
}
```
