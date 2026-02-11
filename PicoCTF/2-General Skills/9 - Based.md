# Based
## Descripcion
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337?

Additional details will be available after launching your challenge instance.
## Solucion
picoCTF{learning_about_converting_values_6c3Fb625}
python
```
>>> bin = "01110000 01101001 01100101"
>>> "".join(chr(int(b,2)) for b in bin.split())
'pie'
>>> oc = "155 141 160"
>>> "".join(chr(int(b,8)) for b in oc.split())
'map'
>>> he = "736f636b6574"
>>> bytes.fromhex(he).decode('utf-8')
'socket'
```

## Notas

## Referencias