# NEXUS-X — Desarrollo extensivo

Repositorio de desarrollo para consolidar y completar el NEXUS-X original, preservando las versiones existentes.

## Fuente de referencia
- Producción existente: https://github.com/miqueas80/Laboratorio2.0
- Este repositorio es un espacio de integración; **no modificar producción** hasta pasar validaciones.

## Principios
- Local-first y offline-first: PWA, Service Worker, IndexedDB y recursos ejecutables localmente.
- IA y Lens locales operativos sin depender de proveedores externos; servicios remotos solo opcionales.
- No inventar identificaciones químicas: resultados de Lens con evidencia, confianza y posibilidad de abstención.
- No incluir datos escolares privados, secretos, credenciales ni documentos sin autorización.
- Mantener compatibilidad de inventario, QR y datos exportables antes de migraciones.

## Plan de ejecución
1. Inventariar el árbol completo de Laboratorio2.0 y establecer una línea base reproducible con pruebas de humo.
2. Importar código y recursos permitidos conservando estructura, atribución e historial de cambios documentado.
3. Auditar offline/PWA, persistencia, seguridad y accesibilidad; agregar pruebas de regresión.
4. Reparar voz offline (STT, activación «Nexus», TTS, acciones) y medir tasas de éxito reales.
5. Mejorar Lens: QR, OCR, GHS, objetos y fusión de evidencias, con abstención ante incertidumbre.
6. Consolidar calendario, ESP32, roles institucionales y Malla Federal Educativa con módulos aislados.
7. Probar modo avión, instalación, datos, compatibilidad móvil y escritorio; publicar solo tras aprobación.

## Criterios de aceptación
- Arranque, inventario y documentos disponibles sin conexión tras instalación.
- Ninguna pérdida de datos al actualizar ni cambios destructivos sin respaldo.
- Voz y Lens sometidos a pruebas offline verificables; fallos documentados.
- Suite automatizada y checklist manual reproducibles.
- El sitio de producción original permanece intacto.

> Estado inicial: planificación y preparación del repositorio. **No se afirma que NEXUS-X esté migrado ni terminado.**
