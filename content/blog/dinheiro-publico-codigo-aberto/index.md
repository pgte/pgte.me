---
title: Dinheiro público, código aberto
date: "2020-02-24T15:04:10.000Z"
description: Sempre que o dinheiro público for usado para comprar ou desenvolver software, este software deve ser público e reutilizável.
---

> Sempre que o dinheiro público for usado para comprar ou desenvolver software, este software deve ser público e reutilizável.

O ano é 1999, e eu estava no início do segundo ano numa empresa de consultoria, à qual me tinha juntado no ano anterior, enquanto terminava o curso de engenharia. Nesta fria manhã encontrava-me sentado numa pequena sala de reuniões de conhecida empresa que fabricava e vendia software de gestão de base de dados, acompanhado por dois colegas do trabalho. Eu, um reles júnior e o mais novo do grupo, estava aqui, calculei eu, pelo meu interesse no ecossistema Java, que nesta altura começava a florir. Ainda na sua infância, esta linguagem e plataforma de desenvolvimento tinha vindo a ser vista como o maior competidor direto à Microsoft e o seu eco-sistema. Esta plataforma Java, ao contrário da competição, tinha um esquema de licenciamento de código aberto e de uso liberal. Inventada pela histórica Sun Microsystems, o crescimento do Java implicava o crescimento da Sun Microsystems, que na altura vendia hardware e o respetivo sistema operativo.

![Lisboa](ricardo-rocha-WyKI9y0TQoY-unsplash.jpg)

*Photo by Ricardo Rocha on Unsplash*

De volta à reunião em causa. Esta empresa estava a apresentar um produto para construção de portais.
Neste ano a internet ainda dava os primeiros passos no mundo do consumidor. A banda-larga era ainda rara, e a internet era principalmente acedida, em Portugal, através de uns lentos modems que tínhamos de ligar à linha telefónica.

E os portais do género do Yahoo estavam na moda, e todos queriam ter um. Este produto permitia então o desenvolvimento e entrega de um dito portal web, utilizando a linguagem de programação Java. Não sem alguma relutância dos representantes deste fornecedor, consegui extrair que este produto era — com a excepção do motor de base-de-dados, que era licenciado à parte, — composto por uma série de componentes open-source (Apache server e Apache Tomcat), bem como algumas bibliotecas — também open-source — e alguma fita-cola, cuspo e suor. A licença de utilização: uma pequena fortuna.

Esta empresa estava a re-empacotar software livre para o qual não tinham contribuído uma linha de código e a revender por uma licença exorbitante. Quantos terão eles enganado com esta tática?

Este episódio e alguns outros serviram para reforçar a minha convicção e aumentar o meu desgosto com a exploração que algumas empresas fazem do software livre. Serviu também para aumentar a minha preocupação com a forma como o software livre era (e ainda muitas vezes é) visto pelos decisores em  empresas privadas e administração pública. Se estes vendiam, tenho a certeza que alguns compraram — nunca ninguém foi despedido por comprar software a um grande fornecedor!

## Mas o mundo mudou!

O mundo do software entretanto mudou muito. O software livre e o movimento de código aberto ganharam por uma margem enorme. O software livre constitui uma parte gigante da infra-estrutura da internet e da web, e teve um papel essencial em baixar a barreira de entrada a novas empresas e à criação de novos produtos. Mas existe ainda um bastião de resistência que pode passar despercebido, mas que toca a todos nós cidadãos pagadores de impostos: a administração púbica. Sim, a administração pública, essa entidade abstrata que trabalha para nós, e a quem compete olear e minimizar o sofrimento que sentimos ao passar pelos milhentos processos burocráticos, que emprega um número muito considerável de portugueses e que necessita, como todas as instituições burocráticas, de sistemas de informação.

![Open](alex-holyoake-R-HXWCbCBGU-unsplash.jpg)

*Photo by Alex Holyoake on Unsplash*

