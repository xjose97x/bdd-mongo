# Flicks4U (MongoDB)
### Integrantes: Christian Samaniego, Miguel Brito, José Escudero

## Antes de empezar
Se debe crear una base de datos en MongoDB.
Recomendamos llamarla `Flicks4U` y posteriormente acceder a ella con el siguiente comando:

```use Flicks4u```

## Orden de ejecucion
Se debe copiar el contenido de estos archivos y pegar en `mongosh`.

1. empleados.json (Crea la coleccion `Empleados` e inserta datos iniciales)
2. peliculas.json (Crea la coleccion `Peliculas` e inserta datos iniciales)
3. salas.json (Crea la coleccion `Salas` e inserta datos iniciales)
4. funciones.json (Crea la coleccion `Funciones` e inserta datos iniciales)
5. reporte_general.json (Crea la vista `ReporteGeneral`)
6. reporte_peliculas_aventura.json (Crea la vista `ReportePeliculasAventura`)
7. reporte_empleados_limpieza.json (Crea la vista `ReporteEmpleadosLimpieza`)

## Colecciones

### Empleados
Se puede ver sus documentos con el siguiente comando  `db.Empleados.find()`

### Peliculas
Se puede ver sus documentos con el siguiente comando  `db.Peliculas.find()`

### Salas
Se puede ver sus documentos con el siguiente comando  `db.Salas.find()`

### Funciones
Se puede ver sus documentos con el siguiente comando  `db.Funciones.find()`

## Vistas

### Reporte general
Se puede ver sus documentos con el siguiente comando  `db.ReporteGeneral.find()`

### Reporte Peliculas Aventura
Se puede ver sus documentos con el siguiente comando  `db.ReportePeliculasAventura.find()`

### Reporte Empleados Limpieza
Se puede ver sus documentos con el siguiente comando  `db.ReporteEmpleadosLimpieza.find()`