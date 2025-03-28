# Especificações do Projeto

Especificações do Projeto: Aplicativo de Doação de Alimentos
Pré-requisitos: Documentação de Contexto
Este projeto visa desenvolver um aplicativo para facilitar a doação de alimentos entre doadores, ONGs, abrigos e beneficiários, oferecendo uma plataforma simples e eficaz para quem deseja doar ou receber alimentos. O objetivo é solucionar problemas logísticos de distribuição e aumentar o impacto das doações de alimentos para populações carentes.

Técnicas e Ferramentas Utilizadas:

- Diagrama de Personas: Para identificar as necessidades e desejos dos usuários.

- Histórias de Usuários: Para descrever as funcionalidades a partir da perspectiva dos usuários.

- BPMN (Business Process Model and Notation): Para descrever os processos de doação.

- Análise de Situação Atual: Para entender as lacunas existentes na distribuição de alimentos.

## Personas

1- Doador: Maria, 35 anos

Maria é dona de uma pequena padaria e quer ajudar a comunidade local. Ela está interessada em um meio simples e rápido para fazer suas doações de pães e outros alimentos não perecíveis. Maria busca uma plataforma confiável para fazer suas doações de forma direta para ONGs ou abrigos de sua cidade.

2- ONG: João, 42 anos

João coordena uma ONG que oferece alimentação para pessoas em situação de rua. Ele precisa de um aplicativo que centralize as doações recebidas e facilite o gerenciamento das entregas aos beneficiários. A ONG busca otimizar a distribuição de alimentos.

3- Beneficiário: Ana, 27 anos

Ana é moradora de rua e depende das doações de alimentos para sua sobrevivência. Ela precisa de um sistema onde possa localizar rapidamente as ONGs ou abrigos que estão distribuindo alimentos em sua região, com horários e locais definidos.

4- Abrigo: Pedro, 50 anos

Pedro administra um abrigo para famílias em situação de vulnerabilidade social. O abrigo precisa de um aplicativo para gerenciar as doações e as necessidades alimentícias de seus moradores, garantindo que tudo seja distribuído de maneira justa e eficiente.



> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Doador (Maria)	     | Cadastrar minha padaria para doação de alimentos | Ajudar pessoas necessitadas em minha cidade |
|ONG (João)	         | Receber notificações de doações perto de mim     | Organizar e planejar a retirada de alimentos |
|Beneficiário (Ana)	 | Consultar em tempo real as ONGs ou abrigos disponíveis | Saber onde e quando posso obter alimentos |
|Abrigo (Pedro)	     | Gerenciar as doações recebidas de forma eficiente      | Distribuir alimentos aos moradores do abrigo |


Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

|--------------------|------------------------------------|----------------------------------------|
|Contexto 1 | Doador de Alimentos |
|EU COMO |  Doador (Maria) |
|QUERO/PRECISO | Cadastrar minha padaria para doação de alimentos |
|PARA | Ajudar pessoas necessitadas em minha cidade. |

|EU COMO | Doador (Carlos) |
|QUERO/PRECISO | Visualizar o histórico de doações realizadas.|
|PARA | Monitorar o impacto das minhas contribuições.|

|EU COMO Doador (João)
QUERO/PRECISO Receber sugestões de ONGs ou abrigos próximos para onde posso fazer doações.
PARA Facilitar o processo de entrega de alimentos sem perder tempo.

-----------------------------------------------------------------------------------------------------------------
Contexto 2: Organizações Não Governamentais (ONGs)
EU COMO: ONG (João)
QUERO/PRECISO: Receber notificações de doações perto de mim.
PARA: Organizar e planejar a retirada de alimentos de forma eficiente.

EU COMO: ONG (Carla)
QUERO/PRECISO: Gerenciar as doações recebidas, incluindo a quantidade e o tipo de alimento.
PARA: Planejar melhor a distribuição para os beneficiários.

EU COMO: ONG (Lúcia)
QUERO/PRECISO: Consultar a disponibilidade de alimentos em tempo real.
PARA: Organizar rapidamente as entregas e atender as necessidades emergenciais.

------------------------------------------------------------------------------------------------------------------

