# 3- Magikarp Ground Mission
## Descripcion
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin.

Additional details will be available after launching your challenge instance.
## Solucion

```
angel@MSI:~$ ssh ctf-player@wily-courier.picoctf.net -p 62919
ctf-player@pico-chall$ cd /
ctf-player@pico-chall$ ls
2of3.flag.txt  boot       dev  home                      lib    media  opt   root  sbin  sys  usr
bin            challenge  etc  instructions-to-3of3.txt  lib64  mnt    proc  run   srv   tmp  var
ctf-player@pico-chall$ cd challenge
ctf-player@pico-chall$ ls
metadata.json
ctf-player@pico-chall$ cat metadata.json
{"flag": "picoCTF{xxsh_0ut_0f_//4t3r_0b24fc4f}", "password": "8c606eb1"}ctf-player@pico-chall$ Connection to wily-courier.picoctf.net closed by remote host.
Connection to wily-courier.picoctf.net closed.

```
picoCTF{xxsh_0ut_0f_//4t3r_0b24fc4f}
## Notas

## Referencias