# Glitch Cat
## Descripcion
Our flag printing service has started glitching!

Additional details will be available after launching your challenge instance.
## Solucion

```
angel@MSI:~$ nc saturn.picoctf.net 64987
'picoCTF{gl17ch_m3_n07_' + chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35) + '}'
```
python
```
chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35)
'bda68f75'
```

picoCTF{gl17ch_m3_n07_bda68f75}
## Notas

## Referencias