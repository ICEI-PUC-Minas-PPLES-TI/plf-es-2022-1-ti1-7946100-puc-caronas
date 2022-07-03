# Informações do Projeto
`TÍTULO DO PROJETO`  

PUC CARONAS

`CURSO` 

Engenharia de software

## Participantes

- André Calebe
- Bruno Duarte
- Gabriel Amorim
- Lucas de Carvalho
- Vinícius Assis


# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

Infelizmente, carros particulares vêm se tornando cada vez mais inviáveis, tendo em vista o alto investimento inicial necessário para a aquisição de um. Ademais, o valor de veículos cresce cada vez mais assim como o combustível e o seguro. Por outro lado, os aplicativos de transporte não são acessíveis à grande maioria da população, especialmente pelo fator limitador financeiro. Nesse viés, muitos têm como alternativa principal o transporte público: ônibus ou metrô, o resultado é sempre o mesmo. Desconforto e falta de segurança estão presentes diariamente na vida de milhares de brasileiros.

## Objetivos


O projeto tem como foco conectar estudantes com necessidades complementares. Assim, alunos que utilizam veículos particulares para se locomover à faculdade ofereceriam carona a alunos interessados, que muitas das vezes dependem atualmente de transportes ineficientes. A operação seria realizada por meio da cobrança de uma tarifa de um valor simbólico, próximo a uma passagem de ônibus, para contribuir com o pagamento do combustível. Por fim, a acessibilidade do projeto é de suma importância, tendo em mente que ele visa ajudar ao máximo de pessoas possível dentro do ambiente universitário.

## Justificativa

A justificativa do projeto reside em um novo modo de juntar os dois mundos: a cooperação entre alunos com e sem carro. Dessa forma, segundo pesquisa efetuada entre estudantes da faculdade, cerca de 80% dos alunos estariam dispostos a utilizar da plataforma idealizada no projeto como meio de transporte universitário principal. Além disso, as vans e o carro particular dominam as estatísticas de meio de transporte em 70%, criando um leque de oportunidades para a união entre os dois âmbitos, e com um custo acessível a todos. A ideia da inovação da locomoção para estudantes surgiu tendo a necessidade dos alunos em vista: gastar pouco no traslado diário. Após idealização e pesquisa, foi constatado que ambos os lados dos agentes principais para a efetivação do projeto poderiam ser beneficiados, cada um em sua maneira.

## Público-Alvo

O público alvo contempla a grande maioria dos estudantes das unidades da PUC, de forma independente da faixa etária. Nesse viés, alunos com carro poderão utilizar o aplicativo de forma eficiente, tendo um auxílio financeiro; assim como aqueles sem carro particular, que terão como vantagem utilizar a carona em detrimento do transporte anterior.
 
# Especificações do Projeto

## Personas e Mapas de Empatia

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/persona1.jpg?raw=true)
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/persona2.jpg?raw=true)
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/persona3.jpg?raw=true)


## Histórias de Usuários

1.	EU, COMO pessoa que vai dar a carona, QUERO uma tela para cadastrar as minhas informações que são necessárias, outra tela para visualizar as possíveis pessoas que eu poderia dar carona com base na minha rota, podendo ser mostrada a rota da pessoa ou não, e um chat para entrar em contato com a pessoa, PARA QUE eu possa combinar com a pessoa que precisa de carona qual vai ser o nosso acordo de carona. 

2.	EU, COMO pessoa que precisa de carona, QUERO uma tela para cadastrar as minhas informações que são necessárias, outra tela para visualizar as possíveis pessoas que me dariam carona com base na minha rota, podendo ser mostrada a rota da pessoa ou não, e um chat para entrar em contato com a pessoa, PARA QUE eu possa combinar com a pessoa que possivelmente me daria carona qual vai ser o nosso acordo de carona. 


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

- O programa deve conter uma tela para o cadastro completo tanto de quem dá a carona e de quem recebe. Essa tela deve conter formulários para o preenchimento das informações de cada indivíduo, contendo seu nome, idade, curso que faz, rota utilizada, valor gasto em seu deslocamento. No final para que o formulário seja enviado, o usuário deve concordar com os termos de uso e políticas do aplicativo/programa. PRIORIDADE: ALTA


- Logo após o cadastro deve haver uma tela de login para o usuário acessar uma tela com uma API de mapas da Google, que calcula rotas. PRIORIDADE: MEDIA 
 
- Após o usuário inserir sua localização, seu destino e sua rota ser calculada, deve aparecer uma tela com as rotas e necessidades de cada usuário, com base no seu cadastro (Caso seja cadastrado como quem vai dar a carona, deve aparecer pessoas que precisam de carona; e caso seja cadastrado como quem precisa de carona deve aparecer quem está dando carona). PRIORIDADE: ALTA 


- Caso o usuário clique em alguma pessoa, deve aparecer as informações pertinentes para que as pessoas se comuniquem e saibam qual a rota e destino de cada uma, e um chat para elas se comunicarem.  PRIORIDADE: ALTA



### Requisitos não Funcionais

