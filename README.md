# ENS Academia A1 — Simulador de supuestos prácticos

Aplicación web estática para preparar supuestos del **Esquema Nacional de Seguridad (RD 311/2022)**, orientada a la oposición de Ingeniero/a Informático/a A1.

## Abrir la aplicación
- Web: https://ivanfebles78.github.io/oposicion/ (tras activar GitHub Pages).
- Localmente: descargar `index.html` y abrirlo con un navegador moderno.

No requiere servidor, dependencias, claves API ni compilación.

## Funciones
- 20 supuestos iniciales detallados con contexto, información técnica y preguntas.
- 90 minutos por intento: comienza al escribir la primera respuesta.
- Nota local orientativa de 0 a 10 y desglose por apartados.
- Zona de formación, ayudas y creación de nuevos casos.
- Historial guardado en el navegador mediante `localStorage`.
- Copiar respuestas para solicitar corrección detallada a ChatGPT.

**Atención:** la evaluación local usa criterios textuales, no una IA integrada ni una evaluación oficial de tribunal.

## Publicación en GitHub Pages
1. Ve a **Settings → Pages → Build and deployment**.
2. Selecciona **GitHub Actions**.
3. El workflow `.github/workflows/deploy.yml` publica la rama `main` en GitHub Pages.
4. Abre https://ivanfebles78.github.io/oposicion/ una vez concluido el despliegue.

## Privacidad
Los intentos y respuestas permanecen en el almacenamiento local del navegador. No se sincronizan entre dispositivos y se perderán si se eliminan los datos del sitio. No introduzcas datos reales de ciudadanos.

## Estructura
```text
index.html
README.md
.nojekyll
.gitignore
.github/workflows/deploy.yml
```

Normativa de referencia: https://www.boe.es/buscar/act.php?id=BOE-A-2022-7191

Proyecto de formación no oficial. No se ha seleccionado una licencia de reutilización específica.
