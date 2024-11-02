# Desenhando um Coração com Python ❤️

O amor pelo Python é grande! Este projeto usa a biblioteca Turtle para desenhar um coração e relaxar um pouco enquanto exploramos a programação.

## O que é Python?
Python é uma linguagem de programação popular, conhecida por ser simples e poderosa. Ela permite criar desde pequenas automações até sistemas complexos, como sites e análises de dados. Python é fácil de aprender e conta com uma grande comunidade que oferece suporte e uma vasta gama de bibliotecas que facilitam o desenvolvimento.

## O que é a Biblioteca Turtle do Python?
A **biblioteca Turtle** é uma ferramenta visual e divertida, ideal para iniciantes. Inspirada na linguagem Logo, a Turtle permite que você controle uma "tartaruga" gráfica que se move pela tela, desenhando formas, linhas e até animações. Com comandos como `forward`, `left`, `right`, e `penup`, você pode criar de figuras geométricas simples até obras de arte mais complexas.

---

## Passo a Passo para Desenhar o Coração

### Etapa 1: Importar a biblioteca Turtle
A biblioteca Turtle já vem embutida no Python, então basta importá-la:

```python
from turtle import *
```
### Etapa 2: Configurar a cor e o preenchimento
O comando `color('red')` define a cor do contorno e do preenchimento. Em seguida, `begin_fill()` indica que o próximo desenho será preenchido com essa cor.

```python
color('red')  
begin_fill()
```
### Etapa  3: Definir a espessura do contorno
Com `pensize(3)`, definimos a espessura da linha para 3 pixels.

```python
pensize(3)
```
### Etapa 4: Desenhar a primeira diagonal do coração
A "tartaruga" gira 50 graus à esquerda e avança 133 unidades, criando a primeira linha diagonal do coração.

```python
left(50)
forward(133)
```

### Etapa 5: Criar o primeiro arco do coração
`circle(50, 200)`desenha um arco com raio de 50 unidades e ângulo de 200 graus, formando a curva superior de um lado do coração.

```python
circle(50, 200)
```

### Etapa 6: Posicionar a tartaruga para o segundo lado
Com `right(140)`, a tartaruga gira 140 graus para a direita para iniciar o outro lado do coração.

```python
right(140)
```

### Etapa 7: Desenhar o segundo arco simétrico
Outro arco de 50 unidades e 200 graus é desenhado, criando a curva superior do lado oposto do coração.

```python
circle(50, 200)
```

### Etapa 8: Completar o contorno do coração
Com `forward(133)`, a tartaruga desenha a segunda linha diagonal, fechando o formato do coração.

```python
forward(133)
```

### Etapa 9: Finalizar o preenchimento
Por fim, `end_fill()` completa o preenchimento do coração em vermelho.

```python
end_fill()
```

### Código Completo
Aqui está o código completo para desenhar o coração:

```python
from turtle import *
color('red')
begin_fill()
pensize(3)
left(50)
forward(133)
circle(50, 200)
right(140)
circle(50, 200)
forward(133)
end_fill()
```

O resultado será um coração simétrico vermelho com um contorno de 3 pixels, conforme a imagem abaixo:



