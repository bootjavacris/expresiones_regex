### Comprueba si existen palabras repetidas en el siguiente ejercicio: 
```bash
coco coco cocodrilo coco cocodrilo cocodrilo
```
**Respuesta:**
>coco|drilo

### 📌Como seleccionar varias líneas
Encontrarlas mediante a grupos con reflexión y con el nombre del grupo sin \1 eliminar una de ellas y poner el texto con la primera letra de cada palabra en mayúsculas
```bash
hola mundo
hola mundo
```
**Respuesta** regex
>((\w*)\s(\w*)\n)(\w*)\s(\w*)

**Respuesta** replace:
>\\u$1 \u$2\n\u$3 \u$4

