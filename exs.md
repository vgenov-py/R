1. Obten el sumatorio de todos los enteros de una sucesión 1:n
2. La Ley de los Números Grandes
### x̄n --> E(X) when n --> ∞  
* Comprueba la LNG con n valores distribuidos normalmente
* media = 0, S = 1
* E(X) = 0.682
```r
v_1 <- c(1,"2", 3, "María")
getwd()
setwd()
```
* Considerando el vector v_1, imprimir por consola sólo los valores númericos
* Crear un vector con valores de 10 a 1000 con una distancia entre cada uno de 10 unidades.
FUNCION is.type
"seq(first, second, [step])"
rep(value_to_repeat, times) #replicate You can replicate vectors
* Imprime por pantalla todos los valores salvo "María"
* Considerando un vector de n valores imprimir sólo el último de los mismos.
* Cambiar el wd
```r
v_1 <- c(1,7, 9, 26)
v_2 <- c(6,7, 4, 1)
rm() 
```

* Sumar todos los elementos por posición de los vectores v_1 y v_2
* Crear una función que sume vectores de diferentes longitudes y así evitar el warning message

### Financial statement Exercise
```r
revenue <- c(14574.49, 7606.46, 8611.41, 9175.41, 8058.65, 8105.44, 11496.28, 9766.09, 10305.32, 14379.96, 10713.97, 15433.50)
expenses <- c(12051.82, 5695.07, 12319.20, 12089.72, 8658.57, 840.20, 3285.73, 5821.12, 6976.93, 16618.61, 10054.37, 3803.96)
```
* Beneficio de cada mes
* Beneficio después de impuestos (21%)
* Margen de beneficio de cada mes (beneficio neto dividido ganancia) (valor porcentual)
* Meses buenos > media del año
* Meses malos < media del año
* Mejor mes
* Peor mes
* Precisión: <strong>0.01</strong>
```r
round()
mean()
max()
min()
```
```r
rbind()
```
### MATRIX

* Crear una matriz que se vea como un tablero de ajedrez

