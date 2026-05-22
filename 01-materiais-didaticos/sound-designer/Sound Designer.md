# Conceito Geral
Os sons desempenham um papel importante e crucial nos jogos, sendo um fator determinante para indicar emoções com base na experiência que você quer transmitir. Por exemplo: uma porta abrindo, um barulho de tiro, um barulho de soco, etc. Já pensou em algum jogo que não tivesse som? Seria bem sem graça, né?

Podemos definir o objetivo do designer de som em três partes: 
- Proporcionar avisos de mecânicas de jogo, ou seja, reforçar o que está acontencendo ao seu redor
- Dar feedbacks auditivos ao usuário, seja bons ou ruins
- Passar emoções

# História
Abaixo vamos adentrar um pouco na história da primeira geração de videogames para entender melhor como era o Sound Designer antigamente, dando uma breve contextualização.
## Tennis for two (1958)
Não se tem consenso sobre quem inventou o primeiro jogo de videogame, mas grande parte dos historiadores acreditam que tenha sido o físico William Higinbotham, com o jogo Tennis for two (1958).Foi produzido em três semanas para entreter os visitantes do laboratório de onde trabalhava, o Laboratório Nacional de Brookhaven. Foi demonstrado através de um osciloscópio e com dois controles de alumínio personalizado.
É um jogo de simulação bidimensional de tênis, onde os jogadores ajustam o ângulo de seus chutes com um botão no controle e tentam acertar a bola por cima da rede pressionando um botão.
![[Pasted image 20260522081120.png|312]]
[Leia mais sobre aqui](https://en.wikipedia.org/wiki/Tennis_for_Two)
[Vídeo mostrando o Tennis for Two](https://youtu.be/6PG2mdU_i8k)
## Spacewar (1961)
Em 1951, Marty Bromley comprou máquinas eletromecânicas e criou a Service Games, que logo após na década de setenta se tornou popular na era dos fliperamas por transformar seus computadores em máquinas de jogos. Em 1961 Steve Russel, aluno do MIT, criou Spacewar! Considerado o primeiro game interativo para computador, jogo esse que em 1962 foi aperfeiçoado por Peter Samson e Dan Edwards.
![[Pasted image 20260522083925.png|368]]
Spacewar! no Museu da História do Computador, em 2007
[Leia mais sobre](https://pt.wikipedia.org/wiki/Spacewar!)
[Vídeo sobre o Spacewar!](https://www.youtube.com/watch?v=ri7mCIsR5Hs)
## Pontos Importantes
O primeiro arcade surgiu inspirado nesse jogo com Nolan Bushnell (que com seu amigo Ted Dabney, fundaram a empresa Atari). Ele viu o jogo e quis adaptar para uma máquina de fliperama, o nome dado foi Computer Space e foi vendido para a Nutting Associates em 1971. Mesmo ele não tendo o sucesso que era esperado, Ralph Baer viu uma oportunidade de desenvolver algo, foi o primeiro passo para desenvolver o Magnavox Odyssey (1972), pensado inicialmente para treinar soldados em seus reflexos, esse console iniciou a primeira geração dos consoles.
![[Pasted image 20260522084246.png|301]]
Magnavox Odyssey (1972)
[Leia mais sobre](https://pt.wikipedia.org/wiki/Magnavox_Odyssey)
[Vídeo sobre o Magnavox Odyssey](https://youtu.be/IMzJbWyoeMA)

Embora inovador na época, não teve o sucesso esperado, fazendo com que o videogame fosse retirado das lojas em 1973. O sucesso dos jogos nessa época é dado pelo PONG em 1972, nos fliperamas da época, ele iniciou a grande era de ouro dos fliperamas. Além disso, colocou a ATARI como principal produtora de arcades.
Repare no vídeo abaixo da imagem a quantidade de sons que temos no jogo, e como ele soa aos ouvidos.
![[Pasted image 20260522084758.png|173]]
[Leia mais sobre o PONG](https://pt.wikipedia.org/wiki/Pong)
[Vídeo mostrando o Atari Pong](https://youtu.be/fiShX2pTz9A)

Em 1978 a Taito lança o Space invaders, que permitia gravar recorde de pontuação, sendo um grande sucesso. Sendo um dos primeiros jogos de tiro com gráfico bidimensional, tendo o objetivo de destruir as ondas de naves com uma espaçonave humana para ganhar o maior número de pontos.
![[Pasted image 20260522085051.png|214]]
[Leia mais sobre Space Invaders](https://en.wikipedia.org/wiki/Space_Invaders)
[Vídeo mostrando o Space Invaders 1978](https://youtu.be/MU4psw3ccUI)

Em 1980 a Namco lançou Pac-Man, fugindo da regra de jogos arcade serem exclusivamente de tiro. 
Em 1981 a Nintendo lança Donkey Kong, entrando para o mercado de jogos.
Voltando aos consoles, em 1977 a Atari lança o Atari 2600, que tinha o Space Invaders (a Atari obteve licença)
Curiosidade: Parte do time de desenvolvedores de jogos da Atari, após desentendimentos com a diretoria abriram a Activision, em 1980.

# Termos técnicos
## Frequência de som
Basicamente é a taxa a que a vibração vai acontecer. Quanto mais devagar a taxa, mais grave é o tom do áudio. Quão mais rápido for, mais agudo será. 
![[Pasted image 20260522025002.png|411]]
[Fonte](https://brasilescola.uol.com.br/o-que-e/fisica/o-que-e-som.htm)
Um som de explosão por exemplo, **pode ser uma ampla faixa de frequência**

## Envelopes sonoros
São a visualização de um som do começo ao fim, ou a própria forma de onda. Vejamos melhor como é dividido um som na imagem abaixo:
![[Pasted image 20260522025440.png|731]]
[Fonte](https://academiadebeats.com.br/blog/envelope-adsr-modificando-timbres/)
Legenda:
- Ataque (*attack*): Representa o tempo que leva entre o silêncio até a intensidade ou volume máximos;
- Decaimento (*decay*): Representa a queda de intensidade que ocorre depois do auge do ataque e que dura até que o som chegue na parte de sustentação;
- Sustentação (*sustain*): Representa o volume em que o som é reproduzido por maior parte da duração do som;
- Repouso (*release*): Representa o tempo que o som leva para desaparecer até o silêncio.
Lembrete: Todo som tem um perfil de ASDR diferente, tendo uma dinâmica de som diferente. 

## Atenuação
Nos jogos, atenuação refere-se à redução na força de um sinal ao se aproximar ou se afastar da fonte do som. 
No exemplo abaixo, se fossemos escutar, o personagem iria falar mais alto conforme a linha de atenuação está mais acima e falaria mais baixo conforme fosse se distanciando.

![[Pasted image 20260522030718.png|567]]
[Fonte](https://www.maisbolsas.com.br/enem/fisica/natureza-do-som)
É importante para jogos em geral, pois o jogador tem que ter o feedback tanto daquilo que está longe quanto daquilo que está perto.
## Equalização
É o processo de ajustar diferentes faixas de frequências em um som. Ela pode manipular o som impulsionando ou cortando determinadas frequências ou faixas de frequências. Ou seja, podemos usar isso para eliminar ruídos, intensificar barulhos, intensificar tons e até alterar o timbre.
![[Pasted image 20260522031304.png|530]]
[Fonte](https://xtudomagazine.com.br/configuracoes-de-equalizador-para-o-som-perfeito/)
## Reverb (reverberaçao)
Um som que reflete em algum lugar, seja num objeto ou até no ambiente que o personagem está inserido. Podemos usar para alocar vários sons juntos (chute, soco e cabeçada num jogo de luta) ou um eco (elevador, sala vazia, montanha...).
![[Pasted image 20260522031956.png|355]]
[Fonte](https://www.practical-music-production.com/reverb/)



_____
# Referências
[Sound Design Riot Games - Inglês com legenda](https://youtu.be/KcorIwJscFA)
[Audio Effects Explained for Beginners - Inglês](https://www.musicsequencing.com/article/audio-effects-explained-for-beginners)
[Sound Design in Arcane - Inglês](https://www.youtube.com/watch?v=ULx1CkqLbnc)