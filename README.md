# LorHels Music

🎨 1. Interfaz y Experiencia de Usuario (El "Front-End")
Diseño Profesional: Tienes una aplicación de una sola página (SPA) fluida, construida con Tailwind CSS, usando un esquema de colores azul corporativo y oscuro (Dark Mode por defecto) con efectos de brillo (Glow) muy modernos.

Navegación sin cortes: Los usuarios pueden buscar música, entrar a su biblioteca o cambiar configuraciones y la música nunca se detiene.

Generación Dinámica: La app lee tu base de datos y crea automáticamente tarjetas para las canciones, una cuadrícula de géneros musicales por colores, y burbujas de artistas.

Buscador Inteligente: Filtra canciones en tiempo real por título o artista mientras el usuario escribe.

👤 2. Sistema de Cuentas y Monetización
Roles de Usuario: La base de datos (Firebase Firestore) distingue inteligentemente entre usuarios Básicos, Premium y Administradores.

Muro de Pago (Paywall): Si un usuario básico intenta usar funciones avanzadas, choca con un muro que le ofrece mejorar su cuenta.

Flujo de Venta por WhatsApp: Un sistema de pago manual muy astuto donde el usuario ve tus datos bancarios y, con un clic, se abre su WhatsApp con un mensaje preescrito para enviarte el comprobante.

Caducidad Automática: El sistema cuenta los días; si a un usuario se le acaba su mes Premium, la app lo detecta al iniciar sesión y lo devuelve a Básico automáticamente.

🎧 3. El Motor del Reproductor Musical
Controles Completos: Barra de progreso, control de volumen, Play/Pausa, Siguiente y Anterior.

Modos de Reproducción: Un sistema avanzado que soporta Aleatorio (Shuffle) y tres estados de Repetición (Apagado, Repetir toda la lista, Repetir una sola canción en bucle).

Modo Offline (¡Nivel Dios!): Los usuarios Premium pueden descargar las canciones en una bóveda secreta del navegador (Cache API) y escucharlas sin conexión a internet.

📚 4. Funciones Sociales y Biblioteca
Favoritos: Los usuarios pueden dar "Corazón" a las canciones para guardarlas en su perfil.

Playlists Personalizadas: Creación de listas de reproducción públicas o privadas.

Viralidad: Generación de enlaces mágicos (?playlist=ABC) que puedes enviar por WhatsApp y, al abrirlos, la app carga automáticamente esa lista de reproducción.

📻 5. La Joya de la Corona: Emisora 24/7
Sincronización Global: Una "Radio en Vivo" que usa trucos matemáticos con el tiempo de Firebase para que todos los usuarios del mundo escuchen el mismo segundo de la misma canción al mismo tiempo.

Control de Cabina: Como Administrador, puedes iniciar o detener la radio y elegir qué Playlist específica será la "programación del día".

Protección Anti-trampas: Al sintonizar la radio, la barra de tiempo y los botones de saltar canción se bloquean para simular una experiencia de transmisión real.

🛠️ 6. Panel de Administración
Gestión de Peticiones: Los usuarios pueden pedirte canciones, y tú puedes aprobarlas (o borrarlas) desde un panel especial.

Publicación Directa: Un formulario exclusivo para que subas música directamente al catálogo sin pasar por las peticiones.

Otorgar Premium: Un buscador donde pones el correo de un cliente y le activas su mes Premium con un solo clic.
