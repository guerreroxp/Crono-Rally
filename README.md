# 🏁 Baja Atacama Series - Control de Tiempos en Vivo ⏱️

![Estado](https://img.shields.io/badge/Status-En%20Vivo-success?style=for-the-badge&logo=github)
![Licencia](https://img.shields.io/badge/Licencia-MIT-blue?style=for-the-badge)
![Tecnologías](https://img.shields.io/badge/Hecho%20con-HTML5%20%7C%20CSS3%20%7C%20JS-orange?style=for-the-badge)

Una plataforma web ultra-robusta, ligera y responsiva diseñada para el seguimiento en tiempo real de los cronometrajes del **Baja Atacama Series**. El sistema se conecta de manera automática a los datos oficiales de la competencia para ofrecer resultados instantáneos tanto en dispositivos móviles como en pantallas de escritorio.

---

## ✨ Características Principales

* 🔄 **Sincronización en Tiempo Real:** Conexión directa a la base de datos de tiempos mediante Google Sheets (formato CSV) con refresco automático cada 30 segundos o bajo demanda.
* 🎛️ **Filtros Avanzados e Interactivos:** * Filtrado instantáneo por categorías de competición.
  * Selector dinámico por etapas (**1° EE**, **2° EE** o **Clasificación General Total**).
* ⚖️ **Lógica de Carrera Estricta:** Reordenamiento automático de posiciones según la etapa seleccionada, enviando los estados especiales (`DNF`, `DNS`, vacíos) al final de la tabla de forma inteligente.
* 📱 **Diseño Adaptativo (Responsive):** Interfaz optimizada con una disposición de logos fluida (Disposición horizontal en PC / Bloque inferior para auspiciadores en móviles).
* 🎨 **Estética de Competición:** Interfaz oscura basada en *Glassmorphism* (efecto cristal) que facilita la lectura bajo condiciones de luz extrema en terreno.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica avanzada.
* **CSS3 Nativo:** Animaciones fluidas, microtransiciones, variables de entorno (`:root`) y diseño adaptativo a través de Media Queries (sin dependencias pesadas de frameworks).
* **JavaScript (Vanilla):** Procesamiento asíncrono de strings (`Fetch API`) para parsear datos CSV en caliente y lógica de ordenamiento algorítmico.

---

## 🚀 Instalación y Despliegue Local

Al ser una aplicación basada puramente en el lado del cliente (Client-Side), no requiere de servidores complejos ni compilaciones:

1. **Clonar el repositorio o descargar los archivos:**
   ```bash
   git clone [https://github.com/TU_USUARIO/baja-atacama-tiempos.git](https://github.com/TU_USUARIO/baja-atacama-tiempos.git)