Ao longo destes anos de profissão trabalhei inicialmente no mercado nacional, e algumas vezes (felizmente poucas) estive em contato com concursos públicos para construção de sistemas de informação. Mas eventualmente — viva a crise! — tive de trabalhar para empresas “lá fora” para sustentar a minha família, e por isso fui-me rapidamente desligando destas tricas e comunidades.

Até lá custou-me observar, não sem alguma náusea, a forma como a administração pública geralmente contrata os serviços de desenvolvimento dos sistemas de informação que vê necessários existir, e a forma como alguns fornecedores a (mal)tratam e, por vezes, exploram.

Como disse, tenho vivido neste país, mas quase como emigrado, trabalhando para empresas de fora, muito desligado da politiquice local, dos ditos concursos públicos e até das manchetes dos jornais. Focado na família e amigos, foquei-me também nas comunidades e projetos open-source, que muito florescem e são a base e o centro da inovação em muitas frentes das tecnologias de informação (pelo menos “lá fora”).

Mas as organizações públicas, tal como as outras, precisam de quem lhes desenvolva, integre e mantenha os sistemas, certo? A ideia de software livre é muito bonita e ideal, mas quem vai providenciar os serviços de desenvolvimento e manutenção de que precisamos no mundo real?

A questão aqui é mais complicada, e precisamos primeiro de definir o que é Software Livre.

Antes disso, quero dizer que as idéias e os princípios que aqui exploro são principalmente aplicáveis à administração pública. É claro que muitas coisas mais ou menos estranhas se passam em organizações privadas, mas isso não nos afeta muito como contribuintes (a não ser que o estado tenha de subsidiar ou salvar esta instituição quando esta estiver falida). No entanto muitos (se não todos) destes princípios são aplicáveis a organizações privadas.

Aqui vai então:

> Software livre dá a todos a oportunidade de indivíduos, empresas, organizações e administração pública o direito de usar, partilhar e melhorar o software.

Vamos então aqui discutir alguns aspetos da software livre na sua aplicação à administração pública:

* Eficiência
* Valor cívico
* Soberania tecnológica
* Segurança
* Inovação
* Colaboração
* Interoperabilidade
* Promoção da iniciativa privada

## Eficiência

O caro leitor já olhou para o texto do caderno de encargos de um concurso público para desenvolvimento de um sistema de informação? Se não, deveria. Regra geral (para a qual espero que existam exemplos contrários), um concurso está pejado de tendências e vieses. Geralmente o caderno de encargos não se limita a listar uma série de requisitos funcionais do género: tem de permitir aos utilizadores do género X fazer Y. Vão mais longe e muitas vezes forçam determinadas arquiteturas: a utilização de um determinado software de gestão de base de dados, um determinado sistema operativo, uma determinada solução (geralmente proprietária) e outras diretivas que em pouco ou nada contribuem (antes pelo contrário) para resolver o problema em questão e a entrega de um sistema útil.

![Eficiência](marc-olivier-jodoin-NqOInJ-ttqM-unsplash.jpg)

*Photo by Marc-Olivier Jodoin on Unsplash*

É verdade que o software não existe no limbo, isolado do resto da realidade dos sistemas de informação da instituição que está a promover o projeto, mas até que ponto isto é eficiente e conduzirá à melhor forma de gastar o dinheiro dos contribuintes?

Muitas vezes (a maioria até!), sistemas semelhantes já existem e foram desenvolvidos noutras partes do país ou do mundo. Qual é a probabilidade de o sistema de informação de licenciamentos de uma câmara municipal necessitar de ser diferente do mesmo sistema em outra câmara? Qual é a probabilidade do sistema de informação hospitalar necessitar de ser diferente de outro sistema de informação hospitalar? Qual é a probabilidade da plataforma utilizada para desenvolver a interface web de self-service de um serviço necessitar de ser diferente da de outro serviço?

Porque razão deverá o estado financiar uma série de projetos de software que fornecem serviços semelhantes, quando é mais eficiente focar-se em um projeto de cada tipo e partilhar os custos entre instituições?

No fundo o que a administração pública pretende é ser eficaz, fazer o máximo com o mínimo de custo possível, certo?

