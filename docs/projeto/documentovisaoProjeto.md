| **Data**   | **Versão** | **Descrição**        | **Autor(es)** |
| ---------- | :--------: | -------------------- | :-----------: |
| 15/09/2021 |    1.0     | Criação do Documento |  Pedro Lima   |

# 1. VISÃO GERAL DO PROJETO

#### 1.1 Organização do Projeto

</br>

| **Papel**     | **Atribuições**                                                                                                                                                                                                                                              | **Responsável** |     **Participantes**      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------- | :------------------------: |
| Desenvolvedor | Implementar os requisitos elicitados, desenvolver as documentações necessárias e escrever testes.                                                                                                                                                            | Pedro Lima      |      Todos da Equipe       |
| Scrum Master  | O Scrum Master é responsável por garantir que a equipe siga os valores do SCRUM, atua também para remover obstáculos à equipe de desenvolvimento. E ainda junto com o PO será responsável pela organização, planejamento e acompanhamento do projeto.        | Victor Buendia  |       Victor Buendia       |
| Product Owner | É a pessoa responsável por maximizar o valor resultante do produto desenvolvido. Sua principal responsabilidade é gerenciar o Product Backlog. E ainda junto com o Scrum Master será responsável pela organização, planejamento e acompanhamento do projeto. | Cibele Freitas  |       Cibele Freitas       |
| DevOps        | Criar e manter a pipeline de integração contínua e implantação contínua.                                                                                                                                                                                     | Brian Pina      | Brian Pina, Cibele Freitas |
| Arquiteto     | É o responsável por liderar e coordenar as atividades e os artefatos técnicos no decorrer do projeto.                                                                                                                                                        | Arthur Matos    |  Brian Pina, Arthur Matos  |

# 2. Ferramentas, Ambiente e Infraestrutura

### 2.1. Hardware

| **Perfil**                 | **Tipo de Hardware** | **Configurações**        | **Qtd. Planejada(es)** | **Prazo Estimado** | **Observação** |
| -------------------------- | :------------------: | ------------------------ | :--------------------: | :----------------: | :------------: |
| Todos os perfis planejados |      Computador      | i5 5ª geração 4GB de Ram |           05           |         -          |       -        |

### 2.1. Software

| **Perfil**                 | **Tipo de Software**                                | **Nome da Ferramenta** | **Versão** | **Qtd Licenças Planejada** | **Prazo Estimado** |
| -------------------------- | --------------------------------------------------- | ---------------------- | :--------: | :------------------------: | :----------------: |
| Todos os perfis planejados | Ferramenta de versionamento de código               | Git                    |  ~ 2.25.1  |             -              |         -          |
| Todos os perfis planejados | Repositório para código e documentação              | GitHub                 |     -      |             -              |         -          |
| Devops                     | Pipeline de CI/CD                                   | GitHub Actions         |     -      |             -              |         -          |
| Todos os perfis planejados | Compartilhamento de arquivos                        | Google Drive           |     -      |             -              |         -          |
| Todos os perfis planejados | Editor de código-fonte                              | Visual Studio Code     |   ~1.58    |             -              |         -          |
| Todos os perfis planejados | Cliente desktop API para Rest e GraphQL             | Postman                |  ~ 8.9.1   |             -              |         -          |
| Todos os perfis planejados | Plataforma de gestão de tarefas                     | Jira                   |     -      |             -              |         -          |
| Todos os perfis planejados | Ferramenta de comunicação do time e envio de avisos | Telegram               |  ~ 2.8.8   |             -              |         -          |
| Todos os perfis planejados | Aplicativo para comunicação síncrona                | Discord                |     -      |             -              |         -          |
| Todos os perfis planejados | Plataforma de quadro branco colaborativo            | Miro                   |     -      |             -              |         -          |
| Todos os perfis planejados | Implementação de virtualização de containers        | Docker                 |     -      |             -              |         -          |
| Todos os perfis planejados | Plataforma de nuvem                                 | Amazon Web Services    |     -      |             -              |         -          |

# 3. Processo de Gerência de Projeto

## 3.1 Processo de Desenvolvimento e Mensuração

### 3.1.1 Metodologia do Projeto

