POPFLEX — PROTOTIPO PARA CLASE

Abrir index.html con Live Server en VS Code.
También puedes ejecutar: python -m http.server 8000
Y abrir: http://localhost:8000

PÁGINAS PRINCIPALES
pages/home.html      Inicio y Best Sellers.
pages/shop.html      Catálogo de ejemplo.
pages/saved.html     Favoritos vacíos, con enlace a Shop.
pages/carrito.html   Carrito de ejemplo.
pages/account.html   Perfil y enlaces de la cuenta.
pages/orders.html    Pedido actual e historial.

Se conserva pages/checkout.html como pantalla adicional del botón CHECKOUT.

CÓMO ESTÁ HECHO
- HTML escrito directamente, sin plantillas ni generación de contenido.
- Componentes básicos de Framework7: navbar, toolbar, card, list, panel y popup.
- css/app.css tiene los estilos separados por pantalla y comentarios.
- js/app.js solamente configura Framework7 y las rutas.
- No necesita npm, React, compilación, bases de datos ni almacenamiento local.
- vendor contiene la librería Framework7 y sus iconos descargados.

ALCANCE
Es un prototipo visual navegable. Productos, perfil, cantidades, precios y
pedidos son datos fijos del ejemplo. Los controles secundarios muestran
una ventana informativa; no cambian cantidades, cuentas ni pedidos.
Todos los productos llevan al mismo carrito de ejemplo.
Shop y Saved son páginas normales con rutas, no ventanas emergentes.
La barra inferior aparece en todas las páginas y permanece fija al desplazar.
Saved muestra un estado vacío; no se guarda una lista de favoritos.
El checkout no envía datos ni cobra. Las fechas del historial son del mockup.

REFERENCIA
Se usaron las cuatro capturas facilitadas en el chat para distribución,
colores y textos. Las fotos son alternativas de la web pública de POPFLEX;
no son las exportaciones exactas del Figma. Fuentes: img/popflex/sources.json.
El contorno azul de la captura de Past orders se trata como selección/foco,
no como borde permanente de la tarjeta.

