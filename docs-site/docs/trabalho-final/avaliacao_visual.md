# Análise de Telas da Aplicação AgroMart - Consistência Visual e de Navegação

**Feito por:** Weverton Rodrigues da Costa Silva
**Matrícula:** 221022767

## Metodologia Utilizada

A avaliação foi conduzida com base em uma abordagem observacional e analítica, com foco na identificação de inconsistências visuais e de navegação. Essa análise teve como objetivo complementar as avaliações realizadas por outros integrantes da equipe, voltadas para heurísticas de usabilidade e tecnologias assistivas.

Foram utilizados os seguintes recursos metodológicos:

- Checklists estruturados, com base nos princípios de design apresentados por Barbosa et al. (2021), especialmente no Capítulo 10 (Princípios e Diretrizes) e no Capítulo 12 (Métodos de Avaliação);

- Simulação de fluxos de navegação, com o intuito de observar padrões e comportamentos de transição entre telas;

- Critérios inspirados nas heurísticas de Nielsen e diretrizes de padronização, com ênfase nos princípios de consistência, visibilidade e reconhecimento.

## Checklist – Consistência Visual

A avaliação da consistência visual teve como objetivo verificar se os elementos gráficos do sistema seguem padrões coerentes ao longo de sua interface. A padronização de cores, tipografia, ícones e alinhamento é essencial para promover previsibilidade e facilitar o aprendizado da interface pelo usuário. Os critérios abaixo foram elaborados com base nos princípios descritos por Barbosa et al. (2021), especialmente nas seções sobre padronização visual e guias de estilo (Cap. 10.2.4 e 10.5).

| Critério                                                        | Avaliação | Observações |
| --------------------------------------------------------------- | --------------- | ----------- |
| Uso consistente de cores nos elementos com mesma função         |                 |             |
| Ícones reutilizados com o mesmo significado em toda a interface |                 |             |
| Fontes e tamanhos padronizados por tipo de informação           |                 |             |
| Layout e alinhamento seguem uma lógica de grade visual          |                 |             |
| Elementos com funções distintas têm aparência diferenciada      |                 |             |
| Contraste adequado entre texto e fundo                          |                 |             |


## Checklist – Consistência de Navegação

Esta seção avalia a consistência dos mecanismos de navegação, considerando a previsibilidade dos fluxos, a organização dos menus e a clareza das opções de retorno. De acordo com Barbosa et al. (2021), interfaces bem estruturadas devem manter uma lógica de navegação constante, permitindo que os usuários compreendam facilmente onde estão e como podem retornar ou avançar no sistema. Os critérios a seguir estão fundamentados nos princípios de visibilidade e padronização (Cap. 10.2.4 e 10.2.7).

| Critério                                                                      | Avaliação | Observações |
| ----------------------------------------------------------------------------- | --------------- | ----------- |
| Menu de navegação visível e acessível                                         |                 |             |
| Botões de navegação posicionados de forma consistente                         |                 |             |
| Fluxos de tarefas seguem padrões previsíveis                                  |                 |             |
| Feedback visual sobre localização do usuário (breadcrumbs, destaque de seção) |                 |             |
| Possibilidade clara de retorno (botões de “voltar”, “início”, etc.)           |                 |             |

## Heurísticas de Nielsen (Relacionadas)

As heurísticas de usabilidade propostas por Jakob Nielsen foram utilizadas como referência adicional na avaliação. Nesta análise, foram consideradas aquelas mais relevantes para os aspectos de consistência e navegação, tais como: “consistência e padronização”, “visibilidade do estado do sistema” e “reconhecimento em vez de memorização”. Essas diretrizes, discutidas por Barbosa et al. (2021) no Capítulo 12, contribuem para detectar falhas que dificultam a previsibilidade da interface e a fluidez da experiência de uso.

