# Flex-direction

Esta propiedad especifica cómo colocar los items en el contenedor, definiendo el eje principal y la dirección.

![Image from: https://css-tricks.com/](https://lh6.googleusercontent.com/tkP6R_hWOccV8F5k-sjR8O7TbSVLtPJfYYkGV6Gg-glriDrRt6c3nvXAu6HUrS174KwEoQkQ16LoBv69sPCRWRZSxLEKxiNp16qgCoPDLxUy6ZWHLlKNPDE1ykKi-K2yczA9GkLO)

Sus atributos son:

* **row**: se define el eje principal \(_main axis_\) horizontalmente y de izquierda a derecha.

```text
.flex-container {
    display: flex;
    flex-direction: row;
}
```

![Image from: https://soyfrontend.com/](https://lh3.googleusercontent.com/H0tvRtGG1GqLlcpNn9mrv8JIGtXn6rq_tG_qvAh9-_7Yik1ztvcgCLQ7F1sSZfbEDZI-bBRWDmbDqlPW1ChzcRy_sO-6ngnyS09sy5RtrZD9csAdDXRJCbmn0qkBJt1tls0Yw8KZ)

* **row-reverse**: trabaja igual que row pero a la inversa.

```text
.flex-container {
    display: flex;
    flex-direction: row-reverse;
}
```

![Image from: https://soyfrontend.com/](https://lh3.googleusercontent.com/Zh0KFS0Bqb883xcbxcfCAavuelx8ZV3m1R7LLJtNpZX_YqbmWzWPhkh6Qu640tS88EpqlEEuEsG55emS7wqb3mcmKn4p3ynay18PfAQyoG0hY87fwD2SzIDqyZBH7l5oYTHMc_r2)

* **column**: con este valor los items se apilan en una columna de arriba hacia abajo, intercambiando los ejes principal y secundario, es decir, el _main-axis_ pasaría a ser vertical y el _cross-axis_ horizontal.

```text
.flex-container {
    display: flex;
    flex-direction: column;
}
```

![Image from: https://soyfrontend.com/](https://lh5.googleusercontent.com/iR_4LEMAeLoEZ2TgFmk5L0IbLH1UOlw4VWHQOHsHjuRdSaOxb7H98ygUOdM7ZAXolGxWoSLgwlu9vEOmRavIYFqdsX3YHx9ezM1rvI2ZJVGQt_tcjV4xD9caElL5u2TwVdiVz4-3)

* **column-reverse**: este valor también trabaja igual que el anterior pero a la inversa.

```text
.flex-container {
    display: flex;
    flex-wrap: wrap-reverse;
}
```

![Image from: https://soyfrontend.com/](https://lh6.googleusercontent.com/_0xAS96e0MfMrsE7xDp8mK2OtMFOmUEYEcWLe9ud69epkY-CoxwXcSRoFbgYJ4AUiVVdNndaRQ0DGfP9s9B7VJib78NfhB37qiSQGFFwWvfO6u2kDoVIhjK51syZr3HxahDW_p8-)

