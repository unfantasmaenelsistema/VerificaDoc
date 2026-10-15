# VerificaDoc

**Marca de agua para tu DNI y otros documentos de identidad**, de [Un Fantasma en el Sistema](https://www.unfantasmaenelsistema.com).

▶ **Abrir:** https://unfantasmaenelsistema.github.io/VerificaDoc/

Cuando una empresa te pide una foto del DNI (un alquiler, un banco, una oferta de trabajo…), enviarlo «en limpio» es arriesgado: esa copia puede acabar usándose para abrir cuentas o contratar servicios a tu nombre. VerificaDoc te deja **estampar una marca de agua** que dice para qué trámite es y en qué fecha, de modo que esa copia no sirva para otra cosa.

## Cómo funciona

1. Sube la imagen del documento (JPG, PNG o WEBP).
2. Elige el trámite (banco, alquiler, empleo) o escribe un texto propio.
3. Ajusta opacidad y color, y añade fecha/hora, aviso legal y número de serie.
4. Genera la imagen y descárgala.

## Privacidad

**Todo ocurre en tu navegador.** La imagen no se sube a ningún servidor: se procesa en tu propio dispositivo y la descarga sale directamente de ahí. Puedes usarla sin conexión.

## Características

- Marca de agua en mosaico diagonal con el texto del trámite y la fecha.
- Aviso legal al pie y número de serie único para trazabilidad.
- **La vista previa es fiel a la imagen final:** la marca escala con el tamaño del documento, así que lo que ves es lo que descargas.
- Español e inglés y tema claro/oscuro (se recuerdan entre visitas).
- Descarga en PNG sin pérdida de calidad.

## Recomendaciones

- Cuanto más específico sea el texto (empresa, fecha del trámite), más difícil es reutilizar el documento.
- La marca de agua **disuade**, pero no sustituye a la prudencia: envía el documento solo a quien debas y por canales seguros.

## Estructura

```
index.html   la aplicación (HTML, CSS y JS en un solo archivo)
logo.png     logo de la casa
```

Para probar en local: `python -m http.server` y abrir `http://localhost:8000`.

## English

**VerificaDoc** adds a watermark to your ID documents before you share them online: pick the purpose (bank, rental, job) or type your own text, and stamp it with date, a legal warning and a unique serial number. Everything runs in your browser — no image ever leaves your device. The live preview matches the final image. Bilingual (ES/EN), light/dark themes.

## Licencia / License

[MIT](LICENSE) © Un Fantasma en el Sistema
