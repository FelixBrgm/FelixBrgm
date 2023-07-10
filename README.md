### Hey!

Im Felix, 20 from Austria 🇦🇹 and I study Software Development 🖥 at 42 Heilbronn 🇩🇪
!
- 🔭 I’m currently working on [ft_transendence](https://github.com/FelixBrgm/42-ft_transendence) 🐳
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
alias ll="ls -la"
alias ld="echo && ls | cat && echo"
alias n="norminette"

alias di="bash /Users/fbruggem/docker_valgrind_setup/init_docker.sh"
alias db="docker build -t valgrind - < /Users/fbruggem/docker_valgrind_setup/valgrind"
alias dv='docker run -ti -v $PWD:/code -v "/Users/fbruggem/docker_valgrind_setup/root":/root valgrind bash'

alias clean='bash ~/42toolbox/cleaner.sh'
alias rs_clean='find . -type f -name "Cargo.toml" -execdir cargo clean \;'

export PATH=$HOME/goinfre/.brew/bin:$PATH
export PS1="\W> "
export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
. "$HOME/.cargo/env"
