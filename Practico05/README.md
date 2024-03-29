# Web1 - Practico 05

## Responsive Design

1. ¿En qué consiste el diseño web responsive? ¿Cuáles son sus ventajas?

https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design

2. ¿Qué es el diseño Mobile First? ¿Piensa que en alguna situación particular el diseño Mobile First no es la mejor opción?

https://en.wikipedia.org/wiki/Responsive_web_design

3. ¿En qué situaciones conviene usar media queries  mediante max-width o min-width?

https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries

4. Investigue para que funciona el siguiente metatag:

https://www.w3schools.com/css/css_rwd_viewport.asp

### Básico

5. Diseñe el body de un sitio web el cual cambia el color de fondo según distintos tamaños de pantalla. Investigue cuales son los breakpoints más utilizados (celular, celular landscape, tablet, etc).

6. Cree un sitio con varios heading. A medida que la resolución de pantalla se agrande, la fuente del sitio también debe agrandarse proporcionalmente. Utilice también medidas de fuente relativas con em y rem. ¿Qué diferencia observa entre utilizar medidas fijas y relativas en las fuentes del sitio?

### Intermedio

7. Modifique la barra de navegación del sitio de noticias utilizando flex para distribuir los elementos horizontalmente.

    Ya lo había hecho.

8. Realice los siguientes layouts mediante las técnicas flexbox y grid css. ¿Cuál de las técnicas le pareció más apropiada para realizar cada uno?

```
    header     header header 
    article    article aside
    aside      footer footer
    footer

    Mobile       Desktop
```
    Grid me parece alpha mal.

10. Modifique [este codepen](https://codepen.io/webUnicen/pen/QRLKbr) para que se vea de la siguiente manera:

Primera versión: no importan las dimensiones de las cajas, solo la grilla 5x5.
Segunda versión: cajas cuadradas

```
.container {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
}

.item {
  width: 250px;
  height: 250px;
  background: red;
  margin: 10px;
  color: white;
}
```

 12. Realice los siguientes layouts mediante las técnicas flexbox y grid css. 

```
      A B C        A A D D        A
      D D D        B C D D        B
                                  C
                                  D

      Desktop      Tablet       Mobile
``` 

13. Realice los siguientes layout responsive:

```
      B B        A B B
      C D        C D E
      E E

    Mobile       Desktop
``` 

14. Realice el siguiente layout responsive. Investigue la propiedad order.

```
      header header header        header
      nav content aside           content
      footer footer footer        nav
                                  aside
                                  footer

            Desktop               Mobile
``` 
