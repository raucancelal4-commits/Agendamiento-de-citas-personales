# Uso de Markdown en proyectos de software

## ¿Qué es Markdown y por qué se utiliza?

Markdown es un lenguaje de marcas ligero con sintaxis de texto plano que puede convertirse fácilmente a HTML u otros formatos mediante herramientas compatibles. Fue creado por **John Gruber en 2004** con el objetivo de permitir a los usuarios escribir de forma simple, legible y convertir el texto en documentos XHTML o HTML válidos sin necesidad de una sintaxis compleja.

Una de sus ventajas más destacadas es que un documento escrito en Markdown **puede leerse incluso sin procesar**, ya que sus marcas son intuitivas y fáciles de escribir. Plataformas como **GitHub, Reddit, Stack Exchange, Diaspora, OpenStreetMap o SourceForge** utilizan variantes de Markdown para facilitar la comunicación entre usuarios.

Actualmente existen múltiples implementaciones del lenguaje en diversos lenguajes de programación, aunque no existe un estándar único definitivo, más allá de la implementación original de Gruber. La IETF trabaja en la creación de un estándar formal.

### ¿Por qué se utiliza en proyectos de software?

Markdown se usa ampliamente debido a:

- **Facilidad de uso:** Se aprende rápidamente y permite centrarse en el contenido sin preocuparse por formatos complejos.  
- **Documentación clara:** Es el estándar para archivos `README.md`, wikis y documentación técnica.  
- **Colaboración:** Su formato en texto plano lo hace perfecto para sistemas de control de versiones como **Git**.  
- **Compatibilidad:** Funciona en múltiples herramientas como GitHub, GitLab, VS Code, Slack, Discord, etc.  
- **Eficiencia:** Facilita la escritura rápida sin necesidad de editores pesados como Word.

## Ejemplo práctico de uso de Markdown

### Encabezados

# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3

### Formatos de texto

- **Negrita:** `**negrita**`
- *Cursiva:* `*cursiva*`
- ~~Tachado:~~ `~~tachado~~`
- Citas:
  > Esto es una cita.
  > - Autor
- Líneas horizontales: `---` / `***` / `___`
- Énfasis: `*texto enfatizado*` o `_texto enfatizado_`

### Listas

#### No ordenadas

- Elemento
- Elemento
- Elemento

#### Ordenadas

1. Elemento 1
2. Elemento 2
3. Elemento 3


#### Anidadas

- Elemento 1
    - Elemento 1.1
    - Elemento 1.2
- Elemento 2
    - Elemento 2.1
    - Elemento 2.2

### Comentarios

<!-- comentario -->

### Enlaces

[Visitar GitHub](https://github.com)

### Imágenes
![Logo de Markdown](https://store-images.s-microsoft.com/image/apps.50768.14132366815472789.d93aceff-2beb-4a3c-9a29-f28c2ff8b309.00edb73c-9c63-4902-b120-e9b1fa714f4e)


### Tablas

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| ------------ | ------------ | ------------ |
| Dato 1       | Dato 2       | Dato 3       |
| Dato 4       | Dato 5       | Dato 6       |

**Alineación:**

| Izquierda      | Centro        | Derecha       |
| :------------- | :-----------: | ------------: |
| Dato 1         | Dato 2        | Dato 3        |
| Dato 4         | Dato 5        | Dato 6        |

### Código

Código en línea:  

`var nombre = "John";`


### Párrafos y saltos de línea

Para un salto de línea sin crear párrafo:  

Texto con salto de línea  
Texto debajo

## Ventajas de usar Markdown con GitHub

- Notas claras y estructuradas.
- Sincronización en la nube.
- Pull requests para colaboración.
- Publicación con GitHub Pages.
- Control de versiones e historial.

## Bibliografía

- Platas, A. B., & García, R. P. Ñ. (2017). TEIdown: Uso de MarkDown extendido para el marcado automático de documentos TEI. Revista de humanidades digitales, 1, 57-75. (https://revistas.uned.es/index.php/RHD/article/view/16683/16586).
- Cómo utilizar MarkDown para escribir documentación técnica: https://experienceleague.adobe.com/es/docs/contributor/contributor-guide/writing-essentials/markdown
- Pressman, R. S. (2010). Ingeniería del Software: Un enfoque práctico (7ª ed.). McGraw-Hill.
- Sommerville, I. (2011). Ingeniería del Software (9ª ed.). Pearson.
