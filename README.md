# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educacion online

## Descripcion del Idioma

- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra tiene diez o mas letras, se debe debe partir a la mitad y unir con un guion en medio
- Si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayusculas y minusculas

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from platzom

platzom("Programar") //Program
platzom('Zorro') //Zorrope
platzom('Zarpar') //Zarpe
platzom('abecedario') //abece-dario
platzom('Sometemos') //SoMeTeMoS
```

## Creditos
- [Brayan Bernal](https://github.com/brayanibp)

## Licencia

[MIT](https://opensource.org/licenses/MIT)