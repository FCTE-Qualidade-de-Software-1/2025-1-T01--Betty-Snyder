# Usabilidade - M4: Percentual de erros com sugestões de correção e mensagens claras.

## Introdução

Na presente execução da análise de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, métricas voltadas à avaliação da experiência do usuário com enfoque mobile-first.  
Esse documento tem como objetivo sintetizar os achados referentes à métrica **M4 (Percentual de erros com sugestões de correção e mensagens claras)**, considerada essencial para avaliar a usabilidade do sistema em dispositivos móveis.

## Referencial teórico 

Segundo a norma ISO/IEC 25010 [1], um dos atributos centrais da qualidade em uso é a capacidade de prevenção e recuperação de erros, o que se relaciona com a clareza das mensagens exibidas ao usuário e a orientação para resolução de problemas.

Na mesma linha, as heurísticas de Nielsen [2], especialmente a **H5 – Prevenção de erros** e a **H9 – Ajuda ao diagnóstico e recuperação de erros**, reforçam que sistemas eficazes devem:

- Evitar que erros aconteçam;
- Ajudar o usuário a compreender o erro;
- Oferecer orientações claras para corrigi-lo.

## Análise

Durante os testes de usabilidade, foram analisadas as telas de cadastro de endereço, finalização de pedido e login.Foram observados os seguintes comportamentos:

- Alguns campos (como CEP e endereço) não possuíam **validação clara**.
- Ausência de **mensagens de erro específicas**, como "CEP inválido" ou "campo obrigatório".
- Nenhuma sugestão automatizada de correção foi apresentada.

No entanto, o sistema também **não travava ou apresentava falhas críticas**, o que demonstra certa tolerância a falhas.

## Execução da análise

A equipe simulou erros em diferentes fluxos:

- Inserção de CEP inválido
- Campos obrigatórios deixados em branco

| Cenário                                   | Erro detectado pelo sistema? | Mensagem clara? | Sugestão de correção? |
|-------------------------------------------|-------------------------------|------------------|------------------------|
| CEP inválido                              | Não                           | Não               |           Mensagem clara de erro         |                   |
| Cadastrar endereço com campos vazios | Sim                            | Não             | Mensagem clara de erro                    |
| Login com campos vazios           | Sim                           | Não              | Mensagem clara do erro   |
| Cadastro com campos vazios           | Sim                           | Não              | Mensagem clara do erro   |

## Resultados


## Referências Bibliográficas 

- [1] ISO/IEC 25010:2011 – Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE)
- [2] NIELSEN, Jakob. *Heuristics for User Interface Design*, 1995.



## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-----:|
|`1.0`|07/07/2025|Criação do documento| [Ana Júlia](https://github.com/ailujana) | — |
