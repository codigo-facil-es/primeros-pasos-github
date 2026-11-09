# GitHub: tu proyecto en la nube

Este es **el repositorio que subimos en directo** en el tutorial de [Código Fácil](https://www.codigofacil.es/aprender): mira su historial, son los mismos commits del vídeo.

## Qué hay aquí

| Archivo | Qué es |
|---|---|
| [`index.html`](index.html) | La página de recetas de los tutoriales de Git |
| [`.gitignore`](.gitignore) | Le dice a Git que **no suba** el archivo `.env` con las claves |

Fíjate en que el archivo `.env` del vídeo **no está aquí**: `.gitignore` lo protegió.

## Los comandos del vídeo

```bash
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git   # conectar con GitHub
git push -u origin main                                                  # subir (la primera vez)
git push                                                                 # subir (las siguientes)
git clone https://github.com/codigo-facil-es/primeros-pasos-github.git   # descargar en otro ordenador
```

## La regla de oro

**Nunca subas tus claves** (archivos `.env`, contraseñas, tokens). Añádelos a `.gitignore` **antes** del primer commit. Si alguna vez subes una clave por error, cámbiala: borrarla del repositorio no basta, porque sigue en el historial.

Siguiente tutorial: **Qué es un agente de código y cómo trabajar con él** → [repositorio](https://github.com/codigo-facil-es/que-es-un-agente-de-codigo).

## Licencia

[MIT](LICENSE)
