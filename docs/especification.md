# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto


# Personas #
![Marcela](https://user-images.githubusercontent.com/105678089/227963189-98671a00-9992-4850-9c1a-a124252fdd2e.png)

![tião](https://user-images.githubusercontent.com/105678089/227963241-4fe7a81d-854e-4f86-9a06-bc7d118848f7.png)

![ana](https://user-images.githubusercontent.com/105678089/227229270-d5ba9715-2c05-432f-a9ae-7078cc3a63b4.png)

![geralda](https://user-images.githubusercontent.com/105678089/227267557-16c94be2-216d-49b6-bbdb-ec922013b6a9.png)

![gloria](https://user-images.githubusercontent.com/105678089/227267593-e325d153-b0bf-4c31-9758-50f1f2cb2a01.png)

![paulo](https://user-images.githubusercontent.com/105678089/227267623-ace1a6fe-9664-43a5-9484-af8cf23b1670.png)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|   EU COMO... `PERSONA`    | QUERO/PRECISO ... `FUNCIONALIDADE`                   | PARA ... `MOTIVO/VALOR`                                        |
|---------------------------|------------------------------------------------------|----------------------------------------------------------------|
|Marcela (usuário-cliente)  |Guia prático para casos de crise                      |Conseguir lidar com as crises sozinha                           |
|Marcela (usuário-cliente)  |Orientações factuais sobre a doença                   |Conscientizar acerca de seus perigos e sintomas                 | 
|Tião (usuário-cliente)     |Precisa de um cronograma                              |Organizar sua dieta alimentar e exercícios físicos              |
|Tião (usuário-cliente)     |Forma de registrar e gerenciar o histórico da glicemia|Evitar crises de hipoglicemia                                   |
|Ana (usuário-cliente)      |Localização do hospital mais próximo                  |Já ter mãos um local de emergências e seu status                |
|Ana (usuário-cliente)      |Guia prático sobre como agir em casos emergenciais    |Já ter mãos um local de emergências e seu status                |
|Geralda (usuário-cliente)  |Informativo sobre sintomas de AVC                     |Estar consciente de leves sinais que podem indicar um acidente  |
|Geralda (usuário-cliente)  |Guia prático sobre como agir em casos emergenciais    |Já ter mãos um local de emergências e seu status                |
|Glória (usuário-cliente)   |Guia prático sobre como agir em casos emergenciais    |Saber qual medida tomar em caso de queimaduras                  |
|Glória (usuário-cliente)   |Orientações factuais sobre tratamento de queimaduras  |Conscientizar acerca de seus perigos e sintomas                 |
|Paulo (usuário-cliente)    |Guia prático sobre manobras de RCP                    |Saber qual medida tomar em caso de desmaio                      |
|Paulo (usuário-cliente)    |Localização do hospital mais próximo                  |Já ter mãos um local de emergências e seu status                |


### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA |  |
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA | |
|RF-003| A aplicação deverá visualizar o site em dispositivos móveis| ALTA | |
|RF-004| A aplicação deverá utilizar uma api que conecte o usuário ao google maps| ALTA | |
|RF-005| A aplicação deverá permitir que o usuário acesse o guia de emergência sem ter que fazer login | MÉDIA | |
|RF-006| Para situaçoes de registro a aplicação deverá solicitar o login | MÉDIA | |
|RF-007| A aplicação deve permitir a busca por prestadores de serviços de forma rápida, eficaz e precisa | ALTA | |
|RF-008| A aplicação deve fornecer um guia de primeiros socorros | ALTA | |
|RF-009| A aplicação deve fornecer informações detalhadas e relevantes sobre como prevenir acidentes domésticos | ALTA | |
|RF-010| A aplicação deverá disponibilizar números telefônicos destinados a casos de emergência | ALTA | |

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
|03| A aplicação não substitui atendimento médico          |
|04| Não é possivel agendar consulta médica diretamente no site |



Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
