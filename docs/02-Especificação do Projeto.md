# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

As partes mais importantes para a solução do problema foi produzida como uma mistura de personas fictícias produzidas pelos membros do grupo e também baseadas em necessidades reais de possíveis usuários.

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na Figuras que se seguem.

Lucas Pereira tem 25 anos, é estudante de TI na UFRN e é estagiário na mesma área na  lojas amaricanas. Gosta de realizar compras na internet e está sempre conectado com as novas tecnologias. Por conta de seu dia corrido acaba não tendo muito tempo lazer. Usa no dia a dia os aplicativos: WhatsApp, Uber e nuBank.

Iury Rodrigues tem 26 anos, é analista de sistemas júnior na TOTVS. Gosta de comprar boas roupas online, cuida da aparência, acorda cedo e aproveita de comidas saudáveis. No seu tempo livre joga no computador, lê livros de economias e técnicas de desenvolvimento. Usa no dia a dia mais frequentemente, os aplicativos como: Telegram, Whatsapp, Banco Inter, Uber, Linkedln.

Cristina Machado tem 35 anos, é gerente no banco Santander. Cristina gosta de beber bons vinhos e passar seu tempo livre com a família. Cristina é bem satisfeita com a vida que tem, mas gostaria de ter um pouco mais de tempo para estudar. Usa com bastante frequência o WhatsApp e Aplicativos bancários.

Roberta Silva tem 28 anos, é engenheira mecânica aeronáutica é formada em engenharia mecânica pela UFMG. Lucas, gosta de produzir músicas nas horas vagas. Suas motivações são sua história e tudo que já percorreu para conquistar o que tem hoje. Usa Instagram, WhatsApp, Aplicativos Bancários, LinkedIn.

José Antônio Pereira da Silva tem 56 anos, desempregado e atualmente é motorista de aplicativo. Se motiva em sua família e sua fé em Deus. Se frustra por não conseguir ser presente no crescimento de seus filhos, por estar desempregado e não ter estudado. Gosta de assistir os jogos do Vasco da Gama, ir aos encontros familiares no domingo e após a empresa onde trabalhava falir, José que não achou espaço no mercado de trabalho, se viu obrigado a pegar o seu carro e trabalhar como motorista de aplicativo para sustentar sua família. Usa com mais frequência os seguintes aplicativos: Instagram, Uber, 99, In Driver.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

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
