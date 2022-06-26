<!-- HEADINGS -->

# my title h1
## my title h2
### my title h3
#### my title h4
#### my title h5
##### my title h6
***
<!-- Para agregar un BREAK LINE se agrega con enter-->

<!--italic -->
*italic*
_italic_

<!-- strong -->
**strong**
__strong__

***Cursiva y Negrita***
___Cursiva y Negrita___

<!-- strikehrough -->
este es un ~~texto~~ tachado

<!-- UL -->
* Lista
    - Lista 2
        + Lista 3
            + Lista 4


<!-- OL -->
1. Lista 1
   - Lista 2
     - Lista 3
2. Lista 4

<!-- Separadores en formas de linea -->

***
---
___

<!-- Esto es una cita -->
> Esto es una cita
>
>>> Y esto es otra cita

<!-- Bloques de código -->
<!-- ALT + 96-->
`print("Hola Mundo")`

<!-- ALT + 126-->
~~~javascript
const mongoose = require('mongoose');

moongose.set('useFindAndModify', false);
moongose.connect('mongodb://localhost/node-notes-db', {
useCreateIndex: true,
useNewUrlParser: true
})
    .then(db => console.log('DB is connected'))
    .catch(err => console.error(err));

~~~

~~~python
print("hello world")
~~~

~~~html
<h1>Hello World</h1>
~~~

~~~C#
Console.WriteLine("Hello World")
~~~

<!-- Link -->
[Mi web](google.com "Texto de enlace")

<!-- Imagen-->

![Visual studio code logo](https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg "vscode logo")


<!-- Símbolo sin formatos-->
\* Texto conescape


<!-- Tablas con sintaxis HTML -->
<table>
    <tr>
        <th>Nombre</th>
        <th>Apellido</th>
        <th>Edad</th>
    </tr>
    <tr>
        <td>Herbert</td>
        <td>Gadea</td>
        <td>30</td>
    </tr>
</table>


<!-- Tablas con Alt + 124 -->
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| cool 3 is     | right-aligned | $1600 |
| cool 2 is     | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

<!-- GITHUB MARKDOWN -->
* [x] Task 1
* [] Task 2
* [] Task 3
* [x] Task 4