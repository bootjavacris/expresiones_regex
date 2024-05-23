### Elimina todo lo que no sea un email de cada una de las líneas:

**Respuesta regex:** (\w+\.\w+|\w+|\w+\.\w+.-)@\w+\.\w{2,3}

**Respuesta replace:** " "


---
b) Respuesta pensada mejor:

**Respuesta regex:** (?:\s|^)(?![\w.+-]+@[\w\d.]+\.\w{2,4}\b)\S+

**Respuesta replace:** " "

