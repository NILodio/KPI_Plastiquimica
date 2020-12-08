# Project for maintenance KPI

# Set up
1. ``python -m venv plasti``
2. ``source activate plasti/bin/activate``
3. ``pip install requirements``

# TODO:
1. Cronologico a AWS
   1. Store procedure (Function) que devuelva el proceso diario
   2. Store procedure (Function) que devuelva el proceso semanal (Queries completas)
   3. Store procedure (Function) que devuelva el proceso mensual (Queries completas)
2. Crear Django y empezar con un template de bootstrap.
   1. Conectar Django con Postgres del AWS y un Postgres propio para los usuarios.
   2. Crear la parte de login usando django authentication

## Backlog
1. Creacion de tablas diarias y semanales. Para optimizacion de queries semanales y mensuales
2. Cuantos usuarios lo pueden estar usando al tiempo.
3. Tablas auxiliares
   1. Maquinas (Pueden crear)
   2. Usuarios (Pueden crear y modificar)