# Metodologia

## Versionamento
| Data |Versão|Descrição| Autor             |
| ------ | --- | --- | ----------------- |
| 31/01/2022  |1.0|Abertura do documento| [@MateusCaltabiano](https://github.com/MateusCaltabiano) |
| 06/03/2022 | 1.1 | Atualização  do Documento de Metodologia | [@phnog](https://github.com/phnog) 
25/04/2022 | 1.2 | Atualização  do Documento de Metodologia | [@MatheusPerillo](https://github.com/MatheusPerillo)

## Introdução

Este documento fará um breve resumo das metodologias ágeis escolhidas para auxiliar no
desenvolvimento do nosso projeto. As metodologias serão brevemente apresentadas junto
com seus pontos mais importantes. Ao final do documento há uma tabela com os membros
do grupo e suas respectivas funções.

## Metodologias

### SCRUM:
É um método que se baseia em **ciclos**, ou ***Sprints***. Para iniciar, deve ser feito um
*Product backlog* que é de onde vem a base para a *Sprint backlog*. É realizada uma *Sprint
Planning*, onde o *Product Owner*(PO) seleciona os itens mais importantes do *Product
backlog* para serem implementados no decorrer da *Sprint*, que geralmente leva de 2 a 4
semanas, mas pode durar meses também. No nosso caso, as sprints serão semanais.
Em uma *Sprint*, ocorre a chamada *Daily Scrum* diariamente, que é uma reunião
rápida, de 5 a 15 minutos, onde os membros devem dizer brevemente como vai o
andamento de suas tarefas, buscando compartilhar conhecimento com o time e, mais
importante ainda, o impedimento de cada um, para que cada um seja devidamente
ajudado.
No final da *Sprint*, a equipe apresenta as funcionalidades que foram implementadas
com sucesso na *Sprint review*, e, em seguida, é realizada uma *Sprint retrospective* para
depois iniciar a próxima Sprint, ou, o próximo ciclo.

* ***Product backlog***: é uma lista contendo todas as funcionalidades desejadas para um
produto. O conteúdo desta lista é definido pelo Product Owner. O Product Backlog
não precisa estar completo no início de um projeto. Pode-se começar com tudo
aquilo que é mais óbvio em um primeiro momento. Com o tempo, o Product Backlog
cresce e muda à medida que se aprende mais sobre o produto e seus usuários;

* ***Product Owner***: É a pessoa que, junto com o cliente, define os itens do Product
backlog e os prioriza nas Sprint plannings;

* ***Sprint backlog***: É uma lista de tarefas que o time vai completar ao longo da sprint. As
tarefas são selecionadas a partir do Product backlog.

* ***Sprint***: É o ciclo base do método SCRUM;

* ***Daily Scrum***: é uma reunião rápida, de 5 a 15 minutos, onde os membros devem
dizer brevemente como vai o andamento de suas tarefas, buscando compartilhar
conhecimento com o time e, mais importante ainda, o impedimento de cada um,
para que cada um seja devidamente ajudado;

* ***Sprint review***: É a reunião onde o projeto é avaliado em relação aos objetivos da
Sprint, e onde são feitas as demonstrações das funcionalidades implementadas;

* ***Sprint retrospective***: O Sprint Retrospective ocorre ao final de um Sprint e serve para
identificar o que funcionou bem e o que pode ser melhorado;

### Kanban:

Em japonês, Kanban significa cartão ou sinalização e é uma das metodologias
ágeis para organizar seu time. Foi criada na década de 40 pela Toyota e se baseia em
visualizar suas tarefas a fazer, as tarefas que estão sendo feitas e as tarefas concluídas,
deixando o progresso do time ou indivíduo visualmente acessível para todos, o que traz
diversos benefícios, como:

* Evita a procrastinação e o tempo ocioso dos colaboradores;
* Economiza tempo;
* É prático e fácil de ser implementado;
* Ajuda na hierarquização de tarefas;
* Ajuda a mensurar a produtividade;
* Facilita a comunicação;

A aplicação do Kanban é simples. Podem ser utilizados post-its, uma lousa ou até mesmo
softwares especializados, mas o importante é deixar claro suas tarefas a fazer, suas tarefas
em desenvolvimento e suas tarefas finalizadas. Esses 3 pontos são a base do Kanban, mas o
grupo que o utiliza é livre para adicionar tópicos, como os impedimentos, por exemplo.

* To do: Tarefas a fazer;
* Doing: Tarefas sendo feitas atualmente;
* Done: Tarefas finalizadas;

### eXtreme Programming

Essa metodologia é baseada em um pequeno conjunto de
valores, princípios e práticas que diferem da maneira tradicional de produzir software

#### Valores:

* **Comunicação**: É preciso comunicação constante entre o cliente e a equipe que está
desenvolvendo o projeto, e para isso é importante o diálogo presencial.
* **Coragem**: É preciso compreender que o cliente pode mudar de ideia a qualquer
momento e se adaptar as mudanças com segurança e coragem.
* **Feedback**: É importante entregar novas funcionalidades o mais rápido possível, para
que o cliente entenda as consequências do que pediu.
* **Respeito**: É o valor que dá sustentação para todos os outros. Membros da equipe só
irão se preocupar uns com os outros se se respeitarem.
* **Simplicidade**: Focar em fazer aquilo que é claramente necessário para evitar perda
de tempo

Os valores são a base da XP, e algumas práticas serão utilizadas para o desenvolvimento de
nosso projeto, como a integração contínua.

### Papéis da equipe

Papel | Responsabilidade | Time A | Time B | Time C  |
---|---|---|---|---|
Scrum Master | O Scrum Master é responsável pela implementação do Scrum tal como definido no Guia do Scrum. Ajudando todos a compreender a teoria e a prática do Scrum, tanto dentro da Scrum Team como dentro da organização. | [@lucascard](https://github.com/lucascard) | [@MateusCaltabiano](https://github.com/MateusCaltabiano)
Product Owner | O Product Owner é responsável por maximizar o valor do produto resultante do trabalho da Scrum Team. O Product Owner é também responsável pela gestão eficaz do Product Backlog. | [@matheusmsvieira](https://github.com/matheusmsvieira) | [@MatheusPerillo](https://github.com/MatheusPerillo) | [@Julio-eng](https://github.com/Julio-eng)
Arquiteto de Software | Este profissional é responsável por garantir o seguimento das diretrizes de um projeto de desenvolvimento de software que normalmente são: qualidade dos sistemas, contexto organizacional, funcionalidade, usabilidade, performance, desempenho e baixo custo de investimento. |  | [@CorreiaJV](https://github.com/CorreiaJV) | [@ian-dcg](https://github.com/ian-dcg)
Devops | O devOps permite a integração das equipes, padronizando e implementando mais velocidade nos processos. Sua atuação agrega um ciclo de planejamento e idealização, seguindo pelo desenvolvimento até o feedback do resultado final. | [@EuricoAbreu](https://github.com/EuricoAbreu) | [@MtsSrs](https://github.com/MtsSrs)
Desenvolvedores | Os Desenvolvedores são as pessoas da Scrum Team que estão empenhados em criar qualquer aspecto de um Increment utilizável em cada Sprint. | [@EuricoAbreu](https://github.com/EuricoAbreu), [@Fellipepcs](https://github.com/Fellipepcs) | [@phnog](https://github.com/phnog), [@iagocabral](https://github.com/iagocabral) | [@murilopbs](https://github.com/murilopbs), [@Alladin-51](https://github.com/Alladin-51), [@Charles-serafim](https://github.com/charles-serafim)

### Bibliografia

http://www.desenvolvimentoagil.com.br/scrum/
http://www.desenvolvimentoagil.com.br/xp/praticas/design_incremental
https://www.digitalhouse.com/br/blog/como-usar-metodologia-kanban
https://fga-eps-mds.github.io/2020.2-Hortum/Documento_metodologia/