- O programa deve ser escrito na linguagem C# utilizando o MySql de banco de dados para computador, e Kotlin e Swift para IOS e Android utilizando MongoDB de banco de dados  PRIORIDADE: MEDIA 

- O aplicativo/programa deve ser multiplataforma, sendo IOS, Android e Windows, MAC e WEB.  PRIORIDADE: MEDIA

- O sistema deve respeitar o tempo máximo de 120 segundos durante processamentos.  PRIORIDADE: ALTA



## Restrições

-	O projeto será executado paralelamente às outras atividades universitárias, visto que inicialmente unicamente é só um trabalho universitário. 

-	O projeto não tem orçamento inicial previsto. 

-	O projeto completo deve ser entregue ao final do semestre, não necessariamente operando, mas funcionando para fins avaliativos. 

-	Caso algum integrante saia do projeto durante o seu desenvolvimento, deve-se imediatamente procurar outro para substituir, visto que o projeto é algo que DEVE ser concluído. 



# Projeto de Interface

Nós desenvolvemos uma interface amigável, e de fácil uso, tendo em vista que acessibilidade é essencial para o sucesso do nosso projeto. São cinco telas principais durante o uso da aplicação que envolvem cadastro, login, rotas e contato.

## User Flow

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/fluxo1.jpg?raw=true)
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/fluxo2.jpg?raw=true)
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/fluxo3.jpg?raw=true)

## Wireframes

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/wireframe.png?raw=true)
O wireframe mostra, de forma pouco detalhada, como o aplicativo funcionaria. Assim, logo na tela inicial haveria um mapa do Google, assim como telas de cadastro de informações, rotas e vagas.

# Metodologia

A metodologia adotada pelo grupo foi o scrum. Criamos sprints internos para as partes que foram designadas para cada um (num intervalo de 3 dias) e discutíamos o próximo sprint tendo em base o que faltava ser feito. Além disso, houveram conversas diárias entre o grupo e com pontenciais clientes, abordando tópicos relacionados ao projeto. Por fim, fizemos backlog do produto e, a partir de seus resultados, montamos o backlog do sprint, dividindo também as tarefas.

Utilizamos o Trello para a efetivação do KanBan, mantendo controle sobre o que faltava ser feito e quem o estava fazendo. Seguem o link do quadro controle de tarefas e o print do mesmo:
https://trello.com/b/5SyInRQi/tiaw-puc-caronas
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/KanBan.png?raw=true)

## Divisão de Papéis

-André: formulários, projeto de Interface, ambiente GitHub, ambiente FIGMA
-Bruno: contexto do projeto, entrevistas qualitativas, design thinking, apresentação Power Point, personas
-Gabriel: Especificação do projeto, personas
-Lucas: contexto do projeto, quadro controle de tarefas (KanBan), personas
-Vinicius: Metodologia, design thinking, ambiente MIRO

As tarefas foram divididas com base no modelo scrum.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinking  | Miro |  https://miro.com/app/board/uXjVOA3AAhM=/ | 
|Repositório de código | GitHub | https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas | 
|Protótipo Interativo |  Figma | https://www.figma.com/file/HE4KyhmiBYZsDRFpOxQHd8/Untitled?node-id=0%3A1| 
|KanBan |  Trello | https://trello.com/b/5SyInRQi/tiaw-puc-caronas| 


- Editor de código: Visual Studio Code
- Ferramentas de comunicação: Discord e Whatsapp 

Escolhemos o vs code, tendo em vista que ele é o mais utilizado, mais versátil, e ja tínhamos conhecimento dele. 
As ferramentas de comunicação utilizadas possuem integração semelhante e todos do grupo já utilizam com frequência, facilitando a comunicação interna. 

## Controle de Versão

A ferramenta para controle de versão que escolhemos foi o próprio GitHub, que é a mais utilizada e com o uso mais fácil com o GitHub Desktop. A ferramenta do Git também foi fundamental para o controle de versão. Foi criada uma branch master e a branch  feature/new-version, para que fosse possível implementar funcionalidades novas durante o desenvolvimento sem que perdêssemos os dados anteriores. Após devidamente testadas e confirmadas funcionais, as novidades eram passadas novamente para a branch master.

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

O site Puc Caronas é uma ferramenta que visa a conexão dos alunos para melhor locomoção comum. Dessa forma, os usuários conseguem se relacionar por meio de pedidos e ofertas de caronas, informando para onde pretende ir, o horário de encontro e as informações de contato. O fim é o bem comum: maior conforto e segurança, por menor preço, para ambas as partes.

## Tecnologias Utilizadas

Para trazer o projeto à vida, foi utilizado uma estrutura HTML (com estilização CSS), assim como arquivos JavaScript. Dessa maneira, os arquivos JS contam com:
- Leitura e edição de campos de formulário (CRUD)
- Cadastro e Login, assim como a validação de login em cada tela
- Dados enviados e puxados do local storage

