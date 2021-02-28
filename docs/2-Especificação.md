# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>


## Personas

Persona 1: Silva Dias tem 32 anos e é membro da comunidade região norte de BH. Supervisor de estoque em um supermercado na zona central da cidade, está sempre realizando diferentes atividades em sua rotina de trabalho. Ele passa por diversas situações turbulentas em seu dia a dia, o que se agravou  com a pandemia do novo coronavírus, e gostaria de se inscrever para receber o tratamento psicológico gratuito na ONG presente em sua comunidade.

Persona 2: Ana Paula Catelli tem 29 anos, é formada em Psicologia. Solteira e apaixonada por serviços voluntários, recentemente realizou seu sonho de atuar em uma ONG que presta atendimentos psicológicos gratuitos à comunidade, e gostaria de algo que auxiliasse em sua organização com os horários dos pacientes e que gere um prontuário do atendimento realizado.

Persona 3: Juliana Medeiros tem 31 anos, é estudante de Direito e atua como secretária em uma ONG para conseguir pagar seus estudos. Casada e mãe de um filho, nunca colocou limites em seus sonhos e sempre acreditou que nunca é tarde para conquistar um diploma. Após concluir a graduação, pretende abrir um escritório próprio de advocacia. Suas atividades exercidas necessitam de uma ferramenta que auxilie na marcação de consultas dos pacientes, assim como manejo nos horários deles.


## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO... | QUERO/PRECISO ...  |PARA ...                  |
|--------------------|------------------------------------|----------------------------------------|
|Membro da Comunidade | Me inscrever no sistema da ONG, informando nome, email, telefone, senha para login         | Se aprovado na triagem, receber atendimento psicológico gratuito              |
|Membro da Comunidade | Visualizar datas disponíveis no calendário         | Selecionar uma data de interesse para consulta       |
|Membro da Comunidade | Ser capaz de cancelar ou alterar a data de um agendamento de consulta     | Não prejudicar a ONG, caso ocorra um imprevisto              |
|Profissional de Psicologia | Me inscrever no sistema da ONG informando nome, e-mail, telefone e senha , número inscrição CFR    | Ser incluído no grupo de profissionais que prestam serviço na ONG |
|Profissional de Psicologia | Gerar prontuários no sistema               |Armazenar dados históricos dos atendimentos para controle e gestão|
|Secretária | Me inscrever no sistema da ONG, informando nome, email, telefone e senha              | Gerir a marcação de consultas dos pacientes |
|Secretária | Visualizar o cadastro dos membros inscritos no sistema   | Avaliar os dados dos membros, no processo de triagem, a fim de verificar se estão aptos ao atendimento gratuito na ONG|
|Secretária | Visualizar os membros liberados para receber atendimento  | Associar um membro ao Profissional de Psicologia |
|Secretária | Criar os agendamentos psicológicos, associando os paciente/cliente com o Profissional de Psicologia que fará o atendimento  | Preencher a agenda de atendimento da semana |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RF-001| O sistema deve permitir os usuários do tipo Psicólogo, Membro da comunidade ou Secretária, se cadastrarem no  sistema, informando Nome, Email, Senha e, no caso dos  profissionais de psicologia, número inscrição CFR.| ALTA |  
|RF-002| O sistema deve permitir que os usuários façam login no sistema através do seu e-mail e senha  | ALTA |
|RF-003| O sistema deve permitir o Membro da Comunidade se inscrever para triagem para que seja verificado se ele atende os pré requisitos para atendimento gratuito na ONG| MÉDIA |
|RF-004| O sistema deve permitir que o Membro da Comunidade selecione uma data para atendimento psicológico, após ser aprovado na triagem  | ALTA |
|RF-005| O sistema deve permitir que o Membro da Comunidade realize o cancelamento de uma consulta | ALTA|
|RF-006| O sistema deve permitir que o Membro da Comunidade realize a mudança de data de uma consulta agendada | ALTA|
|RF-007| O sistema deve permitir que o Profissional de Psicologia adicione informações do paciente em seu prontuário, após cada consulta | ALTA |
|RF-008| O sistema deve permitir que a Secretária visualize membros da comunidade inscritos no sistema e aprovados na triagem, para associá-los a um Profissional de Psicologia | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser responsivo para rodar em um dispositivos móveis | MÉDIA | 
|RNF-002| As notificações de confirmação do agendamento de consulta, devem ser enviadas em forma de push ou email, conforme previamente configurado pelo usuário  | BAIXA | 
|RNF-003| As datas disponíveis para agendamento de consultas, devem ser exibidas em uma interface de calendário, semelhante aos eventos do Google Agenda. | BAIXA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| O projeto deverá ser testado pelo usuário antes de entrar em efetivo funcionamento  |
