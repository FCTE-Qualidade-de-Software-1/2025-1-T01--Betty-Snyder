# Relatório da Entrega Final – Especificação da Avaliação de Qualidade do AgroMart

## Introdução

Este relatório apresenta o processo de avaliação da qualidade da aplicação AgroMart, seguindo a abordagem definida pela norma ISO/IEC 25000 (SQuaRE), complementada pelos métodos GQM (Goal-Question-Metric) [3] e PSM (Practical Software Measurement) [4]. A avaliação foi conduzida no contexto da disciplina de Qualidade de Software da Universidade de Brasília, com o objetivo de analisar criticamente aspectos relacionados à usabilidade e confiabilidade da aplicação.

## Objetivo Geral

O objetivo principal desta fase é **avaliar a qualidade do sistema AgroMart**<sup>[1]</sup> de forma sistemática, utilizando como base a metodologia **GQM (Goal-Question-Metric)** para definir o que será medido e como interpretar os resultados. A avaliação será conduzida de acordo com o processo definido na norma internacional **ISO/IEC 25040**<sup>[2]</sup>, garantindo que os procedimentos adotados sejam reprodutíveis, objetivos e confiáveis. Ao final, espera-se obter um diagnóstico confiável sobre os principais pontos fortes e fracos do sistema, com foco especial nas características de **usabilidade** e **confiabilidade**, que são as mais relevantes para o perfil do público-alvo da aplicação.

## Referencial Teórico

A avaliação foi pautada nas normas da família ISO/IEC 25000 (SQuaRE), com destaque para a ISO/IEC 25010, que define o modelo de qualidade de produto. As características selecionadas — usabilidade e confiabilidade — estão diretamente ligadas à acessibilidade, clareza e estabilidade de sistemas voltados ao público geral.

Complementarmente, foram adotadas as abordagens:

- **GQM (Goal-Question-Metric):** que permite estruturar a avaliação a partir de metas claras, associadas a perguntas e métricas;
- **PSM (Practical Software Measurement):** para facilitar a seleção de métricas observáveis e práticas, alinhadas à realidade da aplicação.

## Fase 1 – Processo de Avaliação

### Contexto de Trabalho

A aplicação AgroMart foi avaliada no contexto acadêmico, sendo um sistema híbrido que conecta pequenos produtores a consumidores por meio de uma interface web (produtores) e um aplicativo móvel (consumidores).

### Características Priorizadas

As seguintes características de qualidade foram priorizadas:

| Característica     | Ênfase (1–5)          |
|--------------------|-----------------------|
| Usabilidade        | 5 – grande interesse  |
| Confiabilidade     | 5 – grande interesse  |
| Funcionalidade     | 4 – largo interesse   |
| Eficiência         | 2 – baixo interesse   |
| Compatibilidade    | 2 – baixo interesse   |
| Segurança          | 1 – nenhum interesse  |
| Manutenibilidade   | 1 – nenhum interesse  |
| Portabilidade      | 1 – nenhum interesse  |

### Público-alvo

- Indivíduos com mais de 30 anos;
- Pessoas com pouca familiaridade tecnológica.

### Conexão com os ODS da ONU

O AgroMart está alinhado com os seguintes Objetivos de Desenvolvimento Sustentável (ODS):  
ODS 2, 8, 11, 12 e 15.

## Fase 2 – Especificação da Avaliação

A Fase 2 foi dedicada à estruturação da avaliação por meio da abordagem GQM. Foram definidos dois objetivos principais, cada um com perguntas e métricas associadas:

### Objetivo 1 – Avaliar a Usabilidade

| Código | Pergunta                                            | Métrica                                         |
|--------|------------------------------------------------------|-------------------------------------------------|
| M1     | Os usuários completam tarefas rapidamente?           | Tempo médio para completar tarefas              |
| M2     | Novos usuários conseguem realizar tarefas básicas?   | Taxa de sucesso de novos usuários               |
| M4     | O sistema sugere correções e mensagens claras?       | % de erros com sugestões e mensagens claras     |
| M5     | Os usuários conseguem se recuperar após erros?       | Taxa de recuperação após erro                   |
| M6     | Qual a percepção geral dos usuários sobre a interface?| Nota média atribuída à interface                |

### Objetivo 2 – Avaliar a Confiabilidade

| Código | Pergunta                                         | Métrica                             |
|--------|--------------------------------------------------|-------------------------------------|
| M7     | O sistema falha com frequência?                  | Frequência de falhas por sessão     |
| M8     | O sistema recupera estado após falhas?           | % de sessões com recuperação total  |

### Critérios de Julgamento

Cada métrica foi associada a uma escala de 0 a 10, agrupada nos níveis:

- 0–3: Insatisfatório
- 4–6: Regular
- 7–8: Bom
- 9–10: Excelente

## Fase 3 – Plano de Avaliação

### Método de Avaliação

A avaliação combinou testes internos de usabilidade e confiabilidade, com observação direta e aplicação de questionários pós-tarefa. Foram considerados:

- Tempo médio por tarefa;
- Erros detectados;
- Nível de satisfação subjetiva;
- Acessibilidade e clareza da interface.

### Instruções de Aplicação

Os participantes realizaram tarefas simuladas enquanto membros da equipe observaram, registrando:

- Tempo para cada etapa;
- Ocorrência e tipo de erro;
- Capacidade de recuperação e clareza das mensagens.

Ao fim, aplicou-se um questionário subjetivo com perguntas sobre clareza, ícones, fluidez e estética da interface.

### Recursos Utilizados

- Cronômetro digital;
- Ferramentas de captura de tela (opcional);
- TalkBack (testes de acessibilidade);
- Documentação das métricas e heurísticas de Nielsen.

### Cronograma

| Etapa                             | Início    | Conclusão | Responsável     |
|----------------------------------|-----------|-----------|-----------------|
| Coleta de dados e testes         | 05/07/25  | 07/07/25  | Equipe Técnica  |
| Análise final e relatório        | 07/07/25  | 08/07/25  | Equipe Técnica  |

## Fase 4 - Execução da Avaliação

Esta etapa refere-se à aplicação prática das métricas de qualidade definidas nas fases anteriores do processo SQuaRE, adaptado com a abordagem GQM + PSM. A execução foi conduzida a partir dos planos estabelecidos, visando coletar dados objetivos e subjetivos sobre os atributos de confiabilidade e usabilidade do sistema AgroMart.

### Métricas Aplicadas

As seguintes métricas foram aplicadas na Fase 4:

#### Usabilidade

* **M1 (Tempo para completar tarefas)**
* **M2 (Taxa de erros)**
* **M3 (Facilidade de aprendizagem)**
* **M4 (Acessibilidade com leitores de tela)**
* **M5 (Aderência a heurísticas de usabilidade)**
* **M6 (Percepção subjetiva dos usuários)**
* **M7 (Avaliação por tecnologias assistivas)**
* **M8 (Consistência visual e de navegação)**

#### Confiabilidade

* **M1 (Tempo de resposta da aplicação)**
* **M2 (Erro no primeiro acesso / onboarding)**
* **M3 (Taxa de falhas ao longo da navegação)**

### Coleta de Dados

A coleta de dados foi realizada conforme o plano de avaliação. Para cada métrica:

* Dados quantitativos: cronômetro, tempo de resposta, contagem de erros.
* Dados qualitativos: opiniões dos usuários, avaliação por tecnologias assistivas, checklists de consistência e heurísticas.
* Participantes: 5 a 6 integrantes da equipe realizaram testes individuais e contribuíram com feedbacks.

### Julgamento dos Resultados

Os resultados foram comparados aos critérios definidos na [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#criterios-para-julgamento). Cada métrica recebeu uma pontuação de 0 a 10, com base nas escalas previamente acordadas.

### Evidências Documentadas

Os resultados detalhados de cada métrica estão documentados nos arquivos:

* `usabilidade-m1.md` a `usabilidade-m8.md`:  
  [M1 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m1/)  
  [M2 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m2/)  
  [M3 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m3/)  
  [M4 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m4/)  
  [M5 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m5/)  
  [M6 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m6/)  
  [M7 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m7/)  
  [M8 - Usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m8/)

* `confiabilidade-m1.md` a `confiabilidade-m3.md`:  
  [M1 - Confiabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/confiabilidade/confiabilidade-m1/)  
  [M2 - Confiabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/confiabilidade/confiabilidade-m2/)  
  [M3 - Confiabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/confiabilidade/confiabilidade-m3/)

Cada documento inclui:

* Introdução
* Referencial teórico 
* Análise
* Execução da análise
* Resultados e Recomendações
* Bibliografia
* Referências Bibliográficas
* Histórico de Versões

### Consolidação e Análise

Os resultados foram agrupados por atributo:

#### Usabilidade

A análise de usabilidade do sistema Agromart foi conduzida com base em oito métricas específicas (M1 a M8), cobrindo aspectos fundamentais da experiência do usuário, especialmente em dispositivos móveis. A seguir, é apresentada uma síntese dos principais achados, destacando tanto os pontos fortes quanto os aspectos que requerem melhorias.

##### Destaques Positivos

- **Boa percepção geral da estética e organização visual** da interface por parte dos participantes.
- **Tempo médio de execução das tarefas** abaixo de 2 minutos, indicando fluidez razoável nas interações básicas (M1).
- A maioria dos fluxos apresenta **respostas rápidas** e sem falhas críticas.
- **Mensagens de erro são parcialmente claras**, permitindo que usuários mais experientes recuperem-se sem necessidade de reinício do processo (M4, M5).

##### Pontos de Melhoria

- **Taxa de sucesso de novos usuários em tarefas básicas (M2)** foi considerada **insatisfatória**, indicando dificuldade de compreensão de navegação sem orientação prévia.
- O **percentual de acertos na identificação de botões (M3)** foi abaixo do esperado, sugerindo falta de padronização nos elementos da interface.
- As **mensagens de erro carecem de clareza e sugestões de correção**, impactando diretamente a eficiência e frustração dos usuários (M4).
- **A recuperação após erro (M5)** é possível, mas sem suporte visual ou textual claro.
- A **compatibilidade com leitores de tela (M7)** é limitada, dificultando o uso por pessoas com deficiência visual.
- **Ferramentas automatizadas de acessibilidade (M8)** apontaram problemas de contraste, hierarquia semântica e ausência de descrições adequadas em botões e imagens.

##### Conclusão

A avaliação da usabilidade demonstra que o sistema possui uma base funcional promissora, porém com lacunas relevantes em aspectos de acessibilidade, onboarding e padronização de elementos visuais. A métrica foi classificada como **Regular**, e melhorias são recomendadas especialmente na orientação ao usuário, consistência de design e adaptação para tecnologias assistivas.

#### Confiabilidade

A avaliação da confiabilidade do Agromart foi realizada com base em três métricas complementares: (1) percepção subjetiva dos usuários sobre confiabilidade, (2) percentual de requisitos com testes automatizados e (3) percentual de critérios de aceitação bem definidos.

##### Destaques positivos

* A aplicação responde corretamente aos comandos básicos, sem apresentar falhas críticas durante o uso comum.
* Parte dos requisitos funcionais já está coberta por testes automatizados (52,17%), especialmente funcionalidades centrais como login, cadastro e exibição de produtos.
* Algumas histórias de usuário possuem critérios de aceitação relativamente bem estruturados, com foco em clareza e testabilidade (ex: US01, US19, US20).

##### Pontos fracos

* A maior parte das histórias de usuário (73%) não possui critérios de aceitação adequados, o que dificulta a verificação e validação confiável do sistema.
* A cobertura de testes automatizados ainda é limitada, com 47,83% dos requisitos funcionais sem validação automatizada — incluindo funcionalidades críticas como o carrinho de compras.
* O processo de onboarding não é intuitivo e causou confusão entre os avaliadores no primeiro contato com o sistema, impactando negativamente a confiança inicial.
* Em alguns testes manuais, houve incerteza quanto ao comportamento esperado do sistema, indicando falhas na especificação e comunicação de requisitos.

##### Conclusão

Apesar de apresentar boa estabilidade em tarefas básicas e uma cobertura inicial de testes, o Agromart ainda carece de práticas mais robustas para garantir a confiabilidade do sistema. A ausência de critérios de aceitação consistentes e a cobertura incompleta de testes automatizados representam riscos para a manutenção, escalabilidade e evolução da plataforma. Reforça-se a necessidade de melhoria na documentação de requisitos e na priorização de testes automatizados para funcionalidades essenciais.

### Ações de Melhoria Implementadas

Com base na fase de julgamento, foram propostas e implementadas melhorias, como:

* Protótipo de alta fidelidade com revisão de fluxo e consistência visual 
* Arquivos [1](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/trabalho-final/avaliacao_agromart_anaju/) e [2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/trabalho-final/avaliacao_visual/) com recomendações de melhoria 
* Atualização do design e layout (com base em feedbacks da métrica M6)

### Conclusão da Avaliação

A Fase 4 permitiu validar as hipóteses formuladas na Fase 2 e gerou subsídios para uma evolução significativa da aplicação AgroMart. A análise integrada revelou que, apesar de limitações pontuais, a plataforma possui bom potencial de usabilidade e apresenta um nível de confiabilidade compatível com o estágio atual de desenvolvimento.

## Tabela de Contribuição - Fase 1

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


## Tabela de Contribuição - Fase 2

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
        <td>20</td>
      </tr>
      <tr>
        <td>221022355</td>
        <td><a href="https://github.com/julia-fortunato">Júlia Rocha Fortunato</a></td>
        <td>20</td>
      </tr>
      <tr>
        <td>221008338</td>
        <td><a href="https://github.com/Oleari19">Maria Clara Oleari de Araujo</a></td>
        <td>13,3</td>
      </tr>
      <tr>
        <td>222007021</td>
        <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira de Araújo</a></td>
        <td>13,3</td>
      </tr>
      <tr>
        <td>222006356</td>
        <td><a href="https://github.com/PedroLock">Pedro Lock Martins</a></td>
        <td>13,3</td>
      </tr>
      <tr>
        <td>221022767</td>
        <td><a href="https://github.com/vevetin">Weverton Rodrigues da Costa Silva</a></td>
        <td>20</td>
      </tr>
    </tbody>
  </table>
</div>


## Tabela de Contribuição - Fase 3

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
        <td>30</td>
      </tr>
      <tr>
        <td>221022355</td>
        <td><a href="https://github.com/julia-fortunato">Júlia Rocha Fortunato</a></td>
        <td>15</td>
      </tr>
      <tr>
        <td>221008338</td>
        <td><a href="https://github.com/Oleari19">Maria Clara Oleari de Araujo</a></td>
        <td>10</td>
      </tr>
      <tr>
        <td>222007021</td>
        <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira de Araújo</a></td>
        <td>10</td>
      </tr>
      <tr>
        <td>222006356</td>
        <td><a href="https://github.com/PedroLock">Pedro Lock Martins</a></td>
        <td>5</td>
      </tr>
      <tr>
        <td>221022767</td>
        <td><a href="https://github.com/vevetin">Weverton Rodrigues da Costa Silva</a></td>
        <td>30</td>
      </tr>
    </tbody>
  </table>
</div>


## Tabela de Contribuição - Fase 4

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
        <td>20</td>
      </tr>
      <tr>
        <td>221022355</td>
        <td><a href="https://github.com/julia-fortunato">Júlia Rocha Fortunato</a></td>
        <td>20</td>
      </tr>
      <tr>
        <td>221008338</td>
        <td><a href="https://github.com/Oleari19">Maria Clara Oleari de Araujo</a></td>
        <td>14</td>
      </tr>
      <tr>
        <td>222007021</td>
        <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira de Araújo</a></td>
        <td>15</td>
      </tr>
      <tr>
        <td>222006356</td>
        <td><a href="https://github.com/PedroLock">Pedro Lock Martins</a></td>
        <td>11</td>
      </tr>
      <tr>
        <td>221022767</td>
        <td><a href="https://github.com/vevetin">Weverton Rodrigues da Costa Silva</a></td>
        <td>20</td>
      </tr>
    </tbody>
  </table>
</div>

## Bibliografia
> [1] NIELSEN, Jakob. Mobile Usability. Berkeley: New Riders Pub, 2012.

> [2] GASSENFERTH, Daniel. How to design better error messages • Centigrade GmbH. Disponível em: <https://www.centigrade.de/en/blog/how-to-design-better-error-messages/>. Acesso em: 07 de julho de 2025.

> \- Documentação da Fase 1 do Grupo Betty Snyder (T01-2025). Disponível em: <https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/processo-avaliacao/processo_de_avaliacao/>. Acesso em: 08 de julho de 2025.

> \- Documentação da Fase 2 do Grupo Betty Snyder (T01-2025). Disponível em: <https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/>. Acesso em: 08 de julho de 2025.

> \- Documentação da Fase 3 do Grupo Betty Snyder (T01-2025). Disponível em: <https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/plano-avaliacao/plano_avaliacao/>. Acesso em: 08 de julho de 2025.

> \- Documentação da Fase 4 do Grupo Betty Snyder (T01-2025). Disponível em: <https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m1/>. Acesso em: 08 de julho de 2025.

## Referências Bibliográficas

> [1] AgroMart. Disponível em: https://github.com/AgroMart. Acesso em: 04 de julho de 2025.

> [2] ISO/IEC. ISO/IEC 25040:2011 — Systems and software engineering – Systems and software Quality Requirements and Evaluation (SQuaRE) – Evaluation process. Geneva: International Organization for Standardization, 2011.

> [3] Basili, V. R., Caldiera, G., & Rombach, H. D. (1994). The Goal Question Metric Approach. In *Encyclopedia of Software Engineering*. John Wiley & Sons.  

> [4] Practical Software and Systems Measurement (PSM). Department of Defense, 2003. Disponível em: https://www.psmsc.com/. Acesso em: 04 de julho de 2025.

## Historico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|04/07/2025|Base documento|[Maria Clara](https://github.com/Oleari19)| - |
|`1.1`|04/07/2025|Ajustes de acordo com as decisões do grupo|[Ana Júlia](https://github.com/ailujana)| - |
|`1.2`|04/07/2025|Criação e documentação do Relatório Final|[Ana Júlia](https://github.com/ailujana) e [Júlia Fortunato](https://github.com/julia-fortunato)| - |
