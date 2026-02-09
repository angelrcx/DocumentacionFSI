# Nice netcat
## Descripcion
There is a nice program that you can talk to by using this command in a shell:

Additional details will be available after launching your challenge instance.
There is a nice program that you can talk to by using this command in a shell:$ nc wily-courier.picoctf.net 56570, but it doesn't speak English...
## Solucion
python
```
list
[112, 105, 99, 111, 67, 84, 70, 123, 103, 48, 48, 100, 95, 107, 49, 116, 116, 121, 33, 95, 110, 49, 99, 51, 95, 107, 49, 116, 116, 121, 33, 95, 101, 57, 99, 56, 53, 125, 10]
for i in list:
    print(chr(i))

    
p
i
c
o
C
T
F
{
g
0
0
d
_
k
1
t
t
y
!
_
n
1
c
3
_
k
1
t
t
y
!
_
e
9
c
8
5
}
```

picoCTF{g00d_k1tty!_n1c3_k1tty!_e9c85}
## Notas

## Referencias

