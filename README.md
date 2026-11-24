# Registro de Capturas / Catch Tracker

Gestor minimalista y offline para el seguimiento de capturas en partidas Nuzlocke de Pokémon. Optimizado para navegadores de escritorio y dispositivos móviles.

Minimalist, offline-first tracker for logging catches in Pokémon Nuzlocke runs. Optimized for desktop browsers and mobile devices.

---

## Español

### Características
* **Archivo único:** Todo el código reside en `index.html`.
* **Almacenamiento local:** Guarda múltiples partidas en el navegador mediante `localStorage`.
* **Copias de seguridad:** Exportación e importación en formato JSON a través del portapapeles o archivos `.txt`.
* **Integración con PokéAPI:** Obtención automática de sprites y habilidades por especie.
* **Control de reglas:**
  * Cinco categorías: *Rutas*, *Cuevas, Montes y Torres*, *Otros lugares*, *Cementerio* y *Baneado*.
  * Registro de zonas falladas escribiendo `"no"` como especie.
  * Prevención de duplicados por zona y especie, con opción de **Captura Especial** para excepciones.
* **Bilingüe:** Cambio dinámico entre Español e Inglés (interfaz y sugerencias de campos).

### Arquitectura
Todo el proyecto está contenido en un único archivo por simplicidad de desarrollo y portabilidad máxima. Al evitar dependencias de compilación o estructuras de carpetas, el archivo puede moverse, compartirse y ejecutarse localmente en cualquier dispositivo sin configuración previa.

### Propiedad Intelectual
Herramienta gratuita desarrollada para la comunidad sin ánimo de lucro. Todos los derechos de las imágenes, sprites y nombres pertenecen a Nintendo, Game Freak y The Pokémon Company.
[PokéAPI](https://pokeapi.co/).

---

## English

### Features
* **Single file:** All code lives inside `index.html`.
* **Local storage:** Saves multiple runs in the browser via `localStorage`.
* **Backups:** JSON export and import via clipboard or `.txt` files.
* **PokéAPI integration:** Automatic fetching of sprites and abilities by species.
* **Rule enforcement:**
  * Five categories: *Routes*, *Caves, Mountains & Towers*, *Other Locations*, *Graveyard*, and *Banned*.
  * Logging of failed encounters by entering `"no"` as the species.
  * Duplicate prevention per location and species, with a **Special Catch** toggle for exceptions.
* **Bilingual:** Dynamic switch between Spanish and English (UI and input placeholders).

### Architecture
The entire project is contained within a single file for quick-and-dirty simplicity and maximum portability. Avoiding build steps or folder structures allows the file to be moved, shared, and executed locally on any device without setup.

### Intellectual Property
Free, non-profit tool developed for the community. All rights to images, sprites, and names belong to Nintendo, Game Freak, and The Pokémon Company.
[PokéAPI](https://pokeapi.co/) library.