Além disso, a API de mapa do "Leaflet"[Ref. 1] está presente na tela principal (home) do site, trazendo a localização do usuário e das unidades da Puc Minas, para que ele se oriente nos pontos de encontro combinados. O framework Bootstrap também foi utilizado durante algumas fases da programação, mas para o envio final, foi retirado e o CSS foi repensado a fim de chegar ao melhor resultado visual ao usuário.
No quesito prático da programação, o Visual Studio Code foi utilizado por cada um dos integrantes do grupo, além do GitHub para o salvamento de arquivos na nuvem e compartilhamento entre os integrantes do grupo, assim como o Git, para a clonagem de repositórios e controle de versão. O Discord e o Whatsapp também foram ferramentas essenciais para a comunicação interna, fazendo reuniões e organizando o Trello, mantendo sempre o controle de tarefas.

**Quadro KanBan**
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/kanban.png?raw=true)
<br/>
<br/>

**Diagrama de User Flow**
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/UserFlow.jpg?raw=true)
Fonte: https://miro.com/app/board/uXjVOoxRS6A=/?share_link_id=985483267908<br/>
<br/>

**Diagrama StoryBoard**
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/StoryBoard.jpg?raw=true)
Fonte: https://miro.com/app/board/uXjVOo2O214=/?share_link_id=639302987553<br/>
<br/>

**Tecnologias utilizadas**
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/TECNOLOGIAS.jpg?raw=true) <br/>
Fonte: https://miro.com/app/board/uXjVOo1Ts-M=/?share_link_id=35820572290 <br/>
<br/>

**Protótipos de tela**
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/1login.png?raw=true)
Tela para o usuário acessar o software, com cadastro previamente realizado.<br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/2cadastro.png?raw=true)
Caso o usuário não tenha já efetuado o cadastro, há a tela para que ele preencha pela primeira vez com suas informações pessoais antes de fazer uso do website. <br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/3home.png?raw=true)
Após efetuar o cadastro/login, o usuário é redirecionado para a Home Screen do website, já com a API de mapa implementada, pedindo a sua localização, e mostrando a localização da PUC.<br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/5liberacao-de-uso.png?raw=true)
Na aba Perfil, é necessário completar o cadastro com as informações básicas para usar o website, sendo possível também voltar nessa tela futuramente para alterar os dados do perfil, deslogar, ou excluir seu perfil completamente.<br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/16-caronas-pegar.png?raw=true)
Ao clicar na seção _Caronas_ o usuário consegue ver as caronas cadastradas no aplicativo, incluindo as que ele mesmo postou e os posts de outros usuários. Caso ele deseje, sempre é possível adicionar novos posts de caronas. Além disso, os posts que ele fez têm direto nessa tela a opção de edição e exclusão, para que a informação esteja sempre atualizada e correta para o usuário.<br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/8criacao-de-caronas.png?raw=true)
Por meio de um formulário rápido de preencher e de acessar, é possível adicionar um post de carona, seja pedindo ou oferecendo-a. Ao clicar em editar carona, o usuário é redirecionado para esse mesmo formulário, já preenchido com as informações cadastradas anteriormente, tendo o poder de alterar e salvá-las<br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/11detalhes-caronas.png?raw=true)
A seção de detalhes de um post de carona feito pelo próprio usuário, contêm os botões de edição e exclusão, além das informações básicas da postagem. Informações de passageiros e/ou condutores também podem estar presentes<br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/12caronas-user2.png?raw=true)
A seção de detalhes de um post de carona feito por outro usuário, em vez dos botões de edição e exlucsão e as informações de passageiros/condutores, conta com um botão _Pegar Carona_, que pode ser clicado para sinalizar sua presença ao dono da postagem original.<br/>
<br/>

![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/13solicitacoes2.png?raw=true)
Por fim, a tela de solicitações contém uma lista de usuários que pressionaram o botão _Pegar Carona_, explicitado na imagem anterior; e dá a opção do usuário de aceitar ou recusar a solicitação de carona feita.<br/>
<br/>

## Arquitetura da solução

**Diagrama de arquitetura:**
![image](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7946100-puc-caronas/blob/master/docs/relatorio/images/Flowchart.jpg?raw=true)
Fonte:https://miro.com/app/board/uXjVOo2RlDY=/?share_link_id=811741050563<br/>
A funcionalidade do serviço é pautada toda no LocalStorage. Nesse contexto, os fomulários necessários para a utilização do website salvam os valores em formato de array no tal armazenamento local (tanto dados do perfil quanto os dados de um post); sendo possível a recuperação dos dados a qualquer momento. A vantagem de salvar em array é a possibilidade de edição posterior, em que o usuário é redirecionado para a mesma página, porém com os valores recuperados do Local Storage do navegador, identificados por meio do índice do post no array. Além disso, a exclusão é feita da mesma maneira, o sistema identifica a posição do array do post que será deletado e faz a modificação. A interação entre os próprios usuários, na promessa e justificativa da pertinência do Puc Caronas., é feita por meio do ID do user, sendo possível distinguir quais posts foram feitos por ele e quais foram feitos por outros usuários, de maneira que ele consegue enviar a solicitação para a vaga postada por outro aluno, por exemplo. Este outro aluno recebe as informações do usuário por meio do request feito ao local storage, que devolve o nome do aluno, assim como informações importantes no geral.<br/>
<br/>

# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
