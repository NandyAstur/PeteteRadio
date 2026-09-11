# PGL Releases — canal oficial de distribución

Repositorio público oficial de **Petete & Geppetto Labs (PGL)** para aplicaciones que hayan sido aprobadas expresamente para distribución externa.

## Aplicaciones disponibles actualmente

### Petete Radio

Petete Radio es, por ahora, la **única aplicación PGL autorizada para distribución pública** desde este repositorio.

- **Windows:** instalador oficial y canal de actualización estable mediante `windows.json`.
- **Android:** APK oficial y canal de actualización estable mediante `android.json`.
- Las publicaciones incluyen comprobaciones SHA-256 para verificar la integridad de los archivos distribuidos.

## Reparar el actualizador de Petete Radio

Las compilaciones **c01, c02 y c03** pueden mostrar que el archivo **.partial** está siendo utilizado por otro proceso.

**[REPARAR ACTUALIZADOR — descargar el instalador oficial c05](https://github.com/NandyAstur/PeteteRadio/releases/download/v1.22.18-c05/Petete-Radio-Windows-Setup.exe)**

1. Cierra Petete Radio.
2. Ejecuta el instalador descargado.
3. No desinstales la aplicación: se conservarán emisoras, favoritas y ajustes.
4. Comprueba al abrir que aparece **v1.22.18 c05**.

El instalador pertenece a la Release oficial y Petete Radio verifica sus actualizaciones mediante SHA-256. Desde c05 existe además un módulo auxiliar que no depende de renombrar un archivo `.partial`.

## Política de distribución PGL

Este repositorio contiene únicamente binarios, instaladores, APK y metadatos de actualización correspondientes a aplicaciones que PGL haya decidido publicar.

Los repositorios de desarrollo y código fuente permanecen privados. **Petete TV, Petete Hub, Petete MD, Petete Core y el resto de proyectos PGL no se distribuyen públicamente desde aquí hasta que sean declarados terminados y seguros para uso externo.**

© 2026 Petete & Geppetto Labs (PGL). Todos los derechos reservados.
