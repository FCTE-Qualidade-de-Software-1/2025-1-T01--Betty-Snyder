# Usabilidade - M3: Percentual de acertos na identificação de botões.

## Introdução

Na presente execução da análise de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, métricas voltadas à avaliação da experiência do usuário com enfoque mobile-first.  
Esse documento tem como objetivo sintetizar os achados referentes à métrica **M3 (Percentual de acertos na identificação de botões)**, considerada essencial para avaliar a usabilidade do sistema em dispositivos móveis.

## Referencial teórico 

Segundo a norma ISO/IEC 25010 [1], a usabilidade é composta por atributos como compreensibilidade, operabilidade e atratividade. A correta identificação dos botões é diretamente ligada à **compreensibilidade e intuitividade**, permitindo ao usuário entender claramente o que cada ação realiza, sem causar confusões ou erros.

As heurísticas de Nielsen [2], especialmente a **H6 (Reconhecimento em vez de memorização)**, também apoiam a ideia de que elementos de interface devem ser facilmente identificáveis e compreensíveis com base no design e rótulos visuais.

## Análise

Foram selecionados **cinco botões principais** da interface:

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

Durante os testes individuais, os participantes foram solicitados a identificar a funcionalidade de cada botão com base apenas em seu **ícone, texto e contexto visual**.

Critério de acerto: botão foi corretamente identificado na primeira tentativa **sem ajuda externa**.

## Execução da análise

Foram considerados os resultados de três representantes da equipe representando o público-alvo. A análise foi feita manualmente com base em observação direta e perguntas simples como:  
> “O que você espera que aconteça ao clicar nesse botão?”

| Botão                 | Acertos | Tentativas | Percentual (%) |
|-----------------------|---------|------------|----------------|
| Adicionar             | 0       | 3          | 0%          |
| Salvar                | 3       | 3          | 100%          |
| Realizar              | 0       | 3          | 0%          |
| Realizar Pagamento    | 3       | 3          | 100%           |
| Escolha sua CSA       | 3       | 3          | 100%          |
| Utilizar esta CSA     | 3       | 3          | 100%           |
| Procurar outra CSA    | 3       | 3          | 100%           |
| Voltar                | 3       | 3          | 100%           |
| Logar                 | 3       | 3          | 100%           |
| Home                  | 3       | 3          | 100%           |
| Busca                 | 3       | 3          | 100%           |
| Histórico             | 0       | 3          | 0%           |
| Perfil                | 3       | 3          | 100%           |
| Meus dados            | 3       | 3          | 100%          |
| Meus endereços        | 3       | 3          | 100%          |
| Meus planos           | 3       | 3          | 100%          |
| Sair                  | 3       | 3          | 100%           |
| Notificações          | 3       | 3          | 100%          |

**Média geral de acertos:** **~83,3%**

## Resultados

A análise mostrou **boa identificação geral** dos botões, com exceção de alguns casos de incerteza nos botões "Adicionar" e "Realizar" e "Histórico", devido à falta de reforço textual ou iconografia ambígua.
Apesar dos botões na tela de início (Home, Busca, Perfil e Histórico) serem óbvios para nós,equipe de desenvolvedores, a equipe concordou em colocar, no protótipo, a palavra assoaciativa da funcionalidade de cada botão.

- **Métrica considerada "Boa"** (meta ≥ 70%)
- Sugestões de melhoria:
  - Adicionar **legendas textuais** curtas para botões que usam apenas ícones;
  - Usar cores e formatos consistentes nos botões de ação.

## Referências Bibliográficas

- [1] ISO/IEC 25010:2011 – Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE)
- [2] NIELSEN, Jakob. *Heuristics for User Interface Design*, 1995.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-----:|
|`1.0`|07/07/2025|Criação do documento| [Ana Júlia](https://github.com/ailujana) | — |
