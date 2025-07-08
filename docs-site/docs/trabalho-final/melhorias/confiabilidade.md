# Proposta de melhorias de confiabilidade

## Introdução

Esta documentação tem como objetivo a sintetização das propostas de melhorias e soluções identificadas para os problemas levantados quanto a qualidade da [confiabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/confiabilidade/confiabilidade-m1/) no AgroMart. 

## Melhorias propostas 

### M1 - Percentual de erros com mensagem clara e sem perda de dados

A métrica M1 investiga a exposição de erros dentro da aplicação, e se relaciona bem, com a métrica [M4](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m4/) de Usabilidade, com o respeito de cada subcaracterística. 

Sendo assim, a sugestação de melhoria implementada foi o aperfeiçoamento e correção realizado nas mensagens de erro presentes no prótotipo de alta fidelidade COLOCAR LINK, com a escolha de mensagens de erro claras, sem ambiguidade e termos técnicos e que sugiram sugestões de correção do erro, sempre que possível. 

Espera-se também que, sempre que possível, os desenvolvedores do AgroMart usem boas práticas de exposição de erros, podendo usar como estudo e guia materiais como o de Gassenferth [1].

### M2 - Percentual de requisitos que possuem testes automatizados associados

A métrica M2 investiga a relação de testes automatizados com os requisitos elicitados da aplicação. Percebe-se, com a análise da suíte de teste que, os testes automatizados cobrem, mais ou menos, 50% da aplicação.

Porém, notou-se a falta de testes automarizados para diversos requisitos com prioridade máxima para o sistema, o que é maléfico a confiabilidade. 

Dessa forma, é indicado sempre possuir e desenvolver testes, de preferência automatizados, para a análise e verificação de comportamento correto para todos os requisitos do AgroMart, e principalmente, para os de prioridade crítica.

### M3 - Percentual de requisitos com critérios de aceitação bem definidos

Já a métrica M2 investiga a qualidade dos critérios de aceitação de requisitos, em especial do das histórias de usuário. 

Dessa forma, a proposta de solução é a melhora na escrita de histórias de usuário, levando em consideração os principais conceitos para as construções das mesmas, como especificado na [avaliação](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/confiabilidade/confiabilidade-m3/). 

Espera-se profundidade e clareza dos critérios de aceitação propostos pelo AgroMart, afim de assegurar a confiabilidade e alinhamento do sistema com os requisitos elicitados. 

Um exemplo de melhoria, pode ser aplicado no critério de aceitação da US12: Adicionar ao carrinho, possui a seguinte estrutura: 

        Eu, como co-agricultor, desejo poder adicionar minhas compras em um carrinho.

        Critérios de Aceitação:
            - Deve estar logado.

Os critérios de aceitação melhorados seriam: 

        Critérios de Aceitação: 
            - O usuário deve estar autenticado no sistema (logado) para adicionar itens ao carrinho.

            - O botão "Adicionar ao carrinho" deve estar visível em todas as páginas de produto.

            - Ao clicar em "Adicionar ao carrinho", o item deve ser incluído no carrinho com a quantidade padrão de 1 unidade.

            - Se o item já estiver no carrinho, a ação deve aumentar a quantidade em 1, em vez de duplicar a entrada.

            - Uma notificação visual deve ser exibida confirmando a adição do item ao carrinho.

            - O carrinho deve ser atualizado de forma dinâmica, refletindo o número total de itens e o valor acumulado.

            - Caso ocorra algum erro durante a adição, uma mensagem de erro amigável deve ser exibida ao usuário sem recarregar a página.


## Bibliografia 

> \- ATLASSIAN. Acceptance Criteria Explained [+ Examples & Tips]. Disponível em: <https://www.atlassian.com/work-management/project-management/acceptance-criteria>. Acesso em: 08 de julho de 2025.

> \- Grupo Betty Snyder, T01, 2025. Medidas obtidas de Confiabilidade. Fisponível em: <https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/confiabilidade/confiabilidade-m1/>. Acesso em: 08 de julho de 2025.
‌
## Referências Bibliográficas

> [1] GASSENFERTH, Daniel. How to design better error messages • Centigrade GmbH. Disponível em: <https://www.centigrade.de/en/blog/how-to-design-better-error-messages/>. Acesso em: 08 de julho de 2025.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-----:|
|`1.0`|08/07/2025|Criação do documento| [Júlia Fortunato](https://github.com/julia-fortunato) | [Weverton Rodrigues](https://github.com/vevetin) |