# tienda-online

Objetivo:
* Listar los productos disponibles
* Seleccionar un producto para comprar
* Agregarlo al carrito de compras
* Ver la información de compra

### Consideraciones

- El desarrollo de debe realizar usando React JS con Typescript
- Utilizar hooks
- Los productos de la tienda deben ser obtenidos mediante REST o GraphQL.
- La tematica de la tienda es libre por lo que los datos pueden ser obtenidos de alguna API libre de su preferencia o de alguna de las siguientes listas: 
  - [APIS REST](https://github.com/public-apis/public-apis)
  - [APIS GRAPHQL](https://github.com/APIs-guru/graphql-apis)
- El wireframe es netamente referencial, la parte visual debe realizarse con una librería de diseño existente. Ejemplo: Chakra UI, Ant Design, Material UI, Tailwind CSS, etc.
- Utilizar componentes reutilizables, orientado a Atomic design
- Utilizar Clean Architecture y principios SOLID

## Historias del usuario

- El usuario puede ver el listado de productos en la página inicial
Los productos cuentan con una miniatura del producto, el nombre, el precio, una breve descripción,
un botón `Agregar`. (Si el API elegida no cuenta con precio, puede generar un precio en base al charCode de la primera letra del producto. Ejemplo: "Avion".charCodeAt(0) = 65 )
- El usuario solo puede agregar como máximo 1 `item` de cada producto y se debería cambiar el botón de `Agregar` por `Eliminar` cuando el producto ya ha sido agregado.
- El usuario puede ver un botón del `Carrito de compras` con la cantidad de productos agregados y el monto total de su compra. (El número y monto debe actualizarse cada vez que se agrega o elimina un porducto)
- El usuario puede hacer clic en el botón `Carrito de compras` para mostrar la compra. Se debería mostrar un menú con la lista de productos y debe permitir eliminar un producto en específico o vaciar todo el carrito.


## Características adicionales

- Agregar test unitarios(Solo agregar 1 test a cualquiera de los componentes desarrollados)
- Agregar mensajes de confirmación al momento de agregar o eliminar un producto(opcional)
- Agregar loaders de carga cuando se obtenga información del API(opcional)


![Carrito-simple-2](https://user-images.githubusercontent.com/13630376/101086340-b6906580-357e-11eb-9864-c7b3413fe43a.jpg)
![Carrito-simple-3](https://user-images.githubusercontent.com/13630376/101086346-ba23ec80-357e-11eb-8b86-9c22948672c3.jpg)
![Carrito-simple](https://user-images.githubusercontent.com/13630376/101086348-babc8300-357e-11eb-9b6b-fa68259083a1.jpg)