Contexto 3: Beneficiário de Alimentos
EU COMO: Beneficiário (Ana)
QUERO/PRECISO: Consultar em tempo real as ONGs ou abrigos disponíveis para distribuição de alimentos.
PARA: Saber onde e quando posso obter alimentos de forma rápida e acessível.

EU COMO: Beneficiário (Lucas)
QUERO/PRECISO: Receber notificações sobre as entregas de alimentos nas ONGs ou abrigos próximos a mim.
PARA: Planejar melhor a minha ida aos locais de distribuição e não perder a oportunidade de receber alimentos.

-------------------------------------------------------------------------------------------------------------------
Contexto 4: Abrigo de Alimentos
EU COMO: Abrigo (Pedro)
QUERO/PRECISO: Gerenciar as doações recebidas de forma eficiente.
PARA: Distribuir alimentos aos moradores do abrigo de maneira organizada e sem desperdícios.

EU COMO: Abrigo (Marta)
QUERO/PRECISO: Monitorar a quantidade de alimentos estocados e as necessidades de doações.
PARA: Planejar a reposição de estoque e garantir que nunca faltem alimentos para os moradores.

EU COMO: Abrigo (Fábio)
QUERO/PRECISO: Receber alertas quando o estoque de alimentos estiver baixo.
PARA: Evitar falta de alimentos e garantir que o abrigo esteja sempre abastecido.

--------------------------------------------------------------------------------------------------------------------


> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Atualmente, as doações de alimentos acontecem de forma desorganizada, com poucas ferramentas tecnológicas para gerenciar as doações entre doadores, ONGs, abrigos e beneficiários. As ONGs muitas vezes não sabem onde encontrar doações e os beneficiários têm dificuldade em acessar esses alimentos.

### Descrição Geral da Proposta

O aplicativo será uma plataforma simples que conecta doadores, ONGs, abrigos e beneficiários, facilitando a doação e a recepção de alimentos. As ONGs e abrigos poderão cadastrar suas necessidades, e os doadores poderão oferecer alimentos diretamente através do aplicativo.

### Processo 1 – Cadastro de Doação

- Oportunidade de Melhoria: Automatizar o processo de recebimento de doações para reduzir o tempo entre a doação e a distribuição.
- Modelo BPMN: O doador registra a doação, a ONG ou abrigo localiza a oferta e organiza a retirada.

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – Distribuição de Alimentos

- Oportunidade de Melhoria: Otimizar a logística de distribuição através de notificações automáticas e mapeamento geolocalizado.
- Modelo BPMN: As ONGs recebem as doações e organizam a distribuição, enquanto os beneficiários são informados sobre os horários e locais.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Indicador de Desempenho           /                    Meta                    
Quantidade de doações realizadas   ---   Aumentar em 20% mensal

Tempo de resposta para aceitar uma doação --- Menor que 1 hora

Número de beneficiários atendidos	 --- Aumentar 30% nos próximos 6 meses

Taxa de retenção de usuários	 --- Manter acima de 70%

Nível de satisfação dos usuários	--- Avaliação de 4 ou mais em 5




Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o doador registre alimentos para doação | MÉDIA | 
|RF-002| Permitir a visualização das necessidades de ONGS e Abrigos | MÉDIA |
|RF-003| Agendamento de entregas e retirada | ALTA |
|RF-004| Cadastro de Beneficiários | BAIXA |
|RF-005| Cadastrar Voluntários e Entregadores | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Desempenho: O sistema deve ser capaz de processar até 1.000 transações simultâneas com tempo de resposta inferior a 7 segundos. | MÉDIA | 
|RNF-002| Segurança: O sistema deve garantir a segurança dos dados dos usuários através de autenticação por login e senha. |  ALTA | 
|RNF-003| Usabilidade: A interface deve de fácil navegação, garantindo uma experiência acessível para todos os usuários. O acesso deve ser feito por meio de sites, priorizando clareza e eficiência no design. | MÉDIA | 
|RNF-004| Compatibilidade: O sistema deve ser compatível com as versões mais recentes dos sistemas operacionais iOS e Android, além de navegadores modernos como Chrome, Firefox e Safari. | ALTA | 
|RNF-005| Disponibilidade: O sistema deve garantir uma taxa de disponibilidade de 99,9%, com exceção dos períodos de manutenção programada. | MÉDIA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
