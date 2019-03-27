# **GRIDS CSS PARA PROJETOS**

# GRID-18

_Esse é um grid básico que foi desenvolvido baseado em 18 colunas, 6 colunas e 2 colunas._

Eu sei...
> Um grid de 18 colunas!?

Mas para dispositivos com telas grande é excelente, trust me !

## Container

Para definir um container:

```
<div class="container">
  --Conteúdo--
</div>
```
> Eu sei... como os outros, porém esse container só servirá para telas grandes !

## Row

```
<div class="row">
  --Colunas--
</div>

```
> Da mesma maneira que os outros grids, sempre deve ter uma div com class "row" antes das colunas.

## Colunas

Para definir uma div como uma coluna basta adicionar col a class.

```
<div class="col">
  --Conteúdo--
</div>
```

## Colunas 18, 6 e 2.

Então como mencionado este grid é dividido em 18 colunas, 6 e 2.

> Estas colunas são respectivamente relacionadas para os tamanhos de telas grande(large), média(medium) e pequena(small).

Desta forma, para criar um layout em **_telas grandes_**, o grid disponhe de 18 colunas.

O Código ficaria assim:

```
<!-- PARA TELAS GRANDES -->
<!-- Div com espaço de uma(1) coluna -->
<div class="col l-1">
  --conteúdo--
</div>
<!-- assim por diante de 1 à 18 -->

```

Para dispostivos com tamanhos de **_telas médias_**, o grid disponhe de 6 colunas.

O **código** ficaria assim:

```
<!-- TELAS MÉDIAS -->
<!--Div com espaço de uma(1) coluna -->
<div class="col m-1">
  --conteúdo--
</div>
<!-- assim por diante de 1 à 6 -->
```

Para dispositivos com tamanhos de **_telas pequenas_**, o grid disponhe de 2 colunas.

O **código** ficaria assim:

```
<!-- TELAS PEQUENAS -->
<!--Div com espaço de uma(1) coluna -->
<div class="col s-1">
  --conteúdo--
</div>
<!-- assim por diante de 1 à 2 -->
```
> obs: No começo é meio confuso de se entender, porém depois fica fácil.

## Divs responsivos

Para desenvolver um site totalmente responsivel, é bastante fácil !

Só basta adicionar as colunas específicas para os determinados tamanhos de telas.

O **código** ficaria assim:

```
<!-- TELAS GRANDES, MÉDIAS E PEQUENAS -->
<!--Div com espaço de uma(1) coluna -->
<div class="col l-1 m-1 s-1">
  --conteúdo--
</div>
<!-- l-[1 à 18] | m-[1 à 6] | s-[1 à 2] -->
```
> obs: Preste muita atenção quando for projetar seus layouts para os determinados tamanhos de telas !

## Offsets

> _Esse tópico ainda não foi adicionado..._

> Os grids ainda estão em desenvolvimento, se você tiver alguma sujestão ou conheci outros tipos de grid css, por favor, mande uma mensagem para este endereço de email ne.hermerson@gmail.com :p





