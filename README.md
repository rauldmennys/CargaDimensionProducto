# CargaDimensionesProducto
1. Clonar el Repositorio 
2. Restaurar backup Demo
    a. Crear Procedimiento almacenado que movera los datos hacia 
       el staging en DemoDW
        Load_StagingProduct.sql
3. Crear Cascaron DemoDW
4. En DemoDW Crear Esquema Int
5. Crear Objetos que pertenecen a ese esquema
    a. Crear Tablas de Linage y IncrementalLoads
    b. Crear Procedimientos almacenados de utileria
       Get_LastLoadedDate.sql
       Get_LineageKey.sql
6. Con esto en su Lugar podemos empezar con el procedimiento descrito
   la guia.