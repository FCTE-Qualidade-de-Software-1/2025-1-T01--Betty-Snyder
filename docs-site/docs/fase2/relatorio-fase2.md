# Relatório da Fase 2 – Especificação da Avaliação de Qualidade do AgroMart

## Objetivo Geral

O objetivo principal desta fase é **avaliar a qualidade do sistema AgroMart**<sup>[1]</sup> de forma sistemática, utilizando como base a metodologia **GQM (Goal-Question-Metric)** para definir o que será medido e como interpretar os resultados. As métricas adotadas são fundamentadas no modelo de qualidade **Q-RAPIDS**, que permite associar dados do desenvolvimento e do código-fonte a fatores de produto e indicadores estratégicos.

A avaliação será conduzida de acordo com o processo definido na norma internacional **ISO/IEC 25040**<sup>[2]</sup>, garantindo que os procedimentos adotados sejam reprodutíveis, objetivos e confiáveis. Ao final, espera-se obter um diagnóstico confiável sobre os principais pontos fortes e fracos do sistema, com foco especial nas características de **usabilidade** e **confiabilidade**, que são as mais relevantes para o perfil do público-alvo da aplicação.

- **Componentes Avaliados**: Interface do usuário (frontend), backend (estabilidade), fluxo de pedidos e cadastro, acessibilidade.
- **Qualidades Prioritárias**: Usabilidade e Confiabilidade.
- **Contexto de Uso**: Agricultores familiares, pessoas com mais de 30 anos, idosos e público com baixa familiaridade com tecnologia.


## Abordagem GQM + Q-RAPIDS

Nesta etapa, combinamos duas abordagens complementares para avaliar a qualidade do sistema AgroMart: a metodologia **GQM (Goal-Question-Metric)** e o modelo **Q-RAPIDS**.

A abordagem GQM nos permite estruturar a avaliação a partir de objetivos claros, traduzidos em perguntas específicas que são respondidas por meio de métricas. Já o Q-RAPIDS nos ajuda a conectar essas métricas a fatores de produto e indicadores estratégicos, tornando possível não apenas medir a qualidade técnica, mas também entender seu impacto nos objetivos do negócio.

A seguir, detalhamos os dois principais objetivos de medição definidos para esta avaliação: Usabilidade e Confiabilidade.

### Objetivo 1: Avaliar a Usabilidade do AgroMart

| Questão | Métrica | Nível de Pontuação | Critério de Julgamento |
|--------|---------|---------------------|-------------------------|
| Os usuários conseguem concluir tarefas sem ajuda? | % de tarefas completadas sem ajuda externa | 0 a 5 | ≥ 80% = Aprovado |
| A navegação é intuitiva? | Tempo médio para realizar uma tarefa (ex: cadastro) | 0 a 5 | ≤ 3 min = Aprovado |
| O design é acessível? | % de conformidade com critérios WCAG | 0 a 5 | ≥ 95% = Aprovado |

### Objetivo 2: Avaliar a Confiabilidade do AgroMart

Neste objetivo, avalia-se a estabilidade e o comportamento do sistema diante de falhas e interrupções. A confiabilidade é crucial para manter a confiança do usuário final e garantir que o sistema funcione corretamente.

| Questão | Métrica | Nível de Pontuação | Critério de Julgamento |
|--------|---------|---------------------|-------------------------|
| O sistema falha durante o uso? | Nº de falhas por 100 sessões | 0 a 5 | ≤ 5 falhas = Aprovado |
| Ele recupera estado após interrupção? | % de processos retomados com sucesso | 0 a 5 | ≥ 95% = Aprovado |
| Mensagens de erro são claras? | % de erros com mensagem útil | 0 a 5 | ≥ 90% = Aprovado |


## Gráfico Hierárquico GQM–Q-RAPIDS

Abaixo está a estrutura hierárquica da avaliação, partindo dos objetivos de medição até as métricas que os sustentam. Essa visualização ajuda a garantir que cada dado coletado está diretamente ligado a um propósito claro de avaliação.

<gráfico>



| Nível | Descrição |
|-------|-----------|
| 5 | Excelente – Métrica atende plenamente |
| 4 | Bom – Pequenas melhorias necessárias |
| 3 | Aceitável – Atenção recomendada |
| 2 | Ruim – Exige correções importantes |
| 1 | Crítico – Falha grave |
| 0 | Não avaliado / Não aplicável |


## Métricas Q-RAPIDS utilizadas

As métricas adotadas para esta avaliação foram selecionadas com base nas camadas do modelo Q-RAPIDS, que conecta dados técnicos a decisões estratégicas. Foram utilizadas:

- **Métricas de Código**: complexidade cognitiva, duplicação, densidade de comentários.
- **Métricas de Processo**: issues abertas/fechadas, bugs, tempo de resolução, backlog.
- **Métricas de Aplicação**: uso real de funcionalidades, tempo médio por tarefa.
- **Fatores de Produto**: usabilidade percebida, tolerância a falhas, acessibilidade.
- **Indicadores Estratégicos**: confiabilidade percebida, mantenabilidade, aderência a requisitos.

Essas métricas permitem uma análise multidimensional da qualidade, indo além da técnica e focando também na experiência do usuário final e nos objetivos organizacionais.

<métricas> 


## Bibliografia
> 

## Referências Bibliográficas

> [1] AgroMart. Disponível em: https://github.com/AgroMart. Acesso em: 04 de julho de 2025.

> [2] ISO/IEC. ISO/IEC 25040:2011 — Systems and software engineering – Systems and software Quality Requirements and Evaluation (SQuaRE) – Evaluation process. Geneva: International Organization for Standardization, 2011.


## Tabela de Contribuição

<div align="center">
  <table border="1">
    <thead>
      <tr>
        <th>Matrícula</th>
        <th>Nome completo</th>
        <th>Contribuição (%)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>221007798</td>
        <td><a href="https://github.com/ailujana">Ana Júlia Mendes Santos</a></td>
        <td>16,6</td>
      </tr>
      <tr>
        <td>221022355</td>
        <td><a href="https://github.com/julia-fortunato">Júlia Rocha Fortunato</a></td>
        <td>16,6</td>
      </tr>
      <tr>
        <td>221008338</td>
        <td><a href="https://github.com/Oleari19">Maria Clara Oleari de Araujo</a></td>
        <td>16,6</td>
      </tr>
      <tr>
        <td>222007021</td>
        <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira de Araújo</a></td>
        <td>16,6</td>
      </tr>
      <tr>
        <td>222006356</td>
        <td><a href="https://github.com/PedroLock">Pedro Lock Martins</a></td>
        <td>16,6</td>
      </tr>
      <tr>
        <td>221022767</td>
        <td><a href="https://github.com/vevetin">Weverton Rodrigues da Costa Silva</a></td>
        <td>16,6</td>
      </tr>
    </tbody>
  </table>
</div>

## Historico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|04/07/2025|Base documento|[Maria Clara](https://github.com/Oleari19)| - |
