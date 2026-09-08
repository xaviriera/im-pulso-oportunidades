# im-pulso-oportunidades

Documentacion interna de la linea de **compra de deuda** de IM·PULSO
(creditos hipotecarios). Separado a proposito de `im-pulso-share`, que
sirve los **informes de mercado** que ven los clientes en
`informes.im-pulso.app`. No mezclar las dos cosas.

Publico: GitHub Pages desde `master`, ficheros en la raiz.

## Contenido

| Fichero | Que es |
|---|---|
| `index.html` | Indice de los documentos |
| `circuito.html` | Los nueve estados de una operacion, actores y reglas |
| `acta-2026-09-05.html` | Acta de la reunion del 5-sep, en dos partes |

Cada pagina es autocontenida: CSS en linea y los dos logos embebidos en
base64. No hay carpeta de assets ni dependencias externas salvo la
tipografia Manrope de Google Fonts.

## Dominio propio (pendiente)

Cuando `dossier.im-pulso.app` este disponible:

1. En Cloudflare, registro `CNAME` de `dossier` -> `xaviriera.github.io`
2. Crear en la raiz de este repo un fichero `CNAME` con una sola linea:
   `dossier.im-pulso.app`
3. Esperar a que GitHub emita el certificado (unos minutos) y activar
   *Enforce HTTPS* en Settings -> Pages

**No crear el fichero `CNAME` antes de que el DNS resuelva** o Pages deja
de servir el sitio. Y ojo: el dominio aplica a TODO el repo, igual que en
`im-pulso-share`.
