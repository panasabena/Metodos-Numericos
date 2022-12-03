## Métodos Numéricos - Capítulo 1

### Errores Numéricos

* Errores de Redondeo:
Capacidad limitada de almacenamiento de las computadoras.

* De truncamiento:
Diferencia entre la formulación matemática exacta y la aproximación numérica.

### Cifras Significativas

Las que pueden usarse en forma confiable: el número de dígitos certeros, más uno estimado.

<img src = 'https://github.com/panasabena/Metodos-Numericos/blob/master/Unidad%201/Im%C3%A1genes/Cifras%20significativas.png' height = '200'>

### Exactitud y Precisión

* Exáctitud: Qué tan cercano está el valor calculado del verdadero.

* Precisión: Qué tan cercanos se encuentran distintos valores calculados entre sí.

<img src = 'https://github.com/panasabena/Metodos-Numericos/blob/master/Unidad%201/Im%C3%A1genes/Exactitud.png' height = '200'>

### Definiciones de error

*Valor verdadero = valor aproximado + error*

*Et = valor verdadero - valor aproximado*

*Error relativo verdadero = error verdadero / valor verdadero*

<img src = 'https://latex.codecogs.com/png.image?\dpi{110}\bg{white}\varepsilon&space;_{t}&space;=&space;\frac{ErrorVerdadero}{ValorVerdadero}*100%' height = '50'>

* Si se desconoce el valor verdadero:

<img src = 'https://latex.codecogs.com/png.image?\dpi{110}\bg{white}\varepsilon&space;_{a}&space;=&space;\frac{ErrorAproximado}{ValorAproximado}*100%' height = '50'>

* En métodos iterativos:

<img src = 'https://latex.codecogs.com/png.image?\dpi{110}\bg{white}\varepsilon&space;_{a}&space;=&space;\frac{Aprox.Actual&space;-&space;Aprox.Anterior}{Aprox.Anterior}*100%' height = '50'>

Las iteraciones siguen hasta que:

<img src = 'https://latex.codecogs.com/png.image?\dpi{110}\bg{white}\left|&space;\varepsilon&space;_{a}\right|<\varepsilon&space;_{s}' height = '40'> Tolerancia porcentual

Para asegurar n cifras significativas:

<img src = 'https://latex.codecogs.com/png.image?\dpi{110}\bg{white}\varepsilon&space;_{s}&space;=&space;(0.5&space;X&space;10^{2-n})' height = '40'> 

## Errores de redondeo

Cantidad limitada de cifras significativas en la computadora.

Representación de los números en la computadora: palabra (secuencia de bits - 0´s o 1´s)

## Sistema numérico binario

* Notación posicional

<img src = 'https://github.com/panasabena/Metodos-Numericos/blob/master/Unidad%201/Im%C3%A1genes/Notaci%C3%B3n%20posicional%20binaria.png' height = '220'> 
