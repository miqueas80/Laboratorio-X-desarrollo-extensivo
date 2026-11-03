# Estado de herencia de NEXUS-X (2026-11-03)

Se importaron directamente desde `miqueas80/Laboratorio2.0` los archivos fuente principales, el inventario, el catálogo, la PWA, módulos offline, librerías de lectura y numerosas pruebas. El repositorio original no se modificó.

## Pendiente — bloquea despliegue completo
Los siguientes recursos grandes/binarios NO están confirmados en el repositorio de destino:
- `offline/v1/voice/vosk-es.tar.gz`
- `offline/v1/voice/vosk.js` (archivo de texto grande)
- `offline/v1/vision/mobileclip-s0.onnx`
- `offline/v1/vision/ocr/PP-OCRv6_tiny_det.onnx`
- `offline/v1/vision/ocr/PP-OCRv6_tiny_rec.onnx`
- `offline/v1/vision/ort-wasm-simd-threaded.jsep.wasm`
- `pdf.worker.mjs` (la primera carga generó un archivo vacío: **reemplazar**)
- Iconos raster, imágenes de prueba, mascota WebP y otros adjuntos binarios por cotejar.

La conexión de GitHub usada para la importación no devuelve el contenido de algunos archivos grandes ni admite escritura binaria directa. Deben cargarse con Git/Git LFS o un mecanismo que preserve bytes exactos y verificarse con hashes. No importar documentos escolares privados.

## Validación
La migración **no está terminada** ni lista para publicar. Se requiere cotejar rutas y SHA-256 contra el ZIP original, ejecutar las pruebas y verificar voz, Lens y PWA sin conexión.
