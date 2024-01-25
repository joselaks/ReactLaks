
# Proyecto final curso React José Laks

El proyecto consiste en una tienda de venta de juguetes de marca "Clap".

## Base de datos

Se utilizó una cuenta de Firebase, donde se generó un proyecto denominado "TPReactLaks" con colecciones: Productos y Ordenes


## Funcionalidad

El usuario puede ingresar, navegar por los productos e ir a sus detalles.
Desde el detalle puede ver la descripción, foto y precio e ingresarlo al carrito.
Una vez que el carrito tiene un producto, se puede visualizar un listado completo de lo comprado hasta el momento.
Para concretar la compra se despielga un formulario e ingreso de datos con controles de tipo de dato.
Al clickear "realizar compra" de gusrda en la base de Firebase la información de la compra

## Piezas incluidas

NavBar
Carrito
Checkout
Error
Item
ItemCount
ItemDetail
ItemDetailCounter
ItemList
ItemListCounter
ItemListContainer


## Requisitos cumplidos

Inicio: Al momento de ingresar a la app en la ruta base ‘/’
Se visualiza un set de productos disponibles para la
compra.
Se cuenta con acceso visible a la vista de carrito que debe alojarse en el route /cart.
Se accede a un menú desplegable que contendiene las categorías. Al clickear en una, se navega en a la lista de productos de la misma mediante un route /categories/:categoryId. Ésta involucra la misma vista que el home, pero visualizando sólamente productos de esa categoría.
Flow: Al clickear un ítem del listado se navega a la ruta /item/:id, donde id es el id del item (generado por firebase), y la descripción del producto ( foto, precio, selector de cantidad). Si se ingresa a /item/:id y el producto no existe en firebase, se responde un mensaje que indica que el producto no existe.
El cart tiene acceso durante toda la experiencia y tiene una indicación de la cantidad de items incluidos agregados.
Finalizada la orden, se recibe la id del objeto de firebase.

