.Tipos de hojas de estilos:
    1._Externas:
        Dan formato a todo el sitio web
        Agilizan la descarga
        Van en un archivo vinculado independiente
    2._Internas:
        Dan formato a una pagina web
        La descarga es más lenta
        Van dentro del head de la página web

.Si dentro de la página se escribirá también código js, este ha de ir después del código css

.Estilos inline: son reglas css dentro de las etiquetas HTML. estos nos permiten cambiar un único elemento HTML de la página web, no ahorran tiempo a la hora de crear las páginas web ni tampoco ancho de banda como las hojas de estilos internas y externas. es necesario usarlo unicamente para aplicar formato a un único elemento.

.Selectore:
    De etiqueta
    De clase: comienzan con un punto .
    De ID: comienzan con una almuadilla #
    De grupo: aplicar estilos a varios selectores. h1, h2, p, address{}
    Universal: aplciar estilos a todos los elementos

.Selectores descendientes

.Estados de vinculos:
    .link: en reposo
    .visited: cuando se ha visitado
    .hover: cuando se pasa el ratón por encima
    .active: cuanto se está haciendo click
    el orden debe ser siempre el especificado

jerarquia de selectores:
    de etiqueta: 1pto
    de clase: 10pto
    de id: 100pto
    inline: 1000pto


===============================================================
Reset css:
html, body, h1, h2, h3, h4, h5, h6, p, ol, ul, li, pre, code, address, form, fieldset{
    padding: 0;
    margin: 0;
    font-size: 100%;
    font-weight: normal;
}
ol{
    margin-left: 1.4em;
    list-style: decimal;
}
ul{
    margin-left: 1.4em;
    list-style: decimal;
}
img{
    border: 0;
}
/*Este es el reset css*/
==================================================================