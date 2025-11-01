
# Squad44 Server Tool - Wiki del Usuario

## 📋 Tabla de Contenidos
- [Visión General](#visión-general)
- [Instalación](#instalación)
- [Interfaz Principal](#interfaz-principal)
- [Pestaña Servidor](#pestaña-servidor)
- [Pestaña Archivos](#pestaña-archivos)
- [Pestaña Mods](#pestaña-mods)
- [Pestaña Configuración](#pestaña-configuración)
- [Idiomas Soportados](#idiomas-soportados)
- [Comprobación de Actualizaciones](#comprobación-de-actualizaciones)
- [Solución de Problemas](#solución-de-problemas)

## 🎯 Visión General

El *Squad44 Server Tool* es una aplicación completa para administrar servidores dedicados para *Squad 44*. Con una interfaz intuitiva y soporte para varios idiomas, te permite controlar todos los aspectos de tu servidor de manera simple y eficiente.

### Características Principales
- ✅ Control total del servidor (iniciar, detener, reiniciar)
- ✅ Programación de reinicios automáticos
- ✅ Gestión de mods a través de Steam Workshop
- ✅ Instalación y actualizaciones automáticas con SteamCMD
- ✅ Interfaz en portugués, inglés y español
- ✅ Comprobación automática de actualizaciones
- ✅ Consola integrada para monitoreo

## 🚀 Instalación

### Requisitos del Sistema
- Windows 10/11 (64-bit)
- .NET 8.0 Runtime
- Conexión a internet
- Al menos 2 GB de espacio libre en disco

### Pasos de Instalación
1. Descarga la última versión desde la [página de Releases](https://github.com/DX-BR/Squad44ServerTool/releases)
2. Extrae el archivo ZIP en una carpeta de tu elección
3. Ejecuta `Squad44ServerTool.exe` como administrador
4. La aplicación creará automáticamente las carpetas necesarias

## 🖥️ Interfaz Principal

La interfaz está dividida en 4 pestañas principales:

### Menú Superior
- **Archivo**: Limpiar datos guardados y salir de la aplicación
- **Ayuda**: Información sobre el programa y comprobación de actualizaciones

### Barra de Estado
- Muestra la versión actual de la aplicación
- Indica el estado de la conexión a internet

## 🎮 Pestaña Servidor

![Pestaña Servidor](images/server-tab.png)

### Controles Principales
- **Iniciar**: Inicia el servidor dedicado
- **Detener**: Detiene el servidor en ejecución
- **Reiniciar**: Reinicia el servidor (detener + iniciar)

### Opciones de Configuración
- **Actualizar servidor al iniciar**: Verifica actualizaciones antes de iniciar
- **Reinicio automático**: Habilita la programación de reinicios automáticos

### Configuración del Servidor
- **ServerName**: Nombre mostrado en la lista de servidores
- **MaxPlayers**: Número máximo de jugadores (predeterminado: 100)
- **NumReservedSlots**: Espacios reservados para administradores
- **ShouldAdvertise**: Hace que el servidor sea visible públicamente

### Parámetros de Inicio
- **Port**: Puerto principal del servidor (predeterminado: 7780)
- **QueryPort**: Puerto para consultas (predeterminado: 27165)
- **FIXEDMAXTICKRATE**: Tasa de actualización del servidor
- **RANDOM**: Configuración de aleatoriedad
- **-log**: Habilita el registro detallado

### Programación de Reinicios

![Programación](images/schedule.png)

1. Marca **Reinicio Automático**
2. Selecciona la hora deseada (formato 24h)
3. Haz clic en **Programar Reinicio**
4. El contador mostrará el tiempo restante hasta el próximo reinicio

**Consejos:**
- Puedes programar múltiples horarios
- Usa **Eliminar Seleccionado** para eliminar un horario específico
- Usa **Borrar Todos** para eliminar todos los horarios

## 📁 Pestaña Archivos

![Pestaña Archivos](images/files-tab.png)

### SteamCMD e Instalación del Servidor

#### Configuración Inicial
1. Haz clic en **Descargar SteamCMD** (solo necesario una vez)
2. Espera a que se descargue e instale automáticamente
3. Haz clic en **Instalar/Actualizar Servidor**
4. El proceso puede tardar entre 10 y 30 minutos dependiendo de tu conexión

#### Actualizaciones Regulares
- Usa **Instalar/Actualizar Servidor** para mantener el servidor actualizado
- El proceso verifica automáticamente las actualizaciones
- Usa **Detener Tarea** para cancelar una operación

#### Limpieza y Mantenimiento
- **Eliminar SteamCMD**: Elimina SteamCMD (tendrás que descargarlo de nuevo)
- **Eliminar Servidor**: Elimina completamente los archivos del servidor
- **Eliminar Mods**: Elimina todos los mods instalados

### Consola de Monitoreo
La consola muestra en tiempo real:
- Estado de las operaciones
- Progreso de descarga
- Mensajes de error
- Registros del servidor

## 🔧 Pestaña Mods

![Pestaña Mods](images/mods-tab.png)

### Gestión de Mods

#### Agregar Mods
1. Haz clic en **Agregar Mod**
2. Ingresa el ID del mod de Steam Workshop
3. El mod aparecerá en la lista con el estado "No Instalado"

#### Instalar Mods
1. Selecciona los mods deseados de la lista
2. Haz clic en **Instalar Mods**
3. Espera a que se complete la descarga e instalación

#### Eliminar Mods
- **Eliminar Seleccionado**: Elimina el mod seleccionado de la lista
- Para desinstalar: usa **Eliminar Mods** en la pestaña Archivos

### Estado de los Mods
- **Instalado**: Mod descargado y listo para usar
- **No Instalado**: Mod en la lista pero no descargado

**Consejo**: Encuentra los IDs de los mods en la URL de Steam Workshop
- Ejemplo: `https://steamcommunity.com/sharedfiles/filedetails/?id=123456789`
- El ID es: `123456789`

## ⚙️ Pestaña Configuración

![Pestaña Configuración](images/settings-tab.png)

### Tema de la Interfaz
- **Claro**: Interfaz con colores claros
- **Oscuro**: Interfaz con colores oscuros (predeterminado)

### Idioma
- **Portugués (Brasil)**: Idioma predeterminado
- **Inglés (EE.UU.)**: Interfaz en inglés
- **Español (ES)**: Interfaz en español

**Nota**: Usa **Recargar Idiomas** si se agregan nuevos archivos de traducción

### Comportamiento
- **Iniciar con Windows**: Inicia automáticamente con el sistema
- **Minimizar a la bandeja**: Minimiza a la área de notificación

### Funciones
- **Documentación**: Abre esta guía
- **Discord**: Acceso al servidor de soporte
- **GitHub**: Repositorio oficial del proyecto

## 🌍 Idiomas Soportados

### Idiomas Disponibles
- 🇧🇷 **Portugués (Brasil)** - Completo
- 🇺🇸 **Inglés (EE.UU.)** - Completo  
- 🇪🇸 **Español (ES)** - Completo

### Cambiar de Idioma
1. Ve a **Configuración** > **Idioma**
2. Selecciona el idioma deseado
3. La interfaz se actualizará automáticamente

### Archivos de Idioma
Los archivos de traducción están en `languages/`:
- `pt-BR.json` - Portugués
- `en-US.json` - Inglés
- `es-ES.json` - Español

## 🔄 Comprobación de Actualizaciones

### Comprobación Manual
1. Ve a **Ayuda** > **Buscar Actualización**
2. El sistema comprobará si hay una nueva versión en GitHub
3. Si hay una actualización, se abrirá la página de descarga

### Proceso de Actualización
1. Descarga la nueva versión desde la página de releases
2. Cierra la aplicación actual
3. Sustituye los archivos con la nueva versión
4. Tus datos y configuraciones se mantendrán

**Importante**: El sistema no descarga actualizaciones automáticamente por razones de seguridad

## 🛠️ Solución de Problemas

### Problemas Comunes

#### "Error de conexión a internet"
- Verifica tu conexión
- Desactiva temporalmente el antivirus/firewall
- Ejecuta como administrador

#### "SteamCMD no encontrado"
- Usa **Descargar SteamCMD** en la pestaña Archivos
- Verifica si no está bloqueado por el antivirus
- Ejecuta como administrador

#### "El servidor no inicia"
- Verifica que los puertos estén abiertos
- Confirma que el servidor se instaló correctamente
- Revisa los registros en la consola

#### "Mods no cargan"
- Asegúrate de que los mods estén instalados
- Verifica que los IDs sean correctos
- Reinstala los mods si es necesario

### Registros y Diagnóstico
- La consola integrada muestra información en tiempo real
- Los archivos de registro están en la carpeta del servidor
- Usa **Limpiar Datos** para un reinicio completo (¡ten cuidado!)

### Soporte
- 💬 **Discord**: Soporte comunitario
- 🐛 **GitHub Issues**: Reporta errores
- 📧 **Correo Electrónico**: Contacto directo con los desarrolladores

## 📝 Consejos Avanzados

### Optimización del Rendimiento
- Usa SSD para un mejor rendimiento
- Configura FIXEDMAXTICKRATE según el hardware
- Monitorea el uso de CPU y RAM

### Copias de Seguridad y Seguridad
- Haz copias de seguridad de las configuraciones regularmente
- Mantén el servidor actualizado
- Usa contraseñas fuertes para el acceso de administradores

### Automatización
- Configura reinicios automáticos
- Usa scripts personalizados si es necesario
- Monitorea los registros regularmente

---

## 📞 Contacto y Soporte

- **GitHub**: [Squad44ServerTool](https://github.com/DX-BR/Squad44ServerTool)
- **Discord**: [Squad44ServerTool](https://discord.gg/Mz5FHTUPgn)
- **Documentación**: Siempre versión actualizada de este archivo

**Versión de la Wiki**: 1.0  
**Última Actualización**: Octubre 2025

---

*Esta guía es mantenida por la comunidad. ¡Las contribuciones son bienvenidas!*
