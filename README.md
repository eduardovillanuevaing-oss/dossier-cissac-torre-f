# Dossier de Calidad — CISSAC Torre F (Arequipa)

Repositorio del **Dossier de Calidad** de los sistemas de protección contra incendios.

| Dato | Detalle |
|------|---------|
| **N° de obra** | 1225-26 |
| **Propietario** | DESARROLADORA VISTA NEVADO SAC |
| **Proyecto** | CASAPARQ, AREQUIPA — TORRE F — ETAPA IV |
| **Dirección** | Urb. El Rosario II, Cerro Colorado, Arequipa |
| **Ejecutor** | SUN FIRE SAC |
| **Cliente** | CISSAC Inmobiliaria y Construcción |

## Cómo visualizar el dossier
1. Descarga el repositorio (botón **Code → Download ZIP**) y descomprímelo, o clónalo.
2. Abre el archivo **`index.html`** con doble clic (Chrome o Edge).
3. Navega por las secciones, visualiza cada documento y descárgalo.

## Estructura
- `index.html` — visor del dossier (índice navegable, búsqueda, ver/descargar).
- `00.` a `09.` — secciones del dossier (fichas técnicas, actas, protocolos, etc.).
- `_dossier_web/` — recursos del visor (índice, logos, fondos) y el regenerador del índice.

## Actualizar el índice tras agregar documentos
El índice del visor es una "foto" del contenido. Tras agregar o quitar archivos,
ejecuta `_dossier_web/Actualizar-Indice.ps1` (clic derecho → Ejecutar con PowerShell)
y vuelve a hacer commit. Ver `_dossier_web/LEEME.txt` para más detalle.

---
**Confidencial.** Documentación de calidad del proyecto. Mantener el repositorio en modo privado.
