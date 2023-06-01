# Amazon-Clone-Flutter

Clon de Amazon de pila completa junto con el panel de administración

## Características
- Autenticación por correo electrónico y contraseña
- Persistencia del estado de autenticación
- Búsqueda de productos
- Filtrado de productos (según categoría)
- Detalles del producto
- Valoraciones
- Obtención de la oferta del día
- Carrito de compras
- Pago con Google/Apple Pay
- Ver mis pedidos
- Ver detalles y estado del pedido
- Cerrar sesión
- Panel de administración
           - Ver todos los productos
           - Agregar productos
           - Eliminar productos
           - Ver pedidos
           - Cambiar estado del pedido
           - Ver ganancias totales
           - Ver ganancias por categoría (en gráfico)


## Para ejecutarlo localmente, 
después de clonar este repositorio, dirígete a la carpeta ```flutter-amazon-clone-tutorial``` y sigue los siguientes pasos:
- Crear proyecto y clúster de MongoDB
- Haz clic en "Connect" y sigue el proceso para obtener la URI. Reemplaza la URI de MongoDB en el archivo ```server/index.js``` con la tuya.
- Ve al archivo ```lib/constants/global_variables.dart``` y reemplaza la dirección IP con la tuya.
- Crea un proyecto en Cloudinary y habilita las operaciones sin firmar en la configuración.
- Ve al archivo ```lib/features/admin/services/admin_services.dart``` y reemplaza ```denfgaxvg``` y ```uszbstnu``` con tu nombre de Cloud y la configuración de carga respectivamente.


A continuación, ejecuta los siguientes comandos para ejecutar tu aplicación:

### Server Side
```bash
  cd server
  npm install
  npm run dev (for continuous development)
  OR
  npm start (to run script 1 time)
```

### Client Side
```bash
  flutter pub get
  open -a simulator (to get iOS Simulator)
  flutter run
```

## Tech Used
**Server**: Node.js, Express, Mongoose, MongoDB, Cloudinary

**Client**: Flutter, Provider
    
