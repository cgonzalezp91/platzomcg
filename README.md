# Platzomcg

Platzomcg es un idioma inventado para el [curso de fundamentos de JavaScript](https://platzi.com/js)

## Descrpicion del idioma
- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unit con un guión del medio
- Si la palabra original es un palíndromo, ninguna regla anterior se cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas

## Instalacion

```
npm install platzomcg
```

## Uso

```
import pltazom from 'platzom'

  console.log(platzom('Programar')) // Program
  console.log(platzom('Zorro')) // Zorrope
  console.log(platzom('Zarpar')) // Zarparpe
  console.log(platzom('abecedario')) // abece-dario
  console.log(platzom('sometemos')) // SoMeTeMoS
```

## Creditos
- [Carlos Gonzalez](https://www.linkedin.com/in/carlos-gonzalez-pe%C3%B1a-32747a159/)

## Licencia

[MIT](https://opensource.org/licenses/MIT)