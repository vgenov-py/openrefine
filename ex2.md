```python
https://datos.gob.es/es/catalogo/ea0019768-autores-espanoles-en-dominio-publico-en-2022-fallecidos-en-1941
```

1. Crear una columna para los siguientes códigos de identificación **viaf**, **isni**, **wikidata**
2. Convertir en números fecha de nacimiento y fecha de fallecimiento
3. Quitar de los valores en la columna **nombre_de_persona**, el intervalo fnac-ffal utilizando RegEx
```python
# Nogués, Xavier , 1873-1941 --> Nogués, Xavier
```
4. Obtener la media de edad
5. Evaluar normalización de **lugar de nacimiento**
6. Aumentar en 1 cada valor en id BNE
