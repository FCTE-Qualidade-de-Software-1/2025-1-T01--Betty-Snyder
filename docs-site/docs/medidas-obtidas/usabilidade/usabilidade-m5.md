# Usabilidade - M5: Taxa de recuperação após erro

## Introdução

Na presente execução da análise de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, a métrica M5 (Taxa de recuperação após erro), com o objetivo de avaliar a capacidade do sistema de permitir que o usuário retome seu fluxo de uso normalmente após a ocorrência de uma falha, com foco na experiência em ambientes mobile-first.

## Referencial teórico

Segundo a norma ISO/IEC 25010<sup>[1]</sup>, a qualidade em uso inclui atributos como recuperabilidade, que diz respeito à capacidade de o sistema auxiliar o usuário na retomada de ações após um erro, sem que haja perda de progresso ou dados inseridos.

As heurísticas de Nielsen<sup>[2]</sup>, em especial a H9 – Ajuda ao diagnóstico e recuperação de erros, reforçam que sistemas eficazes devem:

- Apontar claramente o erro ocorrido;

- Orientar o usuário sobre como corrigi-lo;

- Minimizar perdas de dados ou necessidade de reinício.

Essas práticas contribuem para reduzir a frustração e aumentar a confiança do usuário na aplicação.

## Análise

Durante os testes simulados, foram inseridos erros propositalmente nos seguintes contextos:

- Cadastro com campos obrigatórios em branco;

- Inserção de CEP inválido;

- Login com dados incompletos;

- Tentativa de avançar etapas sem preenchimento prévio.

Esses testes, também descritos na análise da métrica M4, buscaram verificar se o sistema permite que o usuário:

- Corrija o erro sem reiniciar o processo;

- Mantenha os dados já inseridos;

- Receba orientações claras sobre o problema e como solucioná-lo.

## Execução da análise

Os testes foram conduzidos por membros da equipe em ambiente controlado com foco nos fluxos de cadastro, login e pedidos. A Tabela 1 apresenta os resultados dos testes com base na observação direta da equipe:

<div style="text-align: center">
  <font size="3">
    <p><b>Tabela 1 – Recuperação após erro em diferentes cenários</b></p>
  </font>

  <table border="1" style="margin: 0 auto;">
    <thead>
      <tr>
        <th>Cenário</th>
        <th>Erro detectado?</th>
        <th>Retomada possível?</th>
        <th>Perda de dados?</th>
        <th>Retorno claro?</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>CEP inválido</td>
        <td>Sim</td>
        <td>Sim</td>
        <td>Não</td>
        <td>Não</td>
      </tr>
      <tr>
        <td>Cadastro com campos obrigatórios vazios</td>
        <td>Sim</td>
        <td>Sim</td>
        <td>Não, pois os campos estavam vazios</td>
        <td>Não</td>
      </tr>
      <tr>
        <td>Login com campos incompletos</td>
        <td>Sim</td>
        <td>Sim</td>
        <td>Não</td>
        <td>Não</td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/ailujana">Ana Júlia</a></p>
  </font>
</div>


## Resultados

Com base nos testes realizados, constatou-se que:

- 100% dos erros foram detectados corretamente pelo sistema;

- Todos os fluxos permitiram a retomada da tarefa sem perda de dados;

- Nenhum dos casos apresentou mensagens claras ou orientações de correção para o usuário.

Os achados demonstram que, embora o sistema ofereça boa tolerância a erros do ponto de vista técnico, ainda carece de suporte comunicacional adequado para orientar os usuários na recuperação das falhas.

Segundo os critérios definidos na Fase 2, a métrica M5 apresenta resultado mediano:

- Aspecto técnico: satisfatório (retomada sem reinício ou perda de dados);

- Aspecto comunicacional: insatisfatório (ausência de mensagens claras ou sugestões).

Dessa forma, a pontuação atribuída à métrica é **5 (Regular)**.

### Recomendação

A análise da métrica M5 mostra que o sistema Agromart possui uma boa tolerância técnica a erros, permitindo ao usuário continuar suas ações mesmo após falhas de entrada. No entanto, a ausência de feedbacks informativos compromete a compreensão e autonomia do usuário no processo de recuperação.
Recomendações:

- Exibir mensagens de erro específicas, redigidas em linguagem clara e objetiva, com orientações diretas de correção;

- Destacar os campos com erro visualmente;

- Manter os dados previamente inseridos em todos os formulários;

- Adotar ícones e cores padronizadas para alertas, seguindo diretrizes de design de interface.

## Referências Bibliográficas

- [1] ISO/IEC 25010:2011 – Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE)

- [2] NIELSEN, Jakob. Heuristics for User Interface Design, 1995

## Histórico de Versões

| Versão | Data       | Descrição            | Autor                                            | Revisor |
|--------|------------|----------------------|--------------------------------------------------|---------|
| 1.0    | 07/07/2025 | Criação do documento | [Ana Júlia](https://github.com/ailujana)         | [Weverton Rodrigues](https://github.com/vevetin)  |
|`1.1`|07/07/2025|Pequena melhoria da escrita|[Maria Clara](https://github.com/Oleari19)| [Maurício Ferreira](https://github.com/mauricio-araujoo) |