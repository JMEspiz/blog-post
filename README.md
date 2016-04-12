## blog-post

```
Title:
Date:
Category:
Tags:
Slug:
Author:
author_pic_url:
twitter:
author_bio:
author_location:
Summary:
image:
```

### Caracteristicas de la publicacion:

* `Date` debe ser en este formato: 2016-03-30 13:20
* `Category` una sola categoria.
* `Tags` Maximo de 3 separados por comas `,`
* `Slug` Debe estar relacionado con el titulo por ejemplo: `my-super-post`
* `Author` Tu nombre y Apellido o si lo prefieres, tu nick
* `author_pic_url` Url de tu avatar recomendamos gravatar :)
* `twitter` Tu usuario de twitter sin incluir el `@`
* `author_bio` Una pequeña bio de quien eres :D
* `author_location` Donde te encuentras. Por ejemplo: Valencia, Venezuela
* `Summary` Un pequeño resumen de lo que trata el post
* `image` La imagen relacionada a la publicacion debe ser de `300x300`
    * `ext` Puede ser jpg o png

El post debe poseer la extension `.md` !important.

### Imagenes

Se agrega una carpeta llamada `images` donde deben colocar las imagenes relacionadas a su publicacion.

#### Ejemplo

`primer-post.md`

```
Title: Mi primer post
Date: 2016-03-30 13:20
Category: Blog
Tags: Blog,
Slug: primer-post
Author: abr4xas
author_pic_url: https://secure.gravatar.com/avatar/b5a93f6390e4bdb85a484d15b549d467
twitter: abr4xas
author_bio: Solo se que no se nada xD
author_location: En un bosque de la China
Summary: Este es el primer post del blog
image: /images/imagen_300_300.ext

// De acá hacia abajo sería el contenido del post.

Lorem ipsum dolor sit amet, consectetur adipiscing elit.


```


### Recomendaciones:

Leer esta [guia](https://github.com/circa75/dropplets/wiki/Markdown-Syntax-Guide) de Markdown

### Normas para la publicacion

* No deben violar ningun derecho de `copyright`.
* No deben ser sobre racismo.
* Ni hablar de **POLITICA**.
* Pornografia.

Cualquier publicación que viole estas normativas será eliminado.

## Contribuir

1. Fork it
* Crea una rama nueva con tu post (`git checkout -b mi-post`)
* Crea un commit con tus cambios nuevos (`git commit -am 'Se agrega un nuevo post para el blog de ngVenezuela'`)
* Haces un push a tu rama (`git push origin mi-post`)
* Creas un nuevo pull request

## Ya envie mi post, ¿cuando será publicado?

El post pasa a estar publicado luego que sea aceptado el pull request. Este proceso es de aproximadamente 10 minutos pero tambien va a depender de la disponibilidad de los encargados del blog. :D

## Licencia

Todos los post estan disponible bajo *[CC 4.0 (by-nc-sa)](http://creativecommons.org/licenses/by-nc-sa/4.0)* .
