# Tarea 02

## Instrucciones


Del libro Python para todos (👉 [enlace al pdf](https://drive.google.com/file/d/1KWsRn8hgdlz2z0S-u6BXybLMCFvSoyVK/view?usp=sharing)), leer el siguiente capítulo:

- Control de flujo.

Muy importante que vean la siguiente sección, les va a ayudar a hacer la tarea:

> ## if ... elif ... elif ... else
>Todavía queda una construcción más que ver, que es la que hace uso
del `elif`.
>```python
>if numero < 0:
>  print(“Negativo”)
>elif numero > 0:
>  print(“Positivo”)
>else:
>  print(“Cero”)
>```
>
>`elif` es una contracción de `else if`, por lo tanto `elif numero > 0` puede
> leerse como “si no, si numero es mayor que 0”. Es decir, primero se evalúa la condición del `if`. Si es cierta, se ejecuta su código y se continúa ejecutando el código posterior al condicional; si no se cumple, se evalúa la condición del `elif`. Si se cumple la condición del `elif` se ejecuta su código y se continua ejecutando el código posterior al condicional; si no se cumple y hay más de un elif se continúa con el siguiente en orden de aparición. Si no se cumple la condición del `if` ni de ninguno de los `elif`, se ejecuta el código del `else`.

---

El programa que van a realizar debe tener una función que se llame `calcularDispositivoBebe` y que reciba por parámetro:

- edad
- peso
- altura

Por ejemplo:

```python
def calcularDispositivoBebe(edad, peso, altura):
  if(0 <= edad <= 1 and 0 <= peso <= 13 and 0 <= altura <= 75):
    print("Portabebé")
  elif(1 <= edad <= 4 and 9 <= peso <= 18 and 75 <= altura <= 110):
    print("Silla")
```

Su trabajo es terminar la función que iniciamos en el archivo `main.py`.


<div style="overflow-x:auto;">
<table>
<thead>
  <tr>
    <th></th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><img src="https://scontent.fsyq2-1.fna.fbcdn.net/v/t1.6435-9/141984231_4289755744371973_7902865262036247026_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=973b4a&_nc_ohc=-11fZGwDKZYAX9xNOZm&_nc_ht=scontent.fsyq2-1.fna&oh=00_AfAW70MPdvLRlbqZ5n6B4CeOgjVd-rOVwvwJykVQBEqTyg&oe=64029D42" width="400" /></td>
    <td><img src="https://scontent.fsyq2-1.fna.fbcdn.net/v/t1.6435-9/142333625_4289755747705306_9067914534641048891_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=973b4a&_nc_ohc=EhoqzaVDAQoAX9Oy5Fd&_nc_ht=scontent.fsyq2-1.fna&oh=00_AfBjOTnzuk62eKDDyShAF1uy-6FALOWHQVlDA9qCS2R1nQ&oe=6402B91B" width="400" /></td>
  </tr>
  <tr>
    <td><img src="https://scontent.fsyq2-1.fna.fbcdn.net/v/t1.6435-9/142425034_4289755911038623_231997663123640108_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=973b4a&_nc_ohc=rNJ_WwvbYYgAX9TnVwW&_nc_ht=scontent.fsyq2-1.fna&oh=00_AfAg84qQmXepfclhDBAuF5cGJFP-kZvLwDii09_A4kSfhg&oe=6402AA74" width="400" /></td>
    <td><img src="https://scontent.fsyq2-1.fna.fbcdn.net/v/t1.6435-9/141678723_4289758024371745_2976777851100343415_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=973b4a&_nc_ohc=LC-vsgYSDT0AX-YkjVQ&_nc_ht=scontent.fsyq2-1.fna&oh=00_AfA2UWun-BKKc2_suYAPAJXb_Z3H3GfiMgbFg8G4Hmqnlw&oe=6402C073" width="400" /></td>
  </tr>
</tbody>
</table>
</div>

|                                                                                                                   	|                                                                                                                    	|
|-------------------------------------------------------------------------------------------------------------------	|--------------------------------------------------------------------------------------------------------------------	|
| edad: de 0 a 1 año <br> peso: hasta 13 kg <br> altura: hasta 75 cm <br> imprimir: Portabebé                       	| edad: de 1 a 4 años  <br> peso: de 9 a 18 kg  <br> altura: de 75 a 110 cm  <br> imprimir: Silla                    	|
| edad: de 4 a 6 años  <br> peso: de 15 a 25 kg  <br> altura: de 110 a 145 cm  <br> imprimir: Asiento con respaldar 	| edad: de 6 a 12 años  <br> peso: de 22 a 36 kg  <br> altura: de 110 a 145 cm  <br> imprimir: Asiento con respaldar 	|


# Preguntas frecuentes

Enlace a [preguntas frecuentes](https://www.notion.so/kevslife/Preguntas-frecuentes-a5dfd7afd0dd4202b3aa3ea83eb33778) 👈