<p>O time optou por adotar uma combinação do Scrum e do XP. Essa decisão foi tomada através da análise de fatores técnicos, organizacionais e humanos.</p>
<p>Olhando para os aspectos humanos, o Scrum e XP são as melhores alternativas de desenvolvimento e trabalho pela experiência que os membros do time têm com essas metodologias com base na experiência adquirida na matéria de Métodos de Desenvolvimento de Software (MDS) e por todos participarem do contexto da Empresa Júnior de Engenharia de Software.</p>
<p>Já observando os aspectos em um viés mais organizacional, outro motivo para essa decisão foi a maneira como a matéria é estruturada em diversas entregas através de um mínimo produto viável (MVP). Essa configuração torna propício o desenvolvimento do produto em ciclos ágeis.</p>
<p>Por fim, traçando o panorama técnico, percebe-se que o projeto possui um escopo grande, por isso a metodologia de construção envolve o uso de MVPs. Nesse sentido, a escolha de Scrum e XP mostra-se mais adequada, para garantir a adaptabilidade do projeto à medida que incrementamos na entrega dos MVPs.</p>
<p>Durante o desenvolvimento do projeto serão realizadas reuniões diárias de 10 minutos no formato proposto pela metodologia Scrum. Também selecionamos o prazo de 7 dias (uma semana) para a Sprint do projeto. Essa escolha se deve por englobar tempo suficiente para o time realizar suas execuções, fechando o ciclo no sábado com retrospectiva e planejamento. Além de permitir que o time valide mais rápido entre si as atividades da sprint e esteja acompanhando o progresso como um grupo, esse período de sete dias está em consonância com o ritmo e volume de entrega das unidades da disciplina, uma vez que precisamos de iterações mais constantes para validações.</p>
<p>No final de cada sprint, que neste projeto corresponde ao tempo de uma semana, é realizada uma reunião de retrospectiva da sprint com duração de 2 horas aos sábados, onde o progresso do time é revisado com base nos gráficos de Fluxo Cumulativo, BurnUp do projeto e Velocidade de Desenvolvimento, incluindo também a análise e gerenciamento de riscos. Além disso, nessa reunião é iniciado o próximo ciclo, onde cada tarefa deve ser estimada dentro do contexto do Planning Poker, usando a sequência de Fibonacci para avaliar a dificuldade de cada atividade a ser concluída.</p>

### 3.1.2 Metodologia de Elicitação de Requisitos

<p>Para dar início ao levantamento de Requisitos, foi fundamental realizar uma análise de qual seria a melhor técnica para essa construção, pensando no cenário do nosso time e no que era preciso para o nosso projeto.</p>
<p>Dentre as formas de elicitação de Requisitos, percebemos que o Brainstorm era a técnica ideal para levantarmos os requisitos de início. Isso porque o Brainstorm conseguiria fazer um levantamento mais rápidos dos requisitos, trazer uma maior diversidade de ideias para o escopo do Studyt e também colocar à prova restrições e características não funcionais do sistema, algo que complementaria a próxima técnica que usamos para documentar os requisitos.</p>
<p>Assim sendo, depois do Brainstorm, o time possuía os Requisitos do projeto e, a partir deles, era preciso uma forma de documentação e detalhamento. Dessa maneira, utilizamos o Workshop de Histórias de Usuário para complementar o Brainstorm, uma vez que o workshop nos permitiria ter uma abordagem através da perspectiva do usuário, possibilitaria uma visão mais clara das interfaces do produto e também ajudaria a ter critérios de aceitação mais claros por conta das histórias de usuário. Além disso, percebemos que ter histórias de usuário possibilitaria perceber o valor de negócio que os requisitos teriam para os clientes.</p>
<p>Nos atributos utilizados nos requisitos, temos a Versão, Dificuldade e Prioridade. A versão segue uma numeração padrão. Já a dificuldade é avaliada através do Planning Poker (com numeração Fibonacci) usado no XP, metodologia adotada no projeto. Por fim, a prioridade foi decidida através da metodologia de priorização MoSCoW, que permite uma análise mais precisa de quais requisitos são importantes para o MVP e para o produto de forma geral.</p>

### 3.1.3

<p>Uma técnica de validação muito importante para a construção do nosso backlog foi o Walkthrough. Essa técnica foi amplamente utilizada pela equipe em vários momentos na validação dos requisitos elicitados — para garantir que os requisitos estavam sendo feitos da maneira correta e desenhando o produto certo. A escolha dessa técnica ocorreu porque ela é mais flexível e simples, uma vez que pode ser feita em reuniões informais e sem preparação do time, tendo por objetivo conseguir a aprovação dos envolvidos para seguir com o projeto.</p>
<p>Outra técnica que utilizamos foi as etapas de inspeção, em geral todos os membros da equipe exerceram todos os papéis, com exceção de escritor, autor e moderador (papéis realizados pelo Scrum Master e PO). No levantamento de ideias todos participaram validando o que foi sugerido e escrito. Não tivemos um papel fixo de coordenador das inspeções, pois avaliamos juntos os processos realizados. Os erros levantados, como uma história desnecessária, foram corrigidos e as sugestões debatidas em equipe se eram ou não válidas, antes de serem partir para a implementação. Escolhemos esse método porque trazia mais agilidade às reuniões e participação e opinião de todos os membros imediatamente, não tendo um tempo de espera além do já ocorrido na reunião. Além de que esse método é mais criterioso e traz uma análise mais aprofundada ao escopo do nosso projeto.</p>

### 3.1.4 Documentação e Gerenciamento

<p>Para efetuar a documentação foi escolhida a elaboração de uma wiki por meio de repositório no github usando o framework docsity como gerenciamento da documentação do projeto. Essa escolha se dá pelo fato do framework permitir a elaboração de documentações de forma organizada em com usabilidade eficiente. Por meio do próprio github é disponibilizada a documentação pelo github pages. O controle de versionamento é feito pelas  tabelas presentes em cada artigo e página da documentação.</p>
<p>No quesito de gerenciamento decidimos usar o Jira, pois é uma ferramenta completa, que possui quadro kanban, backlog, quadros de velocity, burnout e burndown, sendo possível linkar com repositórios do git. Além disso, o Jira é uma ferramenta amplamente utilizada no mercado e seu manuseio poderá trazer grandes aprendizados ao grupo.</p>
