# Usabilidade - M1: Tempo médio de realização de uma tarefa por meio de toques na interface
## Introdução

Na presente execução da análide de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, métricas voltadas à avaliação da experiência do usuário com enfoque mobile-first. 
Esse documento tem como objetivo sintetizar os achados referentes à métrica M1 (Tempo médio de realização de uma tarefa por meio de toques na interface), considerada essencial para avaliar a usabilidade do sistema em dispositivos móveis.

## Referencial teórico 

Segundo a norma ISO/IEC 25010 <sup>[1]</sup>, a Usabilidade pode ser definida como "o grau com que um produto ou sistema pode ser usado por usuários específicos para alcançar objetivos específicos com precisão e completude, dentro de um tempo adequado e com esforço razoável".

No contexto mobile-first, onde o uso é predominantemente por meio de telas sensíveis ao toque, a métrica de tempo médio para completar tarefas torna-se um indicador direto da fluidez e facilidade de uso da interface.

De acordo com Nielsen <sup>[2]</sup>, uma boa usabilidade em dispositivos móveis depende, entre outros fatores, da disposição clara dos elementos de interação, tamanho adequado dos alvos de toque, e da redução do número de etapas para realizar uma tarefa.

Portanto, quanto menor for o tempo médio de execução de tarefas essenciais, mais eficiente e usável é a interface, refletindo diretamente na satisfação e retenção dos usuários.

## Análise

Dessa forma, a avaliação será dada de forma quantitativa, com base no tempo médio necessário para que usuários concluam tarefas específicas por meio de interações por toque na interface mobile do Agromart.

As tarefas selecionadas para análise foram baseadas em funcionalidades essenciais do sistema, como as descritas na [documentação de histórias de usuário](https://agromart.github.io/docs/docs/modelagem/historiaDeUsuario/co-agricultor), com foco em ações recorrentes, como o agendamento de serviços, visualização de informações e finalização de solicitações.

Os critérios de julgamento e níveis de pontuação da métrica serão utilizados conforme especificados na [Fase 2](../../gqm/gqm.md#níveis-de-pontuação-das-métricas), considerando o tempo médio por tarefa e sua comparação com padrões de usabilidade mobile encontrados na literatura e/ou definidos pela equipe.

A partir desses dados, será possível verificar se o tempo de execução observado está de acordo com o desempenho esperado, e se o sistema oferece uma experiência eficiente e fluida aos usuários em dispositivos móveis.

## Execução da análise

A avaliação foi conduzida por meio de testes exploratórios, nos quais foi realizada a simulação do uso do sistema Agromart em ambiente mobile, a partir da perspectiva de um usuário final. As interações foram realizadas em um dispositivo com tela sensível ao toque, com o objetivo de observar o tempo necessário para a execução de tarefas essenciais exclusivamente por meio de toques (tap) na interface.

Dentre as histórias de usuário disponíveis, apenas a US01: Realizar Cadastro na CSA apresentou estrutura e fluxo funcional suficiente para possibilitar a avaliação da métrica de tempo médio de execução. Essa história foi selecionada por representar uma tarefa comum e crítica no sistema, além de possuir pontuação elevada em critérios de clareza e testabilidade.

A tarefa foi executada três vezes consecutivas, simulando o comportamento de um usuário comum. O tempo de execução foi cronometrado manualmente, considerando o intervalo entre o primeiro toque relacionado ao início do cadastro e a finalização do processo (toque no botão de envio/registro).

A seguir, a Tabela 1 apresenta os tempos registrados em cada tentativa e o valor médio calculado.

<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 1 – Tempos de execução da US01: Realizar Cadastro na CSA</b></p>
  </font>

  <table border="1" style="margin: 0 auto;">
    <thead>
      <tr>
        <th>Tentativa</th>
        <th>Tempo de execução (s)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>1</td>
        <td>27,43</td>
      </tr>
      <tr>
        <td>2</td>
        <td>24,57</td>
      </tr>
      <tr>
        <td>3</td>
        <td>26,31</td>
      </tr>
      <tr>
        <td><b>Média total</b></td>
        <td><b>26,10</b></td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/vevetin">Weverton Rodrigues</a></p>
  </font>

</div>


## Resultados

A partir da execução da métrica M1, observou-se que a tarefa de Realizar Cadastro na CSA pôde ser completada com relativa fluidez, apresentando um tempo médio de 26,10 segundos, o que indica um bom desempenho da interface em termos de agilidade e simplicidade de interação.

No entanto, durante a análise prática, foi identificada uma interferência significativa no fluxo da tarefa: ao tocar no botão "Criar uma conta", a tela de cadastro pisca brevemente e é sobreposta por um modal de busca de CSA, o que obriga o usuário a retornar uma etapa manualmente para prosseguir com o cadastro. Esse tipo de comportamento pode causar confusão e frustração, além de violar o princípio de previsibilidade da interface.

Dessa forma, considerando os critérios definidos na Fase 2, a métrica M1 foi classificada com a **pontuação 7 (Bom)**, o que significa que a aplicação atende de forma satisfatória, mas apresenta oportunidades claras de melhoria, especialmente relacionadas ao fluxo de navegação e comportamento da interface.

## Bibliografia

> \- Documentação de histórias de usuário do AgroMart. Disponível em: <https://agromart.github.io/docs/docs/modelagem/historiaDeUsuario/co-agricultor>. Acesso em: 07 de julho de 2025.

## Referências Bibliográficas

> [1] ISO/IEC. ISO/IEC 25010:2011 — Systems and software engineering – Systems and software Quality Requirements and Evaluation (SQuaRE) – System and software quality models. International Organization for Standardization, 2011.

> [2] NIELSEN, Jakob. Mobile Usability. Berkeley: New Riders Pub, 2012.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/07/2025|Criação do documento| [Weverton Rodrigues](https://github.com/vevetin) | [Ana Júlia](https://github.com/ailujana) |