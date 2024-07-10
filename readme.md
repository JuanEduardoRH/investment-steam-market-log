# Steam market log - Finalizado


### Demo privada


# Detalles


El proyecto nace por una necesidad acerca de como generar más ingresos en una plataforma de videojuegos, con el objetivo de no invertir dinero (real) y hacer que esto mismo sea sustentable y comprar e invertir en el mercado de dicha plataforma para aumentar mi capital.


Para lograr esto, inspeccione determinadamente la plataforma de `Steam`, el objetivo era hacer una especie de monitoreo las 24 horas del día sobre algunos productos en particular, estos mismos debían tener un alto movimiento de transacciones, ya que mientras sea más alto, mayor es la posibilidad de generar ingresos con esta aplicación.


Logre montar una aplicación con laravel que me permitía actualizar y verificar en todo momento una cantidad determinada de productos por minuto, tomando en cuenta el idioma, moneda y sesión de autenticación para acceder a dicha información, dependiendo de la respuesta de la API, se realizó un filtrado de la información entregada.


Esta información debía ser sanitizada con mucho cuidado, ya que la respuesta venía en HTML, y no todos los datos entregados eran necesario para ser almacenados en la DB, logrando almacenar unos 150M de registros en todo lo que lleva funcionando.


A día de hoy ha sido una aplicación muy útil, pues me ha entregado grandes utilidades (dinero) para invertir en un mercado en donde muchos utilizan dinero real para comprar, y yo solo invertí 72 Hrs de desarrollo y poco tiempo al día cuando requiero aumentar mi capital y comprar cuando se requiere.


## Dependencias del proyecto


- Laravel 10
- Dom Crawler
- Inertia JS
- React v18
- React Query
- Tailwind v3


## Funcionalidades


- Administrador
  - Mantenedor de artículos
    - Crear
    - Listar
    - Habilitar / Deshabilitar 
  - Ver últimos registros de compra (general)
  - Ver detalle de producto
    - Filtro de resultado de búsqueda (cantidad, horas, ordenamiento)
    - Listado de últimas compras
