
### Desfibriladores fuera del ámbito sanitario

```python
 https://datos.comunidad.madrid/catalogo/dataset/35609dd5-9430-4d2e-8198-3eeb277e5282/resource/1dd3e628-6f06-45e5-bb7b-36d6e6e557cf/download/desfibriladores_externos_fuera_ambito_sanitario.csv
```
```python
https://docs.openrefine.org/manual/expressions#variables
```

1. Convertir direccion_coordenada_x mediante interfaz
2. Convertir direccion_coordenada_y mediante una expresión
3. Agregar columna x,y
```python
(40302,498851)
```
4. Agrupar horarios de disponibilidad
5. Colocar Horario no disponible en todo horario sin valores
6. Unir direccion_via_codigo, direccion_via_nombre y direccion_portal_numero (title)
```python
Calle De Rios Rosas, 23
```
7. De las columnas mencionadas en el punto 6, dejar sólo la que contiene toda la información
8. Agregar una columna url_id que agregue la siguiente URL a cada codigo_dea
```python
https://www.deamadrid.com/id/<codigo_dea>
```
9. Modificar columna direccion_ubicacion, si es privada upper si es pública lower
10. Exportar en xls