> Poder reutilizar software pode conduzir a enormes reduções de custo e de risco.

## Valor cívico

Publicar software financiado pelo dinheiro público faz todo o sentido. A administração pública deve investir em bens públicos de forma a maximizar o benefício para a sociedade.

> O dinheiro investido no desenvolvimento de software pode ser devolvido aos cidadãos através da publicação do código fonte e de uma licença de utilização livre.

![Civismo](liam-mckay-VHWyqXsWHg0-unsplash.jpg)

## Soberania tecnológica

Imaginemos que uma câmara municipal vai investir na criação de infra-estruturas para uma nova zona da cidade, que neste momento é um terreno deserto. Para isso vai precisar de empresas de construção que lhes construam as infra-estruturas.

Agora imaginem que, depois de finalizado o processo de contratação pública, atribuído no fim a uma empresa, o contrato diz que, uma vez construídas as infra-estruturas, somente a dita empresa de construção tem o direito de manter e alterar esta infra-estrutura. Com a excepção desta dita empresa, nanhuma outra entidade - nem a mando do próprio estado — tem direito a alterar, melhorar ou a corrigir um problema que venha a surgir. Nem mesmo é dado o direito de olhar para estas infra-estruturas, que são proopriedade intelectual da empresa.

Absurdo, não?

Pois é o que geralmente acontece com contratos de desenvolvimento e manutenção de sistemas de informação.

Como é que o software livre pode aqui ajudar? Dada a natureza liberal imposta à partida para a publicação e utilização do código, qualquer empresa poderá concorrer — desde que minimamente qualificada — a prestar serviços de desenvolvimento e manutenção deste sistema.

E mais: qualquer cidadão deverá poder consultar, apontar problemas e sugerir alterações ao código fonte (tal como a comunidade open-source faz há décadas).

No caso de um problema no software, e se um vendedor não for responsável por resolvê-lo, a instituição pode contratar qualquer outra empresa para fazê-lo se o software for livre. A velocidade e a capacidade para resolver um problema pode ser ainda mais importante se este problema for de segurança: quanto mais depressa for resolvido, menor o tempo de exposição a utilização potencialmente abusiva.

![Eficiência](headway-5QgIuuBxKwM-unsplash.jpg)

*Photo by Headway on Unsplash*

## Interoperabilidade

Ao utilizar software livre, com a ajuda da utilização de standards abertos, estamos também a promover a utilização e desenvolvimento de sistemas que são inter-operáveis. Dois sistemas diferentes que utilizem o mesmo standard aberto, poderão facilmente comunicar entre si, o que reduz muito o custo de integração.

No fundo, mais uma vez, o que a administração pública pretende é ser eficaz, fazer o máximo com o mínimo de custo possível, certo?

> Utilizando software livre e standards abertos, estamos a maximizar a transferibilidade, a interoperabilidade e a acessibilidade do código-fonte. Estamos também a remover a dependência de um qualquer fornecedor.

## Segurança

O código aberto é visto muitas vezes como um impedimento à segurança. Afinal de contas, se os atacantes podem ver o código fonte, eles podem mais facilmente descobrir vulnerabilidades, não é? Acontece que é exatamente ao contrário.

Segurança por obscuridade é um princípio muito falível. A obscuridade funciona até a vulnerabilidade ser descoberta.

A segurança por obscuridade muitas vezes é comparada com o plantar o dinheiro debaixo de uma árvore. Só funciona porque ninguém sabe que está lá. Muito melhor será colocar o dinheiro num cofre forte.

Vejamos o caso do sistema operativo Linux. A segurança de uma aplicação assenta na segurança do sistemas operativo e de todos os serviços que são construídos neste. Ao publicar o código fonte, o Linux garante que temos milhares de olhos permanentemente a escrutinar o código e novas alterações a este à procura de vulnerabilidades. O fato do código ser aberto dá mais segurança, não menos.

> Código aberto é código auditável.

![Segurança](matthew-henry-fPxOowbR6ls-unsplash.jpg)

