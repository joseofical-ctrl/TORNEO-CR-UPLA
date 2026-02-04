⚔️ Arena UPLA 2026 - Torneo Estudiantil
Este proyecto es una plataforma web desarrollada con Astro y Tailwind CSS para la organización y difusión de un torneo de Clash Royale exclusivo para la comunidad de la Universidad Peruana Los Andes (UPLA).

📋 Características del Proyecto
Diseño Responsivo: Optimizado para dispositivos móviles y escritorio, eliminando errores de doble desplazamiento (scroll).

Gestión de Sorteo: Sección dedicada para mostrar los 12 cupos oficiales, pases directos (Byes) y llaves de la Ronda 1.

Contenido Estratégico: Visualización del meta actual (Log Bait), cartas restringidas y mazos recomendados.

Centro de Información: Botón de previsualización y descarga de la Guía Oficial en formato PDF.

Registro Centralizado: Enlace directo a Microsoft Forms para inscripciones validadas con correo institucional.

🎮 Reglas del Torneo
Participantes: Limitado a 12 guerreros.

Nivel: Torre Estándar Nivel 11.

Formato: Eliminación directa 1 vs 1.

Inscripción: S/ 3.00 (Pozo de premio: S/ 20.00).

Cartas Prohibidas: Mega Caballero, Chispitas, Pekka y Bárbaros Élite.

🛠️ Tecnologías Utilizadas
Framework: Astro.

Estilos: Tailwind CSS.

Tipografía: Lilita One (vía Google Fonts).

Iconografía: Emojis y recursos gráficos de RoyaleAPI.

🚀 Configuración y Ejecución
Instalar dependencias:

Bash
npm install
Ejecutar en modo desarrollo:

Bash
npm run dev
Construir para producción:

Bash
npm run build
📂 Estructura de Archivos Clave
src/pages/index.astro: Página principal con toda la lógica del torneo.

src/layouts/layout.astro: Estructura base y configuración del viewport responsivo.

public/Guíaoficial.pdf: Documento con el reglamento detallado y FAQ.
