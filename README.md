# FlooderX - Herramienta de Ataques de Red (Flood UDP y TCP)

**FlooderX** es una herramienta diseñada para realizar ataques de *flooding* de red mediante el envío masivo de paquetes UDP o TCP a un servidor específico. Es útil para realizar pruebas de resistencia de redes y servidores, permitiendo simular condiciones extremas de tráfico.

## Funcionalidades principales:

- **Soporte para UDP y TCP**: Puedes elegir entre usar el protocolo UDP o TCP para enviar paquetes al servidor de destino.
- **Envío masivo de paquetes**: Envia paquetes continuamente hasta que se detenga el proceso, con una actualización de cuántos paquetes se han enviado en tiempo real.
- **Soporte para múltiples tareas**: Permite ejecutar múltiples tareas asíncronas para simular un ataque masivo desde diferentes hilos, aumentando la carga en el servidor de destino.

## Características adicionales:

- **Resolución automática de dominios**: Si proporcionas un nombre de dominio, FlooderX resolverá automáticamente la IP asociada.
- **Visualización de paquetes enviados**: Muestra el número total de paquetes enviados cada 5 segundos para monitorear el progreso del ataque.
- **Manejo de errores**: Muestra mensajes claros de error en caso de que no se pueda establecer la conexión con el servidor.

## Requisitos:

- **.NET 8.0**: FlooderX está construido sobre .NET 8.0, por lo que es necesario tener la versión adecuada de .NET instalada en tu máquina para ejecutar el archivo `FlooderX.exe`.

## Instrucciones de uso:

1. **Descargar y ejecutar**: Simplemente descarga el archivo `.exe` y ejecútalo en tu máquina.
2. **Proveer la IP del servidor**: Introduce la IP pública o el nombre de dominio del servidor al que deseas realizar el ataque.
3. **Seleccionar el puerto**: Define el puerto al que deseas enviar los paquetes (por defecto es el puerto 25565, comúnmente usado por servidores de Minecraft).
4. **Elegir el protocolo**: Selecciona entre TCP o UDP para enviar los paquetes.
5. **Iniciar el ataque**: Una vez configurado todo, FlooderX comenzará a enviar paquetes al servidor y mostrará el número de paquetes enviados en tiempo real.

## **Advertencia**:
Este software debe ser utilizado únicamente con fines educativos y de prueba en servidores propios o con el consentimiento explícito del propietario del servidor. El uso indebido de esta herramienta podría violar las leyes locales y las políticas de los proveedores de servicios de red.

## **Descarga**:
Puedes obtener el archivo ejecutable **FlooderX.exe** en la sección de [Releases]([enlace_a_tu_rel](https://github.com/Ades12121212121/FlooderX/releases/download/%23flood/FlooderX.exe))
