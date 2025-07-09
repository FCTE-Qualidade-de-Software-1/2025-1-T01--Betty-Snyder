# Proposta de melhorias de usabilidade

## Introdução

Esta documentação tem como objetivo a sintetização das propostas de melhorias e soluções identificadas para os problemas levantados quanto à qualidade da [usabilidade](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m1/) no AgroMart.

A avaliação revelou uma percepção geral moderada da usabilidade da aplicação, com destaque para inconsistências visuais, barreiras de acessibilidade e fluxos de navegação que exigem esforço cognitivo elevado dos usuários. Para mitigar esses problemas, foi desenvolvido um [protótipo de alta fidelidade](https://www.figma.com/design/UnJYeq1K1Ypd1YQNo7DCDx/AgroMart?node-id=0-1&p=f&t=qPLUJHIEIK80vEAl-0) com foco na resolução dos pontos identificados.

## Melhorias propostas

### M1 – Tempo médio de execução de tarefas via interação por toque

Identificou-se que o tempo médio para completar tarefas básicas foi elevado, indicando dificuldades de navegação. A proposta é otimizar o fluxo das tarefas mais comuns, reduzindo o número de cliques e organizando melhor os botões de ação. Além disso, foram implementadas melhorias no protótipo de alta fidelidade, com interfaces mais diretas e intuitivas.  

**Solução proposta:** Otimizar os fluxos das tarefas mais recorrentes, reduzindo etapas e agrupando ações semelhantes. O novo protótipo adota posicionamentos mais intuitivos de botões e estruturas visuais mais claras.


### M2 – Taxa de sucesso de novos usuários em tarefas básicas

A taxa de sucesso de novos usuários foi considerada regular. Para isso, foi proposto incluir um onboarding interativo que guie o usuário pelas principais funcionalidades do app nas primeiras interações. Também foram sugeridas mensagens informativas e animações visuais discretas para reforçar a aprendizagem.

**Solução proposta:** Inserção de um onboarding interativo, que apresente gradualmente as funções principais da aplicação, com textos explicativos, dicas visuais e interações guiadas.


### M3 – Percentual de acertos na identificação de botões

Foi observado que alguns ícones não estavam claros para os usuários. Assim, o novo protótipo substitui ícones ambíguos por representações mais reconhecíveis e com rótulos de texto visíveis, conforme boas práticas de design universal.

**Solução proposta:** Substituição de ícones ambíguos por ícones padronizados e universais, acompanhados de rótulos textuais para reforçar a compreensão de cada ação.



### M4 – Percentual de erros com sugestões de correção e mensagens claras

Usuários relataram dificuldades na compreensão de mensagens de erro. A proposta é padronizar mensagens claras, sem jargões técnicos, sempre com uma sugestão de correção. As mensagens foram reformuladas no protótipo com foco na empatia e orientação.

**Solução proposta:** Reformulação completa das mensagens de erro, utilizando linguagem acessível, sem jargões, com orientação objetiva e sugestões de correção contextualizadas ao erro cometido.


### M5 – Taxa de recuperação após erro

Embora bem avaliada, a estética ainda recebeu sugestões de melhorias. Foram adotadas paletas de cores com maior contraste, fontes mais legíveis e espaçamentos mais bem distribuídos, respeitando o design responsivo.

**Solução proposta:** Tornar a interface mais leve, objetiva e agradável visualmente, com feedbacks positivos e consistentes ao longo das interações, além de reduzir passos desnecessários.


### M6 – Nota média atribuída pelos usuários em questionário sobre a interface da aplicação

A nota média atribuída à interface foi moderada. Para melhorar essa percepção, o novo design propõe simplificação visual, redução de ruídos gráficos e maior consistência nos componentes.

**Solução proposta:** Revisar aspectos visuais da aplicação, incluindo tipografia, alinhamento, paleta de cores e hierarquia visual. O novo design valoriza clareza, legibilidade e consistência entre as telas.


### M7 – Percentual de compatibilidade com leitores de tela

A análise indicou um bom nível de compatibilidade (66,67%) com leitores de tela, mas com falhas em labels em alguns campos. A proposta é revisar todos os campos da aplicação garantindo uso adequado de `aria-labels`, descrições alternativas e ordem de leitura semântica no código.

**Solução proposta:** Adição de descrições alternativas em todos os elementos gráficos, uso correto de tags semânticas HTML e atributos `aria-label`, garantindo compatibilidade com tecnologias assistivas.


### M8 – Percentual de conformidade com as principais funcionalidades de acessibilidade

O sistema não apresentou nenhuma das quatro funcionalidades básicas analisadas (contraste alto, redimensionamento de texto, ajuda contextual e suporte a Libras). Portanto, é fortemente recomendada a inclusão dessas funcionalidades no próximo ciclo de desenvolvimento. Isso inclui:

- Modo de alto contraste;
- Capacidade de redimensionar textos com gestos do sistema;
- Instruções contextuais acessíveis;
- Integração com soluções de tradução em Libras, como VLibras.

**Solução proposta:** Implementar recursos de acessibilidade como: modo de alto contraste, zoom adaptável sem quebra de layout, orientações contextuais e integração com o VLibras para acessibilidade em Libras.


## Conclusão

As melhorias propostas estão refletidas no novo protótipo desenvolvido no Figma, com base em todas as métricas analisadas. Elas visam tornar o AgroMart mais intuitivo, acessível e eficiente para todos os públicos, promovendo inclusão digital e usabilidade centrada no usuário.

## Link para o protótipo com melhorias

> [Clique aqui para acessar o protótipo no Figma](https://www.figma.com/design/UnJYeq1K1Ypd1YQNo7DCDx/AgroMart?node-id=0-1&p=f&t=8OvhyE5JmOqflUdX-0)

> [Clique aqui para acessar o fluxo completo do protótipo no Figma](https://www.figma.com/proto/UnJYeq1K1Ypd1YQNo7DCDx/AgroMart?node-id=1-6&p=f&t=8OvhyE5JmOqflUdX-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A6)

## Bibliografia 

> - Grupo Betty Snyder, T01, 2025. Medidas obtidas de Usabilidade. Disponível em: <https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/medidas-obtidas/usabilidade/usabilidade-m1/>. Acesso em: 08 de julho de 2025.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-----:|
|`1.0`|08/07/2025|Criação do documento| [Júlia Fortunato](https://github.com/julia-fortunato) | [Weverton Rodrigues](https://github.com/vevetin) |
|`1.1`|08/07/2025|Arrumando links| [Maria Clara](https://github.com/Oleari19) | [Ana Júlia](https://github.com/ailujana) |
