# VerdeVidaAPI

## API sobre especies amenazadas.

API Rest encargada de exponer información sobre las especies en la Categoría Amenazadas según la clasificación de la Lista Roja de la UICN en los Departamentos de Boyacá y Cundinamarca, que se encuentra contenida en los archivo en formato JSON: 

1 especies_amenazadas_boyaca.json 
2 especies_amenazadas_cundinamarca.json 

* Expone funciones como servicios, y estos métodos reciben como argumento general el tipo de consulta para así saber cual fuente o archivo de datos usar.
* Adicionalmente según el caso reciben página inicial/final, y/o id del especimen a consultar.
* Utiliza el paquete FastAPI para exponer funciones como servicios web tipo REST.

## tomado de: https://github.com/desaextremo
