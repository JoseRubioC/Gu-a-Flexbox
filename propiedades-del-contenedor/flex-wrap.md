# Flex-wrap

El comportamiento inicial del _flex container_ es poder mantener los items en su _main-axis_ sin importar que los dimensiones de estos items cambien,  pero hay ocasiones donde vamos a querer controlar este alineamiento y hacer que los elementos puedan saltar de línea para poder mantener el posicionamiento deseado en los items. Con _flex-wrap_ vamos a poder especificar las líneas del _flex container_, si queremos un contenedor de una línea o un contenedor multi-línea.  


![](https://lh6.googleusercontent.com/QNVvFsw1EK0GBc9YBP1ye2O8dmt4GurrNbsF19POkjx9uXz03EHk-khCJag7lkS3ojWa317PE7B2OBzcBflC57bpCYLR9IUU7vVZhv9jtHuwI6zEujLWcKfmVdg5PbyavHztMCb3)

Sus valores son:

* **nowrap \(por defecto\)**: Con este valor los items son colocados en una sola línea sin importar cuántos sean.

```text
.flex-container {
    display: flex;
    flex-wrap: nowrap;
}
```

![Image from: https://soyfrontend.com/](https://lh6.googleusercontent.com/v9-TcpEhG7wMNN-CAunOerbpg1bxjvQwnfsz4UXWwswOovxM8kjOGmba_Ksyx002-6C7jx8A6YrIn_XBrn3sZ4BHUVFc0z7rkaGeBot2TZ0g_AgNeTF256-_5tex6oCadVotrjWP)

* **wrap**: Con este valor los items son colocados en varias líneas si la suma del ancho de los items es superior al ancho del contenedor. Esto vuelve al contenedor un elemento multi-línea.

```text
.flex-container {
    display: flex;
    flex-wrap: wrap;
}
```

![Image from: https://soyfrontend.com/](https://lh4.googleusercontent.com/32PCXolOW3xQYxQmi3GkT9PgQ1Clmu4wBEwGdNaxSm0dkuMYixXktd7nWBsssfboBHH5ohOPYZBtAhOiraLasp1emjavvpnsLBrSHajaaWebnuYVuGiYCCISnTFcs_fU4AwKErr8)

* **wrap-reverse**: con este valor los ítem actuarán igual que con wrap pero a la inversa.

```text
.flex-container {
    display: flex;
    flex-wrap: wrap-reverse;
}
```

![Image from: https://soyfrontend.com/](https://lh5.googleusercontent.com/tiBUjMd90ovxZTTEncCpT9VReIW9CLeQ_MEq2zMDZAsZuGdViCd6u9fF1LVB67NNgTWaE6heeiiTYlFuUonUHqdr175OGkFRv0WJmf-pZbhoNAf1gVANnvWIZuSoVsr36XeqsTV7)

