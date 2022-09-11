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
|Dono do negócio  | Gerenciar a agenda de meu estabelecimento | que os clientes possam realizar o agendamento de acordo a disponibilidade real|
|Dono do negócio  | Gerenciar quais serviços o estabelecimento fornece | para que os clientes possam escolher somente os serviços que estão realmente disponíveis |
|Cliente do negócio | Buscar estabelecimentos | Escolher em qual estabelecimento desejo ser atendido |
|Cliente do negócio | Buscar os serviços prestados por cada estabelecimento | Escolher e agendar os serviços desejados|
|Cliente do negócio | Cancelar/Remarcar agendamento | Para que o estabelecimento esteja ciente caso o cliente não consiga comparecer no horário combinado |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre um estabelecimento | ALTA | 
|RF-002| Permitir que o usuário cadastre os serviços prestados pelo seu estabelecimento | ALTA | 
|RF-003| Permitir que o usuário gerencie a agenda de seu estabelecimento | ALTA |

|RF-004| Permitir que o usuário se cadastre como dono de estabelecimento ou cliente | ALTA | 
|RF-005| Permitir que o usuário veja a agenda de um estabelecimento de acordo com um serviço | ALTA | 
|RF-006| Permitir que o usuário realize agendamento de um serviço | ALTA | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| A equipe não pode subcontratar a execução do projeto  |
|03| A aplicação deve seguir o plano pedagógico e educacional da instituição PUC Minas |




## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
