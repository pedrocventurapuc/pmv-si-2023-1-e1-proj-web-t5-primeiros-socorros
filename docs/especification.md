# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto


# Personas #
![Marcela](https://user-images.githubusercontent.com/105678089/227229206-ac278df8-31ff-4b79-a1c8-832d43d139fd.png)

![tião](https://user-images.githubusercontent.com/105678089/227229237-4ac7e7b2-2179-42df-9b20-871e3263ba16.png)

![ana](https://user-images.githubusercontent.com/105678089/227229270-d5ba9715-2c05-432f-a9ae-7078cc3a63b4.png)

![geralda](https://user-images.githubusercontent.com/105678089/227267557-16c94be2-216d-49b6-bbdb-ec922013b6a9.png)

![gloria](https://user-images.githubusercontent.com/105678089/227267593-e325d153-b0bf-4c31-9758-50f1f2cb2a01.png)

![paulo](https://user-images.githubusercontent.com/105678089/227267623-ace1a6fe-9664-43a5-9484-af8cf23b1670.png)

Geralda Pereira, 55 anos, contadora, trabalhando em seu escritório sentiu uma forte dor de cabeça, 
de início súbito. Além disso, sentiu fraqueza e dormência na face e braços afetando um dos lados do corpo.
Preocupada com o estado de Geralda, sua estagiária no escritório procura alguma informação online que possa ajudar. Encontrando um indicador chamado "Escala de Glasgow", verificando os parâmetros de acordo com os sintomas sentidos por Geralda, ligando imediatamente para emergência mais próxima. 
Motivação: diagnóstico precoce para AVC para melhor atendimento e busca rápida de ajuda. Frustação: falta de informação e conhecimento para que pessoas ajudem a diagnosticar e buscar ajuda médica o quanto antes. 

Glória Fernandes, 43 anos, cozinheira em um restaurante no centro de Belo Horizonte, está fazendo suas atividades rotineiras 
antes do horário de abertura do estabelecimento. Como de costume, Glória prepara a panela com água e coloca sob a chama acesa do fogão.
Por um descuido, Glória deixa a panela cair, causando uma grande queimadura em suas pernas e tronco. O gerente do restaurante não sabe como agir, pois 
os "conhecimentos populares" dizem para passar pó de café ou até mesmo pasta de dente nas queimaduras. Assim, o gerente de Glória procura informações sobre 
procedimento para queimadura online.
Motivação: desmistificar as cresças populares sobre tratamento de queimaduras. Frustração: falta de informação e conhecimento podem agravar a situação da queimadura fazendo uso de substâncias indevidas sob a ferida. 


Paulo Tadeu, 35 anos, motorista de aplicativo, estava indo buscar um passageiro em seu veículo. Paulo se assusta ao ver que um rapaz estava na rua deitado no chão desacordado. 
Assim, o motorista estaciona o carro e tenta acordar o rapaz, porém sem sucesso. Paulo não sabe como agir nessa situação. Tenta verificar o pulso e respiração do rapaz. 
Naquele momento um terceiro cidação se aproximou do rapaz desacordado e disse para Paulo que estudou sobre primeiros socorros, sendo assim, ele consegue aplicar as manobras de Ressuscitação Cardiopulmonar (RCP). 
Motivação: ensinar leigos manobras de Ressuscitação Cardiopulmonar (RCP). Frustração: a morte ocorre em minutos, caso a vítima não receba atendimento adequado. 


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

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA |  |
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA | |


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
