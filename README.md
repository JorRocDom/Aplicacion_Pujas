📱 Aplicación de Subastas en Directo (Live Auctions App)
📌 Descripción del proyecto

Este proyecto consiste en el desarrollo de una aplicación móvil de subastas en directo, inspirada en un modelo híbrido entre plataformas de subastas online y aplicaciones de streaming en tiempo real.

La aplicación permite a los vendedores subastar productos en vivo, mientras los usuarios pueden pujar en tiempo real, interactuar mediante chat y seguir la evolución de la subasta de forma inmediata. El enfoque principal del proyecto es la experiencia en directo, la rapidez en la interacción y la sensación de evento en tiempo real.

La aplicación está desarrollada con React y sigue una arquitectura modular y escalable, orientada a una experiencia de usuario moderna, clara y minimalista.

🎯 Objetivo principal

Crear una aplicación móvil que:

Centralice subastas en tiempo real.

Permita interacción directa entre compradores y vendedores.

Priorice la inmediatez, la competitividad y la experiencia live.

Diferencie claramente entre subastas con streaming y sin streaming.

🔴 Tipos de subasta en directo

La aplicación soporta dos modalidades de subasta live:

1. Subasta Live con cámara

El vendedor transmite en streaming de vídeo.

Los usuarios pueden ver el producto en tiempo real.

Incluye chat en directo, historial de pujas y contador de tiempo.

Indicador visual “EN DIRECTO 🔴”.

2. Subasta Live sin cámara

No hay transmisión de vídeo.

Se muestra la imagen o carrusel del producto.

Mantiene el sistema de pujas, chat en vivo y contador.

Ideal para subastas rápidas o productos ya conocidos.

Ambos modos comparten la misma lógica de puja en tiempo real, adaptando únicamente el componente visual superior.

🧭 Navegación general de la aplicación

La app utiliza una navegación moderna con barra inferior (Bottom Tab Bar), compuesta por cinco secciones principales:

Home

Buscar

Directo

Favoritos

Perfil

El botón Directo actúa como eje central de la aplicación, dando acceso inmediato a las subastas en vivo.

🏠 Pantallas principales
Home

Subastas en directo destacadas.

Subastas próximas con recordatorios.

Subastas destacadas.

Categorías.

Subastadores populares.

Buscar

Barra de búsqueda.

Filtros por:

Categoría.

Precio.

Tiempo restante.

Tipo de subasta (con cámara / sin cámara).

Resultados en tiempo real.

Directo

Feed de subastas en vivo.

Priorización de subastas activas.

Acceso rápido a eventos en curso.

Favoritos

Subastas guardadas.

Subastadores seguidos.

Acceso a notificaciones.

Perfil

Gestión del perfil de usuario.

Historial de pujas.

Compras realizadas.

Métodos de pago y direcciones.

Soporte y preguntas frecuentes.

🎥 Pantalla de Subasta en Directo (núcleo de la app)

La pantalla de subasta en directo es el elemento central de la aplicación y está diseñada para maximizar la rapidez y claridad al pujar.

Incluye:

Componente superior adaptable:

Vídeo en streaming (si hay cámara).

Imagen del producto (si no hay cámara).

Precio actual destacado.

Contador de tiempo restante.

Botón principal “PUJAR +X€” altamente visible.

Campo de puja manual.

Historial de pujas en tiempo real.

Chat en directo estilo streaming.

Número de usuarios conectados.

Sistema de alertas (“Te han superado la puja”).

🏆 Estados post-subasta

Has ganado la subasta
Resumen del producto, precio final y acceso al pago.

Has perdido la subasta
Precio final y recomendaciones de subastas similares.

🛍️ Funcionalidades para compradores

Pujas en tiempo real.

Chat en directo.

Favoritos y recordatorios.

Historial de pujas.

Gestión de compras y pagos.

Seguimiento de vendedores.

🧑‍💼 Funcionalidades para vendedores

Perfil público con reputación y seguidores.

Dashboard de subastas:

Activas.

Próximas.

Finalizadas.

Creación de subastas personalizadas.

Control de subastas en directo.

Moderación del chat.

Visualización de pujas en tiempo real.

⭐ Funcionalidades extra (opcionales)

Chat privado comprador–vendedor.

Valoraciones tras la compra.

Sistema de reportes de usuarios y subastas.

🎨 Diseño y experiencia de usuario

La aplicación sigue un diseño:

Moderno y minimalista.

Basado en cards, contadores grandes y botones llamativos.

Enfocado en el directo y la acción rápida.

Optimizado para dispositivos móviles.

🚀 Tecnologías

Frontend: React

Arquitectura: Componentes reutilizables y estado global

Enfoque: Tiempo real, experiencia live y escalabilidad

(Las tecnologías backend y de streaming se definirán en fases posteriores del proyecto.)