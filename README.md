# Animar `background-color`
A partir de una lista de colores anima la propiedad `background-color` de un elemento como se ve en la imagen

![alt](assets/images/animar-background.gif)

En este ejercicio aplicaremos:

- Listas
- Tratar valores con y sin comillas
- Animaciones

Lista de colores

```SCSS
$colours: '#ff0066', turquoise, blueviolet;
```

---

# Pasar una lista como parámetro a un `@mixin`
Dada una lista anidada, crea las figuras de la imagen pasándole a un `@mixin` una lista que determinará la forma final

![alt](assets/images/lista-parametro.png)

En este ejercicio aplicaremos:

- Variables
- `@mixin`
- Listas y listas anidadas

Lista anidada:

```SCSS
$squareList: 
    (1rem, 0.5rem, 2.25rem, 0),
    (0, 1.5rem, 1.25rem, 3rem);
```