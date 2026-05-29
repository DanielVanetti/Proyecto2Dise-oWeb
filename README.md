# VINOLILLO - Tienda de Vinos

URL del sitio publico en Host: 

---

**Desarrolladores:**
- Daniel González Picado
- Josué Solórzano Ordóñez

---

## Descripción del Proyecto

**VINOLILLO** es un boceto web de comercio electrónico (E-commerce) para la gestión y venta de vinos, destilados, cervezas y licores. El proyecto es desarrollado como **Proyecto 2 de Diseño de Programación**, utilizando HTML5, CSS3 y JavaScript para crear una interfaz moderna y responsive.

El sistema permite a los usuarios navegar por un catálogo de productos premium, visualizar detalles específicos de cada artículo, agregar productos al carrito de compras y proceder al checkout.

---

## Estructura del Proyecto

```
Vinolillo/
├── VinolilloHomePage.html          # Página de inicio principal
├── VinolilloCatalogPage.html       # Catálogo de productos con filtros
├── ProducDetailPage.html           # Detalle individual de productos
├── CartPage.html                   # Carrito de compras
├── CheckoutPage.html               # Resumen y proceso de pago
├── css/
│   └── vinolillo.css               # Sistema de diseño y estilos globales
├── img/                            # Imágenes de productos (.avif optimizadas)
└── README.md                       # Este archivo

```

---

## Páginas Principales

### **Página de Inicio** (`VinolilloHomePage.html`)
- Hero section con imagen de portada
- Sección "Selección del Sommelier" con productos destacados
- Newsletter para suscripción
- Navegación principal a otras secciones

### **Catálogo** (`VinolilloCatalogPage.html`)
- Listado completo de productos
- Filtros avanzados:
  - Rango de precio
  - Categoría (Vinos Tintos, Blancos, Espumantes, etc.)
  - País de origen
  - Variedad/Cepa
  - Marca/Bodega
  - Ofertas
- Búsqueda y ordenamiento
- Paginación
- Integración con carrito

### **Detalle de Producto** (`ProducDetailPage.html`)
- Información completa del producto
- Galería de imágenes
- Descripción detallada
- Especificaciones (alcohol %, región, bodega, etc.)
- Opciones de cantidad y agregar al carrito
- Productos relacionados

### **Carrito de Compras** (`CartPage.html`)
- Visualización de productos agregados
- Actualización de cantidades
- Eliminación de artículos
- Cálculo de totales (subtotal, impuestos, total)
- Botón para proceder al checkout

### **Checkout** (`CheckoutPage.html`)
- Resumen de compra
- Formulario de información del cliente
- Datos de envío
- Método de pago
- Confirmación de orden

### **Panel de Administración** (`/admin/`)
- **Dashboard**: Estadísticas y resumen general
- **Gestión de Marcas**: CRUD de bodegas y viñedos
- **Gestión de Productos**: Inventario completo
- **Nueva Bodega**: Formulario para agregar nuevas marcas
- **Nuevo Producto**: Formulario para crear productos

---

## Licencia

Este proyecto fue desarrollado como parte del **Proyecto 2 de Diseño de Programación**. Todos los derechos reservados © 2026.

---

## Contacto

**Desarrolladores:**
- Daniel González Picado
- Josué Solórzano Ordóñez

---

**Última actualización:** Mayo 2026
**Versión:** 1.0.0
