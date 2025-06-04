📦 Base de Datos Northwind (Adaptada para PostgreSQL)
# UF1472_Tarek

``` bash
C:\Users\ademo>psql -U postgres -d postgres
Contraseña para usuario postgres:

psql (17.4)
ADVERTENCIA: El código de página de la consola (850) difiere del código
            de página de Windows (1252).
            Los caracteres de 8 bits pueden funcionar incorrectamente.
            Vea la página de referencia de psql «Notes for Windows users»
            para obtener más detalles.
Digite «help» para obtener ayuda.

postgres=# createdb northwind_curso
postgres-# psql -d northwind_curso -f northwind_modificado.sql
postgres-# \q

C:\Users\ademo>createdb -U postgres northwind_curso
Contraseña:
```
