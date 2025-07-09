# Usabilidade - M4: Percentual de erros com sugestões de correção e mensagens claras.

## Introdução

Na presente execução da análise de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, a métrica M4 (Percentual de erros com sugestões de correção e mensagens claras), com foco na experiência do usuário em dispositivos móveis.
 Essa métrica avalia a capacidade do sistema de detectar erros e apresentar mensagens claras com orientações corretivas, promovendo uma experiência segura, eficiente e satisfatória para o usuário.

## Referencial teórico 

De acordo com a norma ISO/IEC 25010 [1], a qualidade da usabilidade envolve aspectos como prevenção de erros e recuperabilidade, sendo essencial que o sistema informe adequadamente sobre falhas de uso e auxilie o usuário na resolução de problemas rapidamente.

As heurísticas de Nielsen [2], especialmente a H5 – Prevenção de erros e a H9 – Ajuda ao diagnóstico e recuperação de erros, reforçam a importância de:

- Reduzir as chances de erro;

- Fornecer mensagens claras e específicas quando um erro ocorrer;

- Sugerir caminhos objetivos para resolução.

## Análise

Durante a avaliação, foram selecionados três fluxos considerados críticos para a interação do usuário com o sistema:

- Cadastro de endereço

- Finalização de pedido

- Login

Os testes foram conduzidos com simulações intencionais de erro, a fim de observar a capacidade do sistema de resposta adequada. Os principais comportamentos observados incluem:

- Falta de validação visual em campos obrigatórios (como CEP e endereço);

- Ausência de mensagens de erro específicas, como "CEP inválido" ou "campo obrigatório";

- Inexistência de sugestões automáticas para correção dos erros cometidos.

Apesar disso, o sistema não apresentou falhas críticas ou travamentos, demonstrando tolerância razoável a entradas inválidas.

## Execução da análise

Foram realizadas simulações de erro em diferentes cenários, com observação direta dos resultados. A Tabela 1 resume os achados:

<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 1 – Respostas do sistema a diferentes cenários de erro</b></p>
  </font>

  <table border="1" style="margin: 0 auto;">
    <thead>
      <tr>
        <th>Cenário</th>
        <th>Erro detectado pelo sistema?</th>
        <th>Mensagem clara?</th>
        <th>Sugestão de correção?</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>CEP inválido</td>
        <td>Não</td>
        <td>Não</td>
        <td>Mensagem clara de erro</td>
      </tr>
      <tr>
        <td>Cadastrar endereço com campos vazios</td>
        <td>Sim</td>
        <td>Não</td>
        <td>Mensagem clara de erro</td>
      </tr>
      <tr>
        <td>Login com campos vazios</td>
        <td>Sim</td>
        <td>Não</td>
        <td>Mensagem clara de erro</td>
      </tr>
      <tr>
        <td>Cadastro com campos vazios</td>
        <td>Sim</td>
        <td>Não</td>
        <td>Mensagem clara de erro</td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/ailujana">Ana Júlia</a></p>
  </font>

</div>


## Resultados

Com base nas simulações e observações realizadas, constatou-se que, apesar de o sistema identificar parte dos erros de entrada, as mensagens exibidas são genéricas ou inexistentes, e nenhuma sugestão de correção é apresentada ao usuário.

Esse cenário compromete significativamente a experiência de uso, sobretudo para usuários iniciantes, que dependem de feedback claro para compreender e resolver os problemas que encontram durante a navegação.

Além disso, a ausência de mensagens claras também impacta negativamente o ponto de vista da acessibilidade digital, dificultando o uso da aplicação por pessoas com deficiência cognitiva, baixa alfabetização ou dificuldades de leitura.

De acordo com os critérios definidos na [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas), a métrica M4 foi classificada como **"Insatisfatória" (pontuação ≤ 3)**, uma vez que:

- A taxa de detecção de erros foi parcial;

- Nenhuma mensagem exibida foi considerada clara ou específica;

- Não foram fornecidas sugestões de correção.

### Recomendação

A ausência de mensagens claras e sugestões de correção impacta negativamente a usabilidade do Agromart, especialmente em fluxos críticos como login, cadastro e envio de dados. Para mitigar esse problema, recomenda-se:

- Implementar validações em tempo real nos campos de entrada;

- Exibir mensagens de erro específicas e contextualizadas;

- Fornecer sugestões de correção diretamente nas mensagens (ex.: “Digite um CEP válido”);

- Utilizar elementos visuais como destaque em vermelho e ícones de aviso para reforçar o feedback.

A adoção dessas melhorias tende a aumentar a confiabilidade da aplicação, reduzir frustrações e fortalecer a autonomia do usuário ao lidar com erros.

## Referências Bibliográficas 

- [1] ISO/IEC 25010:2011 – Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE)

- [2] NIELSEN, Jakob. Heuristics for User Interface Design, 1995.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-----:|
|`1.0`|07/07/2025|Criação do documento| [Ana Júlia](https://github.com/ailujana) | [Weverton Rodrigues](https://github.com/vevetin) |
|`1.1`|07/07/2025|Melhoria da escrita|[Maria Clara](https://github.com/Oleari19)| - |
