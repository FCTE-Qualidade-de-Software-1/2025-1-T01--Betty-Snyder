# Relatório da Entrega Final – Especificação da Avaliação de Qualidade do AgroMart

## Objetivo Geral

O objetivo principal desta fase é **avaliar a qualidade do sistema AgroMart**<sup>[1]</sup> de forma sistemática, utilizando como base a metodologia **GQM (Goal-Question-Metric)** para definir o que será medido e como interpretar os resultados. As métricas adotadas são fundamentadas no modelo de qualidade **Q-RAPIDS**, que permite associar dados do desenvolvimento e do código-fonte a fatores de produto e indicadores estratégicos.

A avaliação será conduzida de acordo com o processo definido na norma internacional **ISO/IEC 25040**<sup>[2]</sup>, garantindo que os procedimentos adotados sejam reprodutíveis, objetivos e confiáveis. Ao final, espera-se obter um diagnóstico confiável sobre os principais pontos fortes e fracos do sistema, com foco especial nas características de **usabilidade** e **confiabilidade**, que são as mais relevantes para o perfil do público-alvo da aplicação.

## Abordagem GQM + Q-RAPIDS

Nesta etapa, combinamos duas abordagens complementares para avaliar a qualidade do sistema AgroMart: a metodologia **GQM (Goal-Question-Metric)** e o modelo **Q-RAPIDS**.

A abordagem GQM nos permite estruturar a avaliação a partir de objetivos claros, traduzidos em perguntas específicas que são respondidas por meio de métricas. Já o Q-RAPIDS nos ajuda a conectar essas métricas a fatores de produto e indicadores estratégicos, tornando possível não apenas medir a qualidade técnica, mas também entender seu impacto nos objetivos do negócio.


## Fase 1 - Estabelecer os Requisitos de Avaliação
...

## Fase 2: Especificar a Avaliação

### Seleção das Métricas

Com base na abordagem **Goal-Question-Metric (GQM)**, selecionamos as seguintes métricas para a avaliação:

#### Confiabilidade:
- **M1:** Percentual de erros com mensagens claras e sem perda de dados.
- **M2:** Tempo médio de resposta do sistema após a ocorrência de erros.
- **M3:** Percentual de requisitos que possuem testes automatizados associados.
- **M4:** Percentual de requisitos com critérios de aceitação bem definidos.

#### Usabilidade:
- **M1:** Tempo médio para completar tarefas.
- **M2:** Taxa de sucesso de novos usuários em tarefas básicas.
- **M3:** Percentual de acertos na identificação de botões.
- **M4:** Percentual de erros com sugestões de correção e mensagens claras.
- **M5:** Taxa de recuperação após erro.
- **M6:** Nota média atribuída pelos usuários em questionário sobre a interface da aplicação.
- **M7:** Percentual de compatibilidade com leitores de tela.
- **M8:** Percentual de avaliação positiva em ferramenta automatizada de acessibilidade.
- **M9:** Tempo médio de navegação utilizando o teclado (tecla Tab).

### Níveis de Pontuação das Métricas

Após discussões internas no grupo, decidimos adotar uma escala de pontuação de **0 a 10** para cada métrica, com as seguintes categorias de avaliação:

- **Excelente (10):** Desempenho superior, com poucas falhas e alta usabilidade.
- **Bom (7-9):** Algumas falhas, mas o sistema continua funcional. A usabilidade é razoável.
- **Razoável (4-6):** O sistema apresenta falhas frequentes ou tarefas difíceis de completar.
- **Ruim (1-3):** O sistema apresenta falhas críticas que afetam negativamente a experiência do usuário, necessitando de melhorias substanciais.

### Critérios para Julgamento

Para cada subcaracterística de qualidade, estabelecemos os seguintes critérios de julgamento:

- **Confiabilidade:** O sistema será classificado como **"ruim"** em confiabilidade caso apresente falhas frequentes ou impactantes, prejudicando a funcionalidade e a experiência do usuário. Caso contrário, será classificado como **"aprovado"**.
  
- **Usabilidade:** O sistema será classificado como **"ruim"** em usabilidade caso os membros da equipe encontrem dificuldades significativas ao realizar tarefas principais, como navegação ou interações com a interface. Caso contrário, será classificado como **"aprovado"**.

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
|`1.1`|04/07/2025|Ajustes de acordo com as decisões do grupo|[Ana Júlia](https://github.com/ailujana)| - |
