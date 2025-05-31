# CargaDimensionesProducto
1. Clonar el [Repositorio](https://github.com/rauldmennys/CargaDimensionProducto.git)
2. Restaurar backup Demo
    1. Crear Procedimiento almacenado que movera los datos hacia 
       el staging en DemoDW
        1. Load_StagingProduct.sql
3. Crear Cascaron DemoDW
4. En DemoDW Crear Esquema Int
5. Crear Objetos que pertenecen a ese esquema
    1. Crear Tablas de Linage y IncrementalLoads
    2. Crear Procedimientos almacenados de utileria
       1. **Get_LastLoadedDate.sql**
       2. **Get_LineageKey.sql**
6. Con esto en su Lugar podemos empezar con el procedimiento descrito
   en la guia.
