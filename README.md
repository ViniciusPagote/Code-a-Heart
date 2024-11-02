# Desenhando um Coração com Python

O amor pelo python existe e nada melhor que uma brincadeira com a biblioteca Turtle para nós destrair do dia a dia.

# O que é o Python?
Python é uma linguagem de programação muito usada por ser simples e poderosa. Ela permite criar desde pequenas automações até sistemas complexos, como sites e análises de dados. Python é popular porque é fácil de aprender e tem uma grande comunidade para ajudar, com várias

# O que é a Biblioteca Turtle do Python?
A biblioteca Turtle em Python é uma ferramenta simples e divertida usada para criar desenhos gráficos e aprender os fundamentos da programação. Inspirada na linguagem de programação Logo, a Turtle permite que você controle uma "tartaruga" (um cursor gráfico) que se move pela tela para desenhar formas, linhas, e até criar animações.

Com comandos básicos como forward, left, right e penup, você consegue desenhar tudo, desde figuras geométricas simples até obras de arte mais complexas. A biblioteca é ideal para iniciantes que querem aprender programação de uma forma visual e interativa.

# Agora o Passo a Passo
- Etapa 1
  Instalar e importar a biblioteca Turtle:
  A biblioteca Turtle já vem com o Python, então normalmente basta importá-la.

- Etapa 2
  Defina o ambiente de desenho, o comamdando *color('red')* define a cor da "tartaruga" (o cursor) e, nesse caso, também define a cor da área que será preenchida ao terminar o desenho. O comando begin_fill() informa ao Python que o próximo desenho deve ser preenchido com a cor definida (vermelho).

Codigo exemplo:
  color('red')  
  begin_fill()

- Etapa 3
  O comando pensize(3) define a espessura da linha do contorno para 3 pixels.

- Etapa 4
  Com o comando left(50) e forward(133) a "tartaruga" faz um giro de 50 graus para a esquerda e, em seguida, move-se 133 unidades para frente, desenhando uma linha diagonal que representa uma parte lateral do coração.

- Etapa 5
  Com o comando circle(50, 200) cria um arco com um raio de 50 unidades e um ângulo de 200 graus, formando a parte arredondada superior de um lado do coração.
    
- Etapa 6
  Com o comando right(140) a tartaruga faz uma rotação de 140 graus para a direita, virando na direção oposta para desenhar a outra metade do coração.

- Etapa 7
  Com o comando circle(50, 200) o outro arco de círculo é desenhado, igual ao anterior, mas no lado oposto, criando o lado simétrico da curva superior do coração.
  
 - Etapa 8
  Com o comando forward(133) completa a segunda linha diagonal para baixo, fechando o formato do coração.
  
  - Etapa 9
  Com o comando end_fill() finaliza o preenchimento do coração, colorindo-o de vermelho conforme definido no início.

  O resultado é um coração simétrico vermelho com contorno de 3 pixels.

  Conforme imagem abaixo:
