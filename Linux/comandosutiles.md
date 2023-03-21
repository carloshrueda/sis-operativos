![Consola linux](https://th.bing.com/th/id/OIP.Zg6Q71EVQPclaXHa1nk2-QAAAA?pid=ImgDet&rs=1)

# COMANDOS UTILES

Aqui listo una serie de comandos, snippets y trucos útiles en el sistemas operativo ```Linux```.

## Alias
Listo una serie de alias utiles para el trabajo diario

### Buscar un archivo
```bash
alias findd="ls -la ~/ | grep $1"
```

### Limpiar pantalla
```bash
alias cl="clear"
```

### Listar 20 comandos más usados
```bash
alias masusados='history | awk '\'' {print $2}'\'' | sort | uniq -c | sort -nr | head -n 20'
```