*Photo by Matthew Henry on Unsplash*

# Colaboração e Inovação

O motivo não é ideológico, é organizacional: o Software Livre ajuda a combinar várias tecnologias e conhecimentos de fornecedores independentes, torna a cooperação complexa sem atrito, aprimorando a confiança e reduzindo as despesas gerais de coordenação, além de reduzir as barreiras legais e económicas.

Vejam os exemplos dos projetos e das comunidades à volta de websites como o Github, onde empresas de ponta: Google, Microsoft, Facebooke e muitos outros colaboram e publicam código livre.

> A inovação moderna é complexa, colaborativa e de código aberto.

## A iniciativa privada

A utilização de uma peça de software necessita de muito mais esforço do que simplesmente correr o código. Um sistema de informação necessita de planeamento, integração, customização, migração de dados, formação, suporte, etc. Logo, publicar código como software aberto não prejudica a iniciativa privada nem compete com o sector privado, mas vai sim criar novas oportunidades na procura de serviços comerciais à volta do software livre.

Em vez de criarmos sistemas que tendem a tornar-se monopólios, abrimos o mercado a qualquer empresa com capacidade para concorrer.

## O que mudar na procuração

Isto é tudo muito bonito e ideal, mas o que se poderá fazer para aumentar a adopção do software livre na administração pública?

Para começar, era importante requerer que administrações públicas tenham de justificar formalmente a compra de software proprietário se existe uma alternativa livre.

Nos atuais cadernos de encargos, é dado um grande foco na obtenção de licenças. Com o software livre, o foco passa a ficar na prestação de serviços de desenvolvimento e manutenção. Por isso, na elaboração do caderno de encargos, é importante que se procure soluções, e não licenças.

Na avaliação dos cadernos de encargos, é importante atribuir mais peso nos pontos fortes do software livre. De forma a prevenir situações de impasse e aumentar a longevidade destes sistemas, deverá ser premiado a interoperabilidade, a utilização de standards abertos e a independência de fornecedor.

## Resumindo

O que a administração pública pretende é ser eficaz, fazer o máximo com o mínimo de custo possível. Utilizando software livre e standards abertos, estamos a maximizar a transferibilidade, a interoperabilidade e a acessibilidade do código-fonte. Estamos também a remover a dependência de um qualquer fornecedor, a fomentar a iniciativa privada e a prevenir a criação de monopólios e situações de impasse e extorsão. Estamos também a aumentar a segurança e a auditabilidade do código fonte.

Acima de tudo estamos a maximizar o valor criado ao promover a reutilização e a partilha de recursos, envolvendo o cidadão e abrindo uma maior participação do sector privada, com vista a tornar a nossa administração pública mais eficaz.

![Freedom](sharosh-rajasekher-T7s_TnKO-dk-unsplash.jpg)

*Photo by Sharosh Rajasekher on Unsplash*

## Links relacionados

* [Public Money Public Code - Free Software Foundation Europe](https://publiccode.eu/pt/)
* [ANSOL - Associação Nacional para o Software Livre](https://ansol.org/)
* [Associações exigem ao Governo software livre na administração pública](https://visao.sapo.pt/exameinformatica/noticias-ei/mercados/2017-09-14-associacoes-exigem-ao-governo-software-livre-na-administracao-publica/)
* [O Software Livre e de Código Aberto na Administração Pública - Dos mitos às questões de natureza legal, ética e de optimização de recursos públicos](https://estudogeral.sib.uc.pt/handle/10316/30768)

## Casos de sucesso

* Hungria 2016: reduzir inciso de software proprietário na administração pública em 60% até 2020.
* Helsínquia  2015: adoptou uma estratégia de IT que dá ênfase à utilização preferência de software livre.
* Barcelona 2017: a cidade anunciou que software financiado pelo estado deveria ter uma licença de software livre.
* Outubro 2017: 32 países da EFTA e UE assinaram a declaração de Tallin, onde pediram à comissão europeia para reforçar a utilização de software livre e standards abertos, especialmente quando financiado pela UE.

E muitos outros!

