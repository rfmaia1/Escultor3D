# Escultor3D - Parte 3

A interface gráfica do programa

<img src="img/tela-inicial.png">

O menu é composto por 11 botões que possui as seguintes funcionalidades

* `GridDim` Dimensiona o Grid de desenho.

<img src="img/dim-grid.png">

Após definimos as dimensões, obtemos:
<img src="img/tela-inicial-grid.png">

* `SaveOFF` Salva o desenho num arquivo `.OFF`. que poderá ser lido pelo programa `MeshLab`.

<img src="img/SaveOFF.png">

* `PutVoxel` Desenha um Voxel no Grid.

<img src="img/putvoxel.png">

* `CutVoxel` Apaga um Voxel no Grid.
* `PutBox` Desenha uma Caixa no Grid. Mova a barra deslizante `Box` para definir o valor de `z` (profundidade) da Caixa, é importante lembrar que na posição 0 a profundidade será nula e nada será desenhado.

*Para desenhar a `Box` basta presionar o mouse num quadrado e arrastar até outro quadrado.*
<img src="img/box-desenho.png">

* `CutBox` Apaga uma Caixa no Grid. Mova a barra deslizante `Box` para definir o valor de `z` (profundidade) da Caixa, é importante lembrar que na posição 0 a profundidade será nula e nada será apagado.
* `PutSphere` Desenha uma Esfera no Grid. Mova a barra deslizante `Sphere` para definir o valor de `r` (raio) da esfera.

<img src="img/putsphere.png">

* `CutSphere` Apaga uma Esfera no Grid. Mova a barra deslizante `Sphere` para definir o valor de `r` (raio) da esfera.
* `PutEllipsoid` Desenha um Elipsoide no Grid. Mova a barra deslizante `Ellipsoid` para definir os valores dos semieixos `x`, `y` e `z` do Elipsoide.

<img src="img/putellipsoid.png">

* `CutEllipsoid` Apaga um Elipsoide no Grid. Mova a barra deslizante `Ellipsoid` para definir os valores dos semieixos `x`, `y` e `z` do Elipsoide.
* `Exit` Fecha o programa.


A seguinte imagem foi construída utilizando o programa.

<img src="img/piramide00.png">
