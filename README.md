# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js)

## Descripción del idioma
- Si la palabra termina en "ar", se le quitan esoso dos caracteres
- Si la palabra inizia con z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unir con un guion del medio
-Si la palabara original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas

## Instalación

```
npm install platzom-fundamentosjavascript
```

## Uso

```
import platzom from 'platzom-fundamentos'
platzom("Programar") //Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zorppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```
## Créditos
- [Sacha Lifszyc](https://twitter.com/@slifszyc)
- [Jesus Rojas](http://jesusrojas.com.ve)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
