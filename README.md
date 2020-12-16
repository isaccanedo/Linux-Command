# Linux-Command

#### Coisas importantes para lembrar

- Linux é um sistema que diferencia maiúsculas de minúsculas.
- O Linux tem uma conta de superadministrador "root".
- "root" é a conta máxima que pode ser criada, excluída, modificada e alterada do sistema

#### Linux File System

![linux-filesystem](https://github.com/isaccanedo/Linux-Command/blob/master/linux.png)

- Commands = /usr/bin
- Attached Device = /dev
- Applications = /etc, /var

### Commands

- Check if port is in use

      sudo lsof -i -P -n | grep LISTEN

### Netstat command

- -a : Shows all sockets
- -p : Show related PID
- -t : TCP
- -u : UDP

      netstat -ptau

### Reference

- https://en.wikipedia.org/wiki/List_of_Unix_commands
