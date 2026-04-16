Alguns tópicos que vão ser abordados nesse material são:
**Índice de Conteúdos:**
- [Conceito Geral](#conceito-geral)
- [Estrutura de um GDD](#estrutura-de-um-gdd)
- [Ideia](#ideia)
- [Começando a criar o GDD](#começando-a-criar-o-gdd)
  - [Escrevendo a história](#escrevendo-a-história)
  - [Estilo do jogo](#estilo-do-jogo)
  - [Jogabilidade](#jogabilidade)
  - [Combate](#combate)
  - [Som e Musica](#som-e-musica)
  - [Interface (UI e HUD)](#interface-ui-e-hud)
  - [Requisitos Tecnicos](#requisitos-tecnicos)
  - [Sistema de Salvamento](#sistema-de-salvamento)
  - [Progressao e Recompensas](#progressao-e-recompensas)
  - [Acessibilidade](#acessibilidade)
- [Referências](#referências)

![Imagem GDD](assets/image.png)

--------
# Conceito Geral
Você deve se perguntar "Como posso começar a criar meu jogo?", a maioria pensa que começamos já desenvolvendo código ou criando as artes. Não que seja errado começar assim, apenas não é ideal, visto o quão complexo é criar um jogo do começo ao fim. Então como começar? pelo documento de GDD (Game Design Document). 
O que é esse GDD? É um documento onde vamos escrever todas as informações importantes sobre nosso jogo. Nele vamos colocar todas as informações necessárias para fazer nosso jogo funcionar, como personagens, mundo, chefes, mecânicas... www.gamedesigncanvas.com

## Por que fazer?
Facilitar planejamento do jogo. Podemos encontrar falhas na nossa mecânica, pensar numa ideia mais condizente com nossa história ou refazer uma mecânica sem sentido. **O GDD é o coração de qualquer jogo.**
Lembrando que ele é um documento vivo, sempre vamos precisar retornar a ele para atualizar as mudanças futuras.

## Onde fazer o GDD?
Isso depende muito da equipe. Você pode fazer nos seguintes formatos: 
- Slides no PowerPoint ou Google Apresentações;
- Documento no Docs ou Word;
- Formato de wiki em um site (Esse é mais indicado para jogos grandes, onde tem muito detalhe que precisa ser documentado e equipe precisa ter acesso rápido).
O que você usa para fazer é muito flexível, a única indicação é **não** ser numa folha de papel escrito com caneta. O GDD tem que ser vivo, atualizações vão ser importantes. 

# Estrutura de um GDD
Para estruturar o GDD é necessário já ter algumas ideias de como vai ser o jogo, pelo menos um rascunho. Alguns tópicos importantes para ter em mente na construção de um GDD são:
- Título do jogo;
- Narrativa, como vai ser a história do seu jogo e seu mundo?
- Gênero do jogo. Vai ser um RPG? Uma *Visual Novel*? Um jogo de aventura?
- Ele vai ser para PC? Para Mobile? Qual plataforma vai ser?
- Será dividido em fases? Quantas fases vão ser?
- Personagens, amplie quais personagens vão ser e suas histórias/motivações;
- Qual público alvo do jogo?
- Mundo do jogo, descrever onde ele se passa. Ambientação do jogo;
- Combate, caso precise ter;
- Jogabilidade, como o jogo vai funcionar? como o jogador vai interagir com o mundo?
- Controles, quais botões vão ser necessários? 
- Itens. O jogo tem itens? Quais? Para que eles servem?
- Quais referências do jogo?
- 3d? 2d?
Lembrando que dependendo do projeto e seu tamanho esses tópicos podem mudar ou até mesmo aumentar, depende muito de qual jogo estás produzindo, mas esses tópicos são a base da maioria dos GDD's.

# Ideia
Para conseguirmos ter uma ideia central do jogo é importante respondermos uma pergunta central:
**Qual o objetivo do seu jogo?**

Pode parecer uma pergunta obvia mas ela tem que ser o centro do direcionamento do fluxo do seu jogo. Por exemplo, se seu jogo for educativo ele vai precisar ser simples e com linguagem acessível. Se for *visual novel*, é importante ter uma história cativante e que provoque curiosidade. Saber exatamente o objetivo do seu jogo pode ajudar na construção de mundo, personagens, itens, chefes, batalhas, etc.
Caso o projeto seja em grupo é mais importante ainda a boa estruturação dessas ideias, dado que são muitas cabeças com conceitos e vivências diferentes. Normalmente o *brainstorm* (chuva de ideias em inglês) acontece dessa maneira: várias pessoas soltando as ideias que acham interessantes para aquele jogo e cabe a equipe decidir em conjunto qual vai entrar no GDD. Essa parte é crucial no desenvolvimento pois assim nós conseguimos expandir nossa história de uma maneira fluída, a equipe tendo um consenso de como o jogo será estruturado melhora muito o processo de desenvolvimento dele. Para fazer esse *brainstorm* é necessário apenas uma sala com a equipe, confiança entre todos e um quadro para anotar as coisas interessantes ditas. 

# Começando a criar o GDD
# Escrevendo a história
Beleza, digamos que você já tenha em mente o que você quer tratar nesse jogo, já definiu bem quais mecânicas quer que ele tenha e personagens (lembrando que isso pode ser mutável caso seja necessário), então qual o próximo passo? Vamos começar a escrever sua história.
É extremamente importante que você escreva a história do seu jogo, contando sobre o/a protagonista e a ambientação do seu mundo, pois assim facilita bastante o trabalho dos artistas em desenhar as artes. É um processo bastante particular que depende muito da sua criatividade em como expandir essa história. 
"Mas meu jogo é um jogo simples e curto, preciso realmente ter uma história?"
Olha, é importante ter sempre uma história, nem que seja pequena, por trás do jogo. Deixa ele mais rico, independente do tempo de gameplay. Claro que há jogos que não vão ter necessariamente uma história para contar (como xadrez, sudoku, poker....), mas é bom sempre ter algo para contar. 
"Preciso colocar aspectos complexos como *cutsceanes* ou diálogos entre personagens?"
Depende, você quer colocar? Se você não acha que se encaixe no jogo, não precisa colocar. Tem histórias que se contam sozinhas através de elementos do próprio jogo, nem tudo precisa ser verbalizado, as vezes podemos utilizar da arte ao nosso favor nesse aspecto. Por exemplo, se eu quero referenciar um/uma personagem que tenha TEA (Transtorno do Espectro Autista), ao invés de colocar um diálogo com ela falando sobre (que não necessariamente seria ruim), podemos colocar na sua arte ela usando um colar de identificação, as vezes o menos é mais num jogo.

# Estilo do jogo
É importante definir o gênero do jogo que estamos trabalhando com informações sobre como vai ser a movimentação de câmera, estilo de arte e jogabilidade. Esses aspectos que compõe o estilo de um jogo são particulares de cada projeto, mas em tese é importante destacar que precisamos ter isso bem destacado no nosso GDD, bem como o público alvo daquele jogo. 

# Jogabilidade
Quanto mais detalhada for a jogabilidade no GDD, melhor. Utilize sempre o prefixo do como para pensar na sua jogabilidade, "Como minha personagem vai atacar?", "Como se comporta?". Isso tem que ser destacado para cada personagem, independente de qual seja. É importante para entender como será as mecânicas e o fluxo do jogo, tem que ser bem expandido e detalhado. 

# Combate
Seu jogo tem algum sistema de combate? Como ele é? 
É preciso analisar se faz sentido ter algum combate no seu jogo para a progressão de história, se sim, é importante destacar alguns aspectos como:
- Como cada inimigo vai ser combatido?
- Como será o ataque? Fogo? Água? Ar?
- Tem alguma animação? Como ela é?
- O nome do ataque faz sentido com a execução? 
Por exemplo: Quero que meu jogo RPG tenha um NPC, que seja um pássaro, que seu ataque seja uma rajada de penas. Eu poderia colocar no GDD a descrição da seguinte maneira:
"Pid, o pássaro sombrio: {descrição de personagem, história}
**Habilidades:**
Rajada de penas
Tipo: Ar
Execução: Pid dispara uma rajada de penas caso o player invada sua zona de conforto sem oferecer alpiste primeiro.
Animação: Ele saí de sua pose normal e passa a carregar um ataque, durante 1.24s. Após isso, atira uma rajada de penas.
"
# Som e Musica
Quantas vezes você estava jogando e percebeu que desligou o som sem querer, mas continuou jogando normalmente? Agora pensa: quando foi a última vez que você jogou algo e o som estava errado para aquela cena? Provavelmente você percebeu na hora, mesmo sem saber explicar o porquê. Isso porque **o som é responsável por grande parte da imersão de um jogo**, mesmo que o jogador não perceba conscientemente.

No GDD, o som precisa ser pensado em duas frentes: a trilha sonora e os efeitos sonoros (_SFX_). Vamos ver melhor sobre
## Trilha Sonora

A trilha sonora define a identidade emocional do jogo. Ela comunica o tom antes de qualquer coisa ser dita ou mostrada. Para documentá-la no GDD, não é necessário já ter as músicas prontas, basta descrever a intenção:

- Qual o estilo musical? _Chiptune_, orquestral, eletrônico, acústico?
- Qual a emoção que cada parte do jogo precisa provocar? A fase inicial precisa de algo calmo e introdutório, ou já começa agitado?
- O jogo tem temas para personagens específicos? Um vilão com um tema reconhecível, por exemplo?
- A música muda de acordo com o que acontece na tela, como quando o jogador está quase morrendo?

Esses detalhes ajudam muito o compositor, ou a pessoa que vai escolher as músicas, assim como ajudam o programador a entender quando e como cada faixa deve tocar.
## Efeitos Sonoros (SFX)

Se a trilha sonora é a emoção, os _SFX_ são o peso do jogo. Um ataque sem som parece vazio. Um item coletado sem nenhum feedback sonoro parece que não funcionou. **Cada ação importante do jogo precisa ter um som associado a ela, é crucial**

No GDD você não precisa descrever o arquivo de áudio, mas sim a sensação esperada. Por exemplo:

- Ataque da protagonista: um som curto e seco, que transmita impacto físico
- Coletar uma moeda: um som agudo e rápido, recompensador
- Receber dano: algo que cause desconforto leve, sinalizando perigo
- Game over: algo mais grave e lento, que marque a derrota sem frustrar demais

Pensa nos sons como parte da _interface_ do jogo. Eles confirmam que o jogo recebeu a ação do jogador.

---
# Interface (UI e HUD)

A _interface_ de um jogo é tudo que o jogador vê na tela que não faz parte do mundo do jogo em si. Ela existe para passar informação de forma rápida e clara. **Uma boa interface é aquela que o jogador quase não percebe que está usando**, porque ela entrega o que precisa sem atrapalhar a experiência.

Existem dois termos importantes aqui:
- _UI (User Interface)_: a interface em geral, incluindo menus, telas de pausa, inventário, configurações
- _HUD (Heads-Up Display)_: os elementos que ficam visíveis durante o jogo, como barra de vida, contador de moedas ou mapa

## O que documentar no GDD
Para cada tela e elemento de interface, é importante responder:

- O que essa tela precisa mostrar?
- O jogador acessa ela como?
- O que ele pode fazer nela?

Por exemplo, um menu de pausa simples precisa mostrar a opção de continuar, configurações e sair para o menu principal. Parece óbvio, mas documentar isso evita que cada pessoa da equipe imagine uma versão diferente dessa tela.
Para o _HUD_, vale pensar em quais informações são tão importantes que precisam estar sempre visíveis. Barra de vida? Quantidade de munição? Um minimapa? Cada elemento que entra no _HUD_ é um elemento competindo pela atenção do jogador, então **menos costuma ser mais**.

"Mas meu jogo é simples, precisa mesmo ter tudo isso documentado?" Sim, principalmente se for um projeto em grupo. Decisões de interface parecem pequenas mas geram muita discussão quando não estão definidas com antecedência.

---

# Requisitos Tecnicos
Assim como o GDD define o que o jogo vai ser, os requisitos técnicos definem com o que ele vai ser feito. Essa parte é especialmente importante em projetos colaborativos, onde diferentes pessoas precisam usar as mesmas ferramentas para que tudo funcione junto no final.

## Engine
A _engine_ é o software base onde o jogo é construído. As mais usadas no desenvolvimento independente são Unity, Godot (que temos material dispónivel no link: - ) e GameMaker. A escolha depende do tipo de jogo, da experiência da equipe e, em alguns casos, do orçamento. Não existe a melhor _engine_, existe a mais adequada para o projeto. Documente qual será usada e, se houver motivo específico para a escolha, anote também, isso ajuda novos membros a entenderem a escolha.

## Ferramentas de Arte e Audio
Quais programas serão usados para criar os _assets_ do jogo? Para pixel art é comum usar Aseprite. Para arte vetorial, Inkscape ou Illustrator. Para modelagem 3D, Blender. Para áudio, Audacity ou FL Studio. Alinhar isso no GDD evita que um artista entregue arquivos em formatos que o programador não consegue importar.

## Controle de Versao
Em projetos em grupo, **o controle de versão é indispensável**. Ele permite que várias pessoas trabalhem no projeto ao mesmo tempo sem sobrescrever o trabalho umas das outras, e guarda o histórico de tudo que foi alterado. Git com GitHub ou GitLab são as opções mais comuns. Se a equipe nunca usou, vale dedicar um tempo para aprender o básico antes de começar o desenvolvimento, também temos material sobre Git para te ajudar a aprender: link

---
# Sistema de Salvamento

Um aspecto do jogo que muita equipe deixa para decidir durante o desenvolvimento é o sistema de salvamento, e esse atraso costuma gerar retrabalho. **Definir como o jogo salva o progresso do jogador é uma decisão de design**, não apenas técnica.

Existem algumas abordagens principais:
- **Salvamento automatico por _checkpoint_**: o jogo salva em pontos específicos, como ao entrar em uma nova fase ou derrotar um chefe. O jogador não controla quando salva.
- **Salvamento manual**: o jogador escolhe quando salvar, geralmente acessando um menu. Dá mais controle, mas exige que o jogador lembre de salvar.
- **Salvamento continuo**: o jogo salva o estado constantemente, sem interrupção. Comum em jogos mobile e em jogos com mundos abertos.

A escolha tem impacto direto no design das fases. Um jogo com _checkpoints_ pode ter fases longas porque o jogador sabe que não vai recomeçar do zero. Um jogo sem _checkpoints_ precisa de fases mais curtas ou mais indulgentes, para não frustrar.

"Meu jogo é curto, preciso pensar nisso?" Se o jogador pode fechar o jogo no meio e precisar continuar depois, sim. Mesmo jogos pequenos precisam ter isso claro no GDD.

---

# Progressao e Recompensas

O que faz um jogador continuar jogando além das primeiras horas? Em grande parte, **a sensação de que seu personagem ou sua habilidade está crescendo**. Isso é a progressão. Documentar esse sistema no GDD é tão importante quanto documentar o combate, porque ele afeta diretamente o quanto tempo o jogador vai querer ficar no jogo.

## Como o personagem evolui?
Pensa nas seguintes perguntas para definir sua progressão:

- O personagem ganha experiência (_XP_) e sobe de nível?
- Subir de nível libera novas habilidades, ou melhora as que já existem?
- A progressão é linear, ou o jogador pode escolher em qual direção evoluir?
- Existe algum tipo de _build_, onde escolhas diferentes levam a personagens diferentes?

Não é obrigatório ter um sistema de _XP_ e níveis. Há jogos onde a progressão acontece através de itens encontrados, ou de habilidades desbloqueadas conforme a história avança. O importante é que exista alguma forma de o jogador sentir que está avançando.

## Recompensas

Cada acao significativa no jogo deveria ter uma recompensa proporcional. Derrotar um inimigo comum pode dar uma pequena quantidade de moedas. Derrotar um chefe pode liberar uma habilidade nova ou um item raro. Completar uma fase pode desbloquear um trecho de história. **Recompensas são o jogo dizendo ao jogador "você fez algo certo"**, e precisam estar equilibradas para não serem nem fáceis demais nem difíceis demais de obter.

No GDD, liste quais ações geram recompensas, o que o jogador recebe e qual o peso daquela recompensa na progressão geral.

---

# Acessibilidade

Acessibilidade em jogos é o conjunto de opções e decisões de design que permitem que mais pessoas consigam jogar. Não se trata apenas de inclusão de pessoas com deficiência, embora isso seja central, mas também de adaptar a experiência para diferentes perfis de jogador.

"Meu jogo é indie e pequeno, preciso me preocupar com isso?" Sim, e por duas razoes. A primeira é que ampliar quem pode jogar o seu jogo é bom para o jogo. A segunda é que muitas práticas de acessibilidade melhoram a experiência para todo mundo, não só para quem tem alguma necessidade específica.

Alguns pontos importantes para documentar no GDD:

- **Legendas**: o jogo tem diálogos? Há opção de ativar legendas? O tamanho da fonte é ajustável?
- **Controles**: o jogador pode remapear os botões? Há suporte para diferentes periféricos?
- **Dificuldade**: o jogo tem modos de dificuldade? Existe alguma opção para tornar o jogo mais acessível sem remover a experiência central?
- **Daltonismo**: a interface ou elementos importantes do jogo dependem de distinguir cores? Se sim, há alternativas visuais como formatos ou ícones diferentes?
- **Audio**: o jogo depende de áudio para passar informações importantes? Se sim, existe alguma alternativa visual para jogadores surdos ou com deficiência auditiva?

Não é esperado que um jogo pequeno implemente tudo isso de uma vez. Mas pensar nisso desde o GDD evita que você precise refazer sistemas inteiros mais tarde só para adicionar uma legenda ou um modo daltônico.

# Crie seu GDD
Nós preparamos um modelo base para você começar a documentar as ideias da sua equipe sem precisar criar tudo do zero. 

**[Clique aqui para acessar o Template de GDD](template.md)**

* Lembrando que o template é em .md, recomendamos fortemente usar o software **[Obsidian](https://obsidian.md/)** ou o **[Notion](https://www.notion.com/)**. Você pode adptar para usar ferramentas como **[Miro](https://miro.com/pt/)** ou o **[Excalidraw](https://excalidraw.com/)** para um ambiente interativo. 

_____
# Referências
[COMO CRIAR UM GDD (GAME DESIGN DOCUMENT) COM MODELO PARA DOWNLOAD](https://www.youtube.com/watch?v=aqXwal3tRkg) 

[8 Passos para Fazer um GDD (GAME DESIGN DOCUMENT) ](https://www.youtube.com/watch?v=JdMlfvSKaVg)

[4 TIPOS DE GDD (GAME DESIGN DOCUMENT)](https://www.youtube.com/watch?v=8NOJfc1yGQs&t=28s)

[Game Design Documents - a Minimalist Approach INGLES](https://www.youtube.com/watch?v=uBxYGFRi-S4&t=1060s)
