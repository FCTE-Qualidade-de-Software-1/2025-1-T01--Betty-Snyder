# Confiabilidade - M4: Percentual de requisitos com critérios de aceitação bem definidos 

## Introdução

Na presente execução da análise de confiabilidade do Agromart, foi definida, durante a [Fase 2](../../gqm/gqm.md#seleção-das-métricas) do projeto, métricas que seriam utilizadas para avaliação do software. Logo, este documento tem como objetivo sintetizar os achados da métrica M4 de confiabilidade do Agromart: Percentual de requisitos com critérios de aceitação bem definidos.


## Referencial teórico 

Para executar a avaliação, é necessário possuir um definição de critérios de aceitação para requisitos. Cabe frizar que a análise foi realizada a partir dos critérios de aceitação das **histórias de usuário**, uma vez que, quando especificados os requisitos na documentação do Agromart, não foram colocados critérios de aceitação.

Segundo Cohn [1], a clareza e satisfação de histórias de usuário tem profunda ligação com adequação de uma aplicação. Dessa forma, podemos compreender também que ao satisfazer histórias de usuário, o software, consequentemente, se torna mais confiável em sua atividade, uma vez que, conclui as atividades de forma correta e satisfatória. 

Sendo assim, é de extrema importância a declaração de critérios de aceitação para histórias de usuário de forma correta. Sendo assim, bons critérios de aceitação devem seguir os seguintes conceitos [1],[2]:

- Clareza e consisão: devem ser escritos em linguagem sinples, sem a uitlização de jargões técnicos e com ambiguidade, para que assim todos os interessados (devs, testers, PO, etc) consigam compreender o que o critério significa;

- Testabilidade: cada critério de aceitação deve poder ser comprovado por um teste específico, dessa forma, é possível cerificar a funcionalidade e cumprimento dos requisitos;

- Resultado: o foco deve ser no resultado esperado do requisito, ou seja, "o quê" está sendo realizado, deixando em aberto como a solução deve ser implementada;

- Independência: cada critério a ser utilizado deve poder ser avaliado isoladamente. Dessa forma, os testes individuais são facilitados e a baixa coesão do software é evidenciada. 

Assim, um conjunto de critérios de aceitação completo é aquele que, para cada história de usuário, define claramente as condições de sucesso de forma testável. Critérios eficazes são: clareza e brevidade, testabilidade objetiva, foco no resultado do usuário e mensuráveis, e idealmente independentes entre si. 


## Análise 

Dessa forma, a avaliação será dada de forma qualitativa, com a análise dos critérios de aceitação disponíveis na documentação do Agromart, em [histórias de usuário](https://agromart.github.io/docs/docs/modelagem/historiaDeUsuario/co-agricultor). 

Os critérios de julgamento e níveis de pontuação da métrica serão utilizados conforme especificados na [Fase 2](../../gqm/gqm.md#níveis-de-pontuação-das-métricas).

### Execução da análise
Na Tabela 1, está presente a análise realizada nos critérios de aceitação de histórias de usuário do Agromart. 

A organização da tabela está feita de acordo com a história de usuário, seguindo das colunas que expressam os conceitos corretos para critérios de aceitação, e por fim, a pontuação para a corretude desses critérios aplicados a história de usuário correspondente.

<table border="1">
  <thead>
    <tr>
      <th>História de Usuário</th>
      <th>Clareza e Concisão</th>
      <th>Testabilidade</th>
      <th>Resultado</th>
      <th>Independência</th>
      <th>Pontuação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01: Realizar Cadastro na CSA</td>
      <td>Sim</td>
      <td>Não</td>
      <td>Sim</td>
      <td>Sim</td>
      <td>3/4</td>
    </tr>
    <tr>
      <td>US02: Realizar Cadastro em outra CSA</td>
      <td>Não</td>
      <td>Não</td>
      <td>Sim</td>
      <td>Não</td>
      <td>1/4</td>
    </tr>
    <tr>
      <td>US03: Realizar login no Agromart</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US04: Baixar o aplicativo no celular</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US05: Acessar uma notificação</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US06: Realizar uma busca</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US07: Sair</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US08: Acesssar página Meus Planos</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US09: Acesssar página Meus Endereços</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
  </tbody>
</table>





## Resultados 
criterios de aceitação com deve sair da sua conta???

criterios de aceitação parecem mais requisitos necessarios para concluir uma tarefa, em casos de uso, como possuir um telefone, ter acesso a internet, isso nao faz sentido para um criterio de aceitação de baixar aplicativo 

incompletas, muito, acessar uma notificação p unico criterio de aceitação é DEVE ESTAR LOGADO? nao faz sentido nenhum. o mesmo para realizar busca, sair, acessar meus endereços, 




## Bibliografia

> \- Documentação de histórias de usuário do AgroMart. Disponível em: <https://agromart.github.io/docs/docs/modelagem/historiaDeUsuario/co-agricultor>. Acesso em: 07 de julho de 2025.

## Referências Bibliográficas

> [1] COHN, M.; BECK, K. User stories applied : for agile software development. Boston Etc.: Addison-Wesley, , Cop, 2004.

> [2] ATLASSIAN. Acceptance Criteria Explained [+ Examples & Tips]. Disponível em: <https://www.atlassian.com/work-management/project-management/acceptance-criteria>. Acesso em: 07 de julho de 2025.



## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/07/2025|Criação do documento| [Júlia Fortunato](https://github.com/julia-fortunato) ||