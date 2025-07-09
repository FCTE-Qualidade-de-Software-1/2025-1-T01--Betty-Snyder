# Usabilidade - M2: Taxa de sucesso de novos usuários em tarefas básicas
## Introdução

Durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto Agromart, foi definida a métrica M2 com o objetivo de avaliar a eficácia da interface para novos usuários. A métrica busca mensurar o grau de intuitividade do sistema, com base na taxa de sucesso de usuários inexperientes na execução de tarefas básicas, sem auxílio externo. Trata-se de um indicador direto da capacidade da interface em guiar novos usuários com clareza e consistência.

## Referencial teórico

Segundo Nielsen (1993)<sup>[1]</sup>, sistemas eficazes devem permitir que usuários novatos realizem tarefas essenciais sem depender de treinamentos prévios, com base apenas em sua familiaridade com interfaces similares e na clareza das instruções visuais disponíveis. A taxa de sucesso em tarefas básicas é, portanto, um dos indicadores mais confiáveis de usabilidade, especialmente no que diz respeito à curva de aprendizado, consistência dos padrões e organização semântica da interface.

## Análise

Para a avaliação da métrica M2, foram consideradas tarefas diretamente associadas à jornada inicial do usuário no aplicativo, conforme definido na Fase 2:

- Criar uma conta;

- Realizar login;

- Escolher uma CSA.

Essas tarefas foram executadas por três membros da equipe simulando o comportamento de novos usuários, ou seja, sem conhecimento prévio da aplicação e sem acesso a documentação técnica.

## Execução da análise

Cada tarefa foi considerada "bem-sucedida" se o participante conseguisse completá-la integralmente, sem solicitar ajuda ou cometer erros críticos que inviabilizassem o progresso. As interações foram monitoradas presencialmente e os resultados foram registrados manualmente.

<div style="text-align: center">
 <font size="3"> <p><b>Tabela 1 – Taxa de sucesso dos novos usuários em tarefas básicas</b></p> </font>
  <table border="1" style="margin: 0 auto;">
   <thead>
      <tr>
        <th>Tarefa</th>
        <th>Tentativas bem-sucedidas</th>
        <th>Total de tentativas</th>
        <th>Taxa de Sucesso (%)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Criar conta</td>
        <td>0</td>
        <td>3</td>
        <td>0%</td>
      </tr>
      <tr>
        <td>Realizar login</td>
          <td>0</td>
          <td>3</td>
          <td>0%</td>
        </tr>
      <tr>
        <td>Escolher uma CSA</td>
        <td>0</td>
        <td>3</td>
        <td>0%</td>
      </tr>
    </tbody>
  </table> <font size="3"> <p><b>Autor:</b> <a href="https://github.com/ailujana">Ana Júlia</a></p> </font> 
</div>

Observação: Nenhuma das tentativas foi bem-sucedida devido à ausência de documentação técnica eficaz e à dificuldade de executar a aplicação em seu estado atual.

## Resultados

A taxa de sucesso geral observada foi de 0%, ficando significativamente abaixo do valor de referência de 70% estabelecido na Fase 2 do projeto. Esse resultado evidencia sérias limitações no sistema quanto à sua capacidade de apoiar a jornada de usuários iniciantes.

Os principais fatores observados foram:

- Falta de documentação clara e atualizada para instruir o primeiro acesso;

- Interface com baixa orientação visual e ausência de feedback contextual;

- Fluxos confusos e pouco previsíveis, especialmente na tela de criação de conta.

Dessa forma, a métrica M2 foi classificada com **pontuação 1 (Insatisfatório)**, comprometendo a experiência de novos usuários e evidenciando a necessidade urgente de melhorias na interface e nos mecanismos de onboarding.

Recomenda-se:

- Atualizar o aplicativo e garantir que os fluxos essenciais estejam funcionando;

- Revisar e ampliar a documentação técnica e de uso;

- Incorporar feedbacks visuais e guias interativos no início do uso.

## Referências Bibliográficas

- [1] NIELSEN, Jakob. Usability Engineering. San Francisco: Morgan Kaufmann, 1993.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/07/2025|Criação do documento| [Ana Júlia](https://github.com/ailujana) | [Weverton Rodrigues](https://github.com/vevetin)|
|`1.1`|07/07/2025|Pequena melhoria na escrita|[Maria Clara](https://github.com/Oleari19)| - |