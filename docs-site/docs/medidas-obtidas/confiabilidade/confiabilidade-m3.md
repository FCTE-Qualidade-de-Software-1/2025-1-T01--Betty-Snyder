# Confiabilidade - M3: Percentual de requisitos com critérios de aceitação bem definidos 

## Introdução

Na presente execução da análise de confiabilidade do Agromart, foi definida, durante a [Fase 2](../../gqm/gqm.md#seleção-das-métricas) do projeto, métricas que seriam utilizadas para avaliação do software. Logo, este documento tem como objetivo sintetizar os achados da métrica M3 de confiabilidade do Agromart: Percentual de requisitos com critérios de aceitação bem definidos.


## Referencial teórico 

Para executar a avaliação, é necessário possuir um definição de critérios de aceitação para requisitos. Cabe frizar que a análise foi realizada a partir dos critérios de aceitação das **histórias de usuário**, uma vez que, quando especificados os requisitos na documentação do Agromart, não foram colocados critérios de aceitação.

Segundo Cohn <sup>[1]</sup>, a clareza e satisfação de histórias de usuário tem profunda ligação com adequação de uma aplicação. Dessa forma, podemos compreender também que ao satisfazer histórias de usuário, o software, consequentemente, se torna mais confiável em sua atividade, uma vez que, conclui as atividades de forma correta e satisfatória. 

Sendo assim, é de extrema importância a declaração de critérios de aceitação para histórias de usuário de forma correta. Sendo assim, bons critérios de aceitação devem seguir os seguintes conceitos <sup>[1]</sup><sup>[2]</sup>:

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

<font size="3"><p style="text-align: center">Tabela 1 – Avaliação e pontuação dos critérios de aceitação das histórias de usuário do Agromart</p></font>
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
    <tr>
      <td>US10: Acessar página das lojas da CSA cadastradas</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US11: Acessar histórico de compras</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US12: Adicionar ao carrinho</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US13: Comprar cesta</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US14: Comprar produto</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US15: Comprar planos</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US16: Realizar login no Strapi</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US17: Realizar login no Aplicativo</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US18: Possuir um tutorial</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US19: Interagir com Produtos</td>
      <td>Sim</td>
      <td>Sim</td>
      <td>Não</td>
      <td>Sim</td>
      <td>3/4</td>
    </tr>
    <tr>
      <td>US20: Interagir com Planos</td>
      <td>Sim</td>
      <td>Sim</td>
      <td>Não</td>
      <td>Sim</td>
      <td>3/4</td>
    </tr>
    <tr>
      <td>US21: Interagir com Cestas</td>
      <td>Sim</td>
      <td>Sim</td>
      <td>Não</td>
      <td>Sim</td>
      <td>3/4</td>
    </tr>
    <tr>
      <td>US22: Interagir com um Co-agricultor</td>
      <td>Sim</td>
      <td>Sim</td>
      <td>Não</td>
      <td>Sim</td>
      <td>3/4</td>
    </tr>
    <tr>
      <td>US23: Interagir com Lojas</td>
      <td>Sim</td>
      <td>Sim</td>
      <td>Não</td>
      <td>Sim</td>
      <td>3/4</td>
    </tr>
    <tr>
      <td>US24: Criar notificações</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US25: Interagir com Pedidos</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
    <tr>
      <td>US26: Visualizar endereços</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>Não</td>
      <td>0/4</td>
    </tr>
  </tbody>
</table>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>


## Resultados 

Ao realizar a análise, observou-se que grande parte das histórias não apresentam critérios de aceitação que atendam minimamente essas qualidades. Em muitos casos, os critérios estavam ausentes, eram ambíguos ou expressavam condições que mais se aproximam de pré-requisitos para uso (como "possuir acesso à internet", "ter o código da CSA") do que de critérios de aceitação propriamente ditos.

Além disso, notou-se o uso de termos vagos ou técnicos demais, como em "deve conversar com o administrador para estabelecer a forma de pagamento" — o que pode gerar confusão: trata-se de uma interação com o sistema ou com uma pessoa real? Tal fato compromete diretamente a clareza e a testabilidade.

Também foram identificados critérios como "deve estar logado", utilizados de forma repetida e isolada para funcionalidades diversas (como acessar notificações, histórico de compras, etc.), sem detalhar o fluxo ou o comportamento esperado da funcionalidade.

Dessa forma, a Tabela 2 apresenta um panorama quantitativo das pontuações atribuídas aos critérios de aceitação das histórias de usuário avaliadas, evidenciando a necessidade de revisão e aprimoramento desses elementos para garantir maior qualidade e confiabilidade na especificação dos requisitos, uma vez que, cerca de **73%** dos critérios de aceitação não pontuaram na avaliação, sendo assim o nível de pontuação da métrica marcado como **insatisfatório**.


<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 2 – Distribuição de histórias de usuário por pontuação dos critérios de aceitação</b></p>
  </font>

  <table border="1" style="margin: 0 auto;">
    <thead>
      <tr>
        <th>Pontuação</th>
        <th>Quantidade</th>
        <th>Porcentagem</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>0/4</td>
        <td>19</td>
        <td>73,08%</td>
      </tr>
      <tr>
        <td>1/4</td>
        <td>1</td>
        <td>3,85%</td>
      </tr>
      <tr>
        <td>2/4</td>
        <td>0</td>
        <td>0,00%</td>
      </tr>
      <tr>
        <td>3/4</td>
        <td>6</td>
        <td>23,07%</td>
      </tr>
      <tr>
        <td>4/4</td>
        <td>0</td>
        <td>0,00%</td>
      </tr>
      <tr>
        <th>Total</th>
        <th>26</th>
        <th>100%</th>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/julia-fortunato" target="_blank">Júlia Fortunato</a></p>
  </font>

</div>


## Bibliografia

> \- Documentação de histórias de usuário do AgroMart. Disponível em: <https://agromart.github.io/docs/docs/modelagem/historiaDeUsuario/co-agricultor>. Acesso em: 07 de julho de 2025.

> \- ALTEXSOFT. Acceptance Criteria: Purposes, Types, Examples and Best Prac. Disponível em: <https://www.altexsoft.com/blog/acceptance-criteria-purposes-formats-and-best-practices/>. Acesso em: 07 de julho de 2025.

‌

## Referências Bibliográficas

> [1] COHN, M.; BECK, K. User stories applied : for agile software development. Boston Etc.: Addison-Wesley, , Cop, 2004.

> [2] ATLASSIAN. Acceptance Criteria Explained [+ Examples & Tips]. Disponível em: <https://www.atlassian.com/work-management/project-management/acceptance-criteria>. Acesso em: 07 de julho de 2025.


## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/07/2025|Criação do documento| [Júlia Fortunato](https://github.com/julia-fortunato) | [Maurício Ferreira](https://github.com/mauricio-araujoo) |