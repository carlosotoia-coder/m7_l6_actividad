# Actividad N° 6 – Implementación de Operaciones CRUD con Django

## ¿Cómo funciona el flujo completo de una operación CRUD?

El flujo CRUD en Django comienza con la solicitud del usuario a través de una URL.
Dicha URL está asociada a una vista, la cual se encarga de ejecutar la lógica necesaria.

Las vistas interactúan con el modelo utilizando el ORM de Django para crear, leer,
actualizar o eliminar registros en la base de datos.

Luego, la vista envía la información a un template, el cual se encarga de mostrar los
datos al usuario. En el caso de formularios, se utiliza protección CSRF para garantizar
la seguridad de la aplicación.

## ¿Qué aprendí sobre el enrutamiento y los parámetros dinámicos en URLs?

Aprendí que Django permite definir rutas claras y ordenadas mediante el archivo urls.py.
Los parámetros dinámicos, como <int:id>, permiten identificar registros específicos
dentro de una vista.

Esto facilita operaciones como editar o eliminar elementos, ya que se puede acceder
directamente a un objeto según su identificador, manteniendo un flujo de navegación
estructurado y seguro.
