# CreamSlider

[Demostración](http://zkreations.github.io/CreamSlider/)
Basado en [Sheet Slider](https://github.com/zkreations/SheetSlider)

## Version 

### Cream Slider 1.01

* Reset en el css para evitar la sobreescritura

## Instalación

[Descargar](https://github.com/zkreations/CreamSlider/archive/master.zip) e incluir arriba de `</head>` el codigo css.

```html
<link rel="stylesheet" href="cream-slider.min.css"/>
```

### Utilizar Cream Slider

La forma mas simple de usar el slider (sin textos) seria la siguiente:

```html
<div class="cream-slider">
   <input id="c1" type="radio" name="cream1"/>
   <input id="c2" type="radio" name="cream1"/>
   <input id="c3" type="radio" name="cream1"/>
   <ul>
      <li class="tab"><img src="img01.jpg"/><label for="c1"></label></li>
      <li class="tab"><img src="img02.jpg"/><label for="c2"></label></li>
      <li class="tab"><img src="img03.jpg"/><label for="c3"></label></li>
   </ul>
</div>
```

## Color y tema

Despues de incluir `cream-slider.min.css` agregar el siguiente codigo.

```html
<link rel="stylesheet" href="dist/color/cyan.css"/>
```

No hay temas por el momento

## Limitaciones

* Solo puede haber un slider por página, ya que se basa en la **id** del **input** y esta no puede repetirse.
* El slider solo puede contener hasta un máximo de 8 imágenes.
* En Internet Explorer 11, **transition** no funciona para flexbox.