## Acuerdo de licencia del contribuyente

Al contribuir, aceptas la [LICENCIA](https://github.com/DpdC/biblioteca-espanol-gratis/blob/master/LICENCIA.txt) del repositorio.


## Brevemente

1. Asegúrate de seguir las [guías](#guias) y respetar el [formato de Markdown](#formato) de los documentos.
2. Asegúrese de verificar que sus cambios pasen las pruebas, a través de Travis CI que comprobara que sus listas estén alfabetizadas y siguen las reglas de formato.
3. No es necesario que conozcas 'git': si encuentras algo de interés que no está ya en este repositorio , inicia un 'issues'/problema con tu propuesta de enlaces.
    * Si conoce git, por favor bifurque el repositorio y envía solicitudes de extracción
4. Se divide en 5 tipos de listas. Elige la correcta:
    * *Conjuntos de problemas y programación competitiva* : un sitio web o software que le permite evaluar sus habilidades de programación resolviendo problemas simples o complejos, con o sin revisión de código, con o sin la comparación de los resultados con otros usuarios.
    * *Cursos* : Un curso es un material de aprendizaje que no es un libro y donde no hay una herramienta interactiva incorporada en el sitio.  [Esto es un curso](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/).
    * *Libros* : PDF, HTML, ePub, un libro de gitbook.io, un repositorio de Git, etc.
    * *Recursos de Javascript* : cualquier recurso que enseñe un marco de JavaScript o una biblioteca.
    * *Tutoriales Interactivos* : un sitio web interactivo que permite al usuario escribir códigos o comandos y evalúa el resultado (por "evaluar" no queremos decir "calificación"). Por ejemplo: [Probar Haskell](http://tryhaskell.org), [Probar Github](http://try.github.io).
5. "Un enlace, un libro: un enlace, un curso"; gratis, no siempre es *libre*. Por favor, contribuir únicamente con contenido libre. Asegúrate de que sea realmente gratis.


## Código de conducta del contribuidor

Al contribuir, acepta el [Código de Conducta](https://github.com/EbookFoundation/free-programming-books/blob/master/CODE_OF_CONDUCT.md) de este repositorio.


### Formato

* Las secciones usan encabezados de nivel 3 (`###`), y las subsecciones de nivel 4 (`####`).
* Todas las listas comienzan con un índice. La idea es enumerar y vincular todas las secciones y subsecciones en el. Mantenlo en orden alfabético.
* Todas las listas son archivos `.md`. Se recomienda, aprender la sintaxis de [Markdown] (https://guides.github.com/features/mastering-markdown/). ¡Es sencillo!

La idea es tener`2` líneas vacías entre el último enlace y la nueva sección,  `1` línea vacía entre el encabezado y el primer enlace de su sección, `0` líneas vacías entre dos enlace y`1` línea vacía al final de cada archivo `.md`.

Aquí se pueden visualizar, ejemplos: [Espaciados Adecuados](https://github.com/EbookFoundation/free-programming-books/blob/master/CONTRIBUTING.md#formatting)


### Guías

* Asegúrese de que un libro sea gratis. Verifique dos veces si es necesario. Ayuda a los administradores comentando en el 'Pull Requests' por qué crees que el libro es gratuito.
* En dominios raíz, deshazte del 'slash' o barra final.
* Incluir el nombre o los nombres del autor cuando corresponda. Puedes acortar las listas de autor con "et al." (que significa: y otros).
* Inserte tus enlaces en orden alfabético. Si encuentras un enlace extravíado, por favor, corrigelo y envía una 'Pull Requests'.
* No incluyas archivos alojados en google drive, dropbox, mega, scribd, issuu u otras plataformas de carga de archivos similares
* Preferiblemente 'commits' (un 'commit' por adición/ eliminación/ modificación) antes de grandes 'commits'. No es necesario aplastar tus compromisos antes de enviar un PR (Nunca aplicaremos esta regla ya que es solo una cuestión de conveniencia para los mantenedores)
* Preferiblemente utiliza el enlace "actual" al de una versión: [http://example.com/dir/book/current/](http://example.com/dir/book/current/) es mejor que [http://example.com/dir/book/v1.0.0/index.html](http://example.com/dir/book/v1.0.0/index.html)
* Siempre es preferible el enlace más corto: `http://example.com/dir/` es mejor que `http://example.com/dir/index.html`
    * Sin enlaces de acortadores de URL.
* Siempre es preferible enlaces `https` sobre uno `http` siempre y cuando estén en el mismo dominio y sirvan el mismo contenido.
* Si un enlace tiene un certificado caducado / certificado autofirmado / o problema SSL de cualquier tipo:
  1. *Reemplazarlo* con su `http` si es posible (porque aceptar excepciones puede ser complicado en dispositivos móviles).
  2. *Déjalo* si la versión `http` no esta accesible, pero la`https` sí; a través de una excepció nde seguridad del navegador.
  3.  De otra manera*eliminalo*.
* Si existe un enlace de forma múltiple, agrega un enlace por separado con una nota sobre cada formato.
* Si existe un recurso en diferentes lugares de Internet
    * usa el enlace con la fuente más autorizada
    * si se vinculan a diferentes ediciones y usted juzga que estas ediciones son lo suficientemente diferentes como para que valga la pena mantenerlas, agregue un enlace por separado con una nota sobre cada edición (ver [Issue #2353](https://github.com/EbookFoundation/free-programming-books/issues/2353) para contribuir a la discusión sobre el formato.)
* Si el libro es más antiguo, incluya la fecha de publicación con el título. 
* Si el libro no esta terminado, 
if the book is not finished, y todavía se está trabajando en él, agrega la notificación"en proceso" como se describe [aquí.](https://github.com/EbookFoundation/free-programming-books/blob/master/CONTRIBUTING.md#in_process)
* Usa el enlace con la fuente más autorizada. Lo que signfica que el sitio web del autor es mejor que el sitio web del editor, y esté; mejor que el sitio web de un tercero.
    * no uses servicios de alojamiento (esto incluye (pero no está limitado a) Dropbox y enlaces de Google Drive)

