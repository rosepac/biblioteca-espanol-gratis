## Acuerdo de licencia del contribuyente
Al contribuir, aceptas la [LICENCIA](https://github.com/EbookFoundation/free-programming-books/blob/master/LICENSE) del repositorio.

## Código de conducta del contribuidor
Al contribuir, acepta el [Código de Conducta](https://github.com/EbookFoundation/free-programming-books/blob/master/CODE_OF_CONDUCT.md) de este repositorio.

## Brevemente
1. "Un enlace, un libro: un enlace, un curso"; gratis, no siempre es *libre*. Por favor, contribuir únicamente con contenido libre. Asegúrate de que sea gratis.
2. No es necesario que conozcas 'git': si encuentras algo de interés que no está ya en este repositorio , inicia un 'issues'/problema con tu propuesta de enlaces.
    - Si conoce git, por favor bifurque el repositorio y envía solicitudes de extracción
3. Se dividie en 5 tipos de listas. Elige la correcta:

    - *Libros* : PDF, HTML, ePub, un libro de gitbook.io, un repositorio de Git, etc.
    - *Cursos* : Un curso es un material de aprendizaje que no es un libro y donde no hay una herramienta interactiva incorporada en el sitio.  [Esto es un curso](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/).
    - *Tutoriales Interactivos* : un sitio web interactivo que permite al usuario escribir códigos o comandos y evalúa el resultado (por "evaluar" no queremos decir "calificación"). Por ejemplo: [Probar Haskell](http://tryhaskell.org), [Probar Github](http://try.github.io).
    - *recursos de Javascript* : cualquier recurso que enseñe un marco de JavaScript o una biblioteca.
    - *Conjuntos de problemas y programación competitiva* : un sitio web o software que le permite evaluar sus habilidades de programación resolviendo problemas simples o complejos, con o sin revisión de código, con o sin la comparación de los resultados con otros usuarios.

4. Asegúrate de seguir las [guías](#guias) y respetar el [formato de Markdown](#formato) de los documentos.

5. :construict: Travis CI will run tests to make sure your lists are alphabetized and formatting rules are followed. Be sure to check that your changes pass the tests.

### Guías :construction::construction::construction::construction: 
- make sure a book is free. Double-check if needed. It helps the admins if you comment in the PR as to why you think the book is free.
- we don't accept files hosted on google drive, dropbox, mega, scribd, issuu and other similar file upload platforms
- insert your links in alphabetical order. If you see a misplaced link, please reorder it and submit a PR
- use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + no file hosting services (this includes (but is not limited to) Dropbox and Google Drive links)
- always prefer a `https` link over a `http` one -- as long as they are on the same domain and serve the same content
- on root domains, strip the trailing slash: `http://example.com` instead of `http://example.com/`
- always prefer the shortest link: `http://example.com/dir/` is better than `http://example.com/dir/index.html`
    + no URL shortener links
- usually prefer the "current" link over the "version" one: `http://example.com/dir/book/current/` is better than `http://example.com/dir/book/v1.0.0/index.html`
- if a link has an expired certificate/self-signed certificate/SSL issue of any other kind:
  1. *replace it* with its `http` counterpart if possible (because accepting exceptions can be complicated on mobile devices)
  2. *leave it* if no `http` version but link still accessible through `https` by adding an exception to the browser or ignoring the warning
  3. *remove it* otherwise
- if a link exists in multiple format, add a separate link with a note about each format
- if a resource exists at different places on the Internet
    + use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + if they link to different editions and you judge these editions are different enough to be worth keeping them, add a separate link with a note about each edition (see [Issue #2353](https://github.com/EbookFoundation/free-programming-books/issues/2353) to contribute to the discussion on formatting.)
- prefer atomic commits (one commit by addition/deletion/modification) over bigger commits. No need to squash your commits before submitting a PR. (We will never enforce this rule as it's just a matter of convenience for the maintainers)
- if the book is older, include the publication date with the title. 
- include the author name or names where appropriate. You can shorten author lists with "et al."
- if the book is not finished, and is still being worked on, add the "in process" notation, as described [below.](#in_process)

### Formato
- All lists are `.md` files. Try to learn [Markdown](https://guides.github.com/features/mastering-markdown/) syntax. It's simple!
- All the lists start with an Index. The idea is to list and link all sections and subsections there. Keep it in alphabetical order.
- Sections are using level 3 headings (`###`), and subsections are level 4 headings (`####`).

The idea is to have
- `2` empty lines between last link and new section
- `1` empty line between heading & first link of its section
- `0` empty line between two links
- `1` empty line at the end of each `.md` file

Example:

    [...]
    * [An Awesome Book](http://example.com/example.html)
                                    (blank line)
                                    (blank line)
    ### Example
                                    (blank line)
    * [Another Awesome Book](http://example.com/book.html)
    * [Some Other Book](http://example.com/other.html)

- Don't put spaces between `]` and `(`

```
BAD : * [Another Awesome Book] (http://example.com/book.html)
GOOD: * [Another Awesome Book](http://example.com/book.html)
```

- If you include the author, use ` - ` (a dash surrounded by single spaces)

```
BAD : * [Another Awesome Book](http://example.com/book.html)- John Doe
GOOD: * [Another Awesome Book](http://example.com/book.html) - John Doe
```

- Put a single space between the link and its format

```
BAD : * [A Very Awesome Book](https://example.org/book.pdf)(PDF)
GOOD: * [A Very Awesome Book](https://example.org/book.pdf) (PDF)
```

- Author comes before format:

```
BAD : * [A Very Awesome Book](https://example.org/book.pdf)- Jane Roe
GOOD: * [A Very Awesome Book](https://example.org/book.pdf) - Jane Roe (PDF)
```

- Multiple formats:

```
BAD : * [Another Awesome Book](http://example.com/)- John Doe (HTML)
BAD : * [Another Awesome Book](https://downloads.example.org/book.html)- John Doe (download site)
GOOD: * [Another Awesome Book](http://example.com/) - John Doe (HTML) [(PDF, EPUB)](https://downloads.example.org/book.html)
```

- Include publication year in title for older books:

```
BAD: * [A Very Awesome Book](https://example.org/book.html) - Jane Roe - 1970
GOOD: * [A Very Awesome Book (1970)](https://example.org/book.html) - Jane Roe
```

<a name="in_process"></a>
- In-process books 

```
GOOD: * [Will Be Awesome Soon Book](http://example.com/book2.html) - John Doe (HTML) (:construction: *in process*)
```