| Heurística                           | Avaliação | Problemas Identificados |
| ------------------------------------ | --------------- | ----------------------- |
| Consistência e Padronização          |                 |                         |
| Visibilidade do estado do sistema    |                 |                         |
| Correspondência com o mundo real     |                 |                         |
| Reconhecimento em vez de memorização |                 |                         |
| Estética e design minimalista        |                 |                         |

## Resultados e Evidências Visuais

Durante a aplicação dos checklists e a navegação pelas interfaces do sistema, foram identificadas inconsistências que impactam negativamente a usabilidade. Abaixo, as ocorrências estão organizadas por tela ou fluxo, com descrição do problema, impacto percebido, classificação de severidade e indicação da existência de evidência visual.

### Tela de Login

Problema identificado: O botão de login apresenta desalinhamento lateral em relação ao campo de senha. Além disso, sua cor e estilo diferem dos botões equivalentes em outras telas (ex: "Salvar", "Entrar").

Impacto: Pode causar confusão visual e transmitir descuido na construção da interface, prejudicando a percepção de profissionalismo logo no primeiro contato com o sistema.

Severidade: Média

Print Anexado: 

...

## Interpretação dos Resultados com Base na Escala de Pontuação

Para tornar a avaliação comparável e objetiva, foi aplicada a escala de pontuação definida pela equipe na [Fase 2 - Especificar a avaliação].

Com base na aplicação dos checklists, nas observações sistemáticas e na análise das evidências visuais coletadas, foram atribuídas as seguintes pontuações, de acordo com a escala definida pela equipe:

    Consistência Visual: 6 (Regular)

    Consistência de Navegação: 5 (Regular)

**Consistência Visual – Nota 6 (Regular)**

A nota atribuída reflete a presença de uma base visual minimamente padronizada, mas com deficiências relevantes que afetam a coerência estética da interface. Entre os pontos positivos, destacam-se o uso consistente da paleta de cores e a boa organização espacial na tela inicial. No entanto, foram observadas falhas como:

- Variações no estilo e significado de ícones para a mesma função, o que prejudica o reconhecimento visual imediato;

- Ausência de diferenciação clara entre botões com funções distintas, como "Salvar" e "Excluir", que apresentam aparência muito semelhante;

- Pequenas incongruências no alinhamento de elementos, especialmente em formulários e telas de login.

Esses aspectos comprometem a previsibilidade da interface e podem gerar confusão ao usuário, especialmente durante as primeiras interações. A padronização de componentes visuais e a adoção de um guia de estilo são medidas recomendadas para elevar esse aspecto ao nível “Bom” ou “Excelente”.

**Consistência de Navegação – Nota 5 (Regular)**

A navegação apresenta uma estrutura funcional básica, com alguns elementos positivos, como a presença de breadcrumbs em telas secundárias e o uso de uma barra de menu lateral. Entretanto, a pontuação reflete a existência de falhas que dificultam a experiência do usuário, incluindo:

- Ausência de mecanismos de retorno (como botão "voltar" ou links para a página inicial) em algumas telas críticas, como relatórios ou configurações;

- Inconsistência no posicionamento de botões de navegação, que aparecem em locais diferentes dependendo da tela;

- Padrões de fluxo nem sempre são previsíveis, o que exige maior esforço cognitivo por parte do usuário para se orientar.

Esses problemas afetam principalmente a fluidez e o senso de controle durante a navegação. Para melhorar esse aspecto, recomenda-se a revisão da arquitetura de informação, com foco na uniformização da navegação e na inserção de elementos de feedback de localização e transição entre telas.

## Conclusão e Recomendações

A avaliação evidenciou [x] inconsistências relevantes na interface, principalmente nos aspectos de [ex: uso de ícones e cores]. As principais recomendações incluem:

- Padronizar uso de cores e ícones em todas as seções;

- Garantir consistência nos fluxos de navegação (especialmente em menus e botões);

- Adotar um guia de estilo visual para futuras versões.

A análise seguiu os critérios propostos por Barbosa et al. (2021) e contribui para uma visão mais ampla da qualidade de uso do sistema, reforçando a importância da coerência visual e estrutural para a usabilidade.