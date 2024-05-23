### Basándote en el fichero original, sustituye todos los subdominios de los correos que acaben en cl o ch por gmail (incluidos los que ya tengan dicha casuística):

Por ejemplo:
    - antes -> cabrigo@garmendia.cl
    - después -> cabrigo@gmail.cl

**Respuesta regex:** (\w+\.)(cl)|(\w+\.)(ch)

**Respuesta replace:** gmail.$2

---
b) Respuesta pensada mejor:

**Respuesta regex:** (\w+\.)(cl|ch)

**Respuesta replace:** gmail.$2