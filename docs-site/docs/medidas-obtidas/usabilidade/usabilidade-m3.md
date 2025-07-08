# Usabilidade - M3: Percentual de acertos na identificação de botões

## Introdução

Na presente execução da análise de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, a métrica M3 (Percentual de acertos na identificação de botões), com foco na experiência do usuário em dispositivos móveis.  
Essa métrica visa avaliar a capacidade dos usuários em identificar corretamente a funcionalidade dos botões presentes na interface, com base em seus rótulos, ícones e contexto visual.

## Referencial teórico 

Segundo a norma ISO/IEC 25010 <sup>[1]</sup>, a usabilidade é composta por atributos como compreensibilidade, operabilidade e atratividade. A capacidade de identificar corretamente os botões da interface está diretamente relacionada à compreensibilidade do sistema, sendo crucial para que o usuário navegue com segurança e eficiência.

As heurísticas de usabilidade propostas por Nielsen <sup>[2]</sup>, especialmente a H6 (Reconhecimento em vez de memorização), enfatizam que os elementos de interface devem ser compreensíveis sem exigir esforço de memória, promovendo a identificação imediata da funcionalidade esperada de cada botão.

## Análise

Foram selecionados 18 botões recorrentes no sistema Agromart, com base em sua frequência de uso e importância para a navegação. A seguir, os botões avaliados:

- "Adicionar"
- "Salvar"
- "Realizar"
- "Realizar Pagamento"
- "Escolha sua CSA"
- "Utilizar esta CSA"
- "Procurar outra CSA"
- "Voltar"
- "Logar"
- "Home"
- "Busca"
- "Histórico"
- "Perfil"
- "Meus dados"
- "Meus endereços"
- "Meus planos"
- "Sair"
- "Notificações"

Cada botão foi avaliado individualmente quanto à sua capacidade de ser corretamente identificado por usuários, considerando apenas seus elementos visuais e contexto imediato.

Critério de acerto: botão foi corretamente identificado na primeira tentativa **sem ajuda externa**.

## Execução da análise

A análise foi realizada com três participantes representando o público-alvo do sistema. Cada participante foi instruído a observar o botão e responder à pergunta: _“O que você espera que aconteça ao clicar nesse botão?”_

Um botão foi considerado corretamente identificado se o participante descreveu corretamente sua funcionalidade sem auxílio externo.

A Tabela 1 apresenta os resultados coletados:

<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 1 – Percentual de acertos na identificação dos botões</b></p>
  </font>

  <table border="1" style="margin: 0 auto;">
    <thead>
      <tr>
        <th>Botão</th>
        <th>Acertos</th>
        <th>Tentativas</th>
        <th>Percentual (%)</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Adicionar</td><td>0</td><td>3</td><td>0%</td></tr>
      <tr><td>Salvar</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Realizar</td><td>0</td><td>3</td><td>0%</td></tr>
      <tr><td>Realizar Pagamento</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Escolha sua CSA</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Utilizar esta CSA</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Procurar outra CSA</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Voltar</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Logar</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Home</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Busca</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Histórico</td><td>0</td><td>3</td><td>0%</td></tr>
      <tr><td>Perfil</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Meus dados</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Meus endereços</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Meus planos</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Sair</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr><td>Notificações</td><td>3</td><td>3</td><td>100%</td></tr>
      <tr>
        <td><b>Média Geral</b></td>
        <td colspan="2" style="text-align: center"><b>—</b></td>
        <td><b>83,3%</b></td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/ailujana">Ana Júlia</a></p>
  </font>

</div>


## Resultados

Os dados obtidos apontam para um bom nível de identificação dos botões por parte dos usuários (média de 83,3%). A maioria dos botões apresentava texto e/ou ícones intuitivos, o que favoreceu o reconhecimento correto.

Entretanto, os botões "Adicionar", "Realizar" e "Histórico" apresentaram baixa taxa de acertos (0%), indicando problemas de clareza visual ou ambiguidade de significado. Esse resultado sugere a necessidade de:

- Incluir rótulos textuais complementares em botões que utilizam apenas ícones;

- Revisar iconografia e nomenclatura, especialmente em ações genéricas como “Realizar”;

- Aplicar padrões visuais consistentes, com o uso de cores e formatos que transmitam intenção da ação.

Com base nos critérios definidos na Fase 2, a métrica M3 foi classificada com a **pontuação 8 (Bom)**, demonstrando que, apesar de pontos de atenção, a interface atende satisfatoriamente ao princípio de compreensibilidade.

## Referências Bibliográficas

- [1] ISO/IEC 25010:2011 – Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE)

- [2] NIELSEN, Jakob. Heuristics for User Interface Design, 1995.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-----:|
|`1.0`|07/07/2025|Criação do documento| [Ana Júlia](https://github.com/ailujana) | [Weverton Rodrigues](https://github.com/vevetin) |
