# Usabilidade - M8: Percentual de conformidade com as principais funcionalidades de acessibilidade

## Introdução

Na presente execução da análise de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, métricas voltadas à avaliação da experiência do usuário com foco na verificação da acessibilidade da interface em dispositivos móveis.

Este documento sintetiza os achados relacionados à métrica M8 (Percentual de conformidade com as principais funcionalidades de acessibilidade), considerada essencial para garantir que o sistema atenda usuários com diferentes tipos de limitações físicas, sensoriais ou cognitivas.

## Referencial teórico 

As Diretrizes de Acessibilidade para Conteúdo Web (WCAG 2.1)<sup>[1]</sup>, mantida pela W3C, estabelecem princípios amplamente adotados para garantir acessibilidade, como:

- Perceptível: disponibilizar alternativas textuais para conteúdo não textual, usar contraste adequado e elementos redimensionáveis;

- Operável: permitir navegação por teclado, fornecer tempo suficiente para leitura/interação e evitar conteúdos que possam causar crises epilépticas;

- Compreensível: tornar o conteúdo legível e previsível, com instruções claras;

- Robusto: compatibilidade com tecnologias assistivas, como leitores de tela e suporte à língua de sinais digital.

Além disso, o Material Design 3<sup>[2]</sup>, mantido pela Google, também fornece orientações práticas para o desenvolvimento de interfaces acessíveis, incluindo:

- Suporte a modo de alto contraste;

- Adequação de tamanho mínimo de texto e botões;

- Uso consistente de cores e ícones com significados reconhecíveis;

- Práticas de design responsivo que favorecem a leitura e navegação em telas menores.

Essas diretrizes funcionam como base para avaliar a conformidade do sistema Agromart em relação a funcionalidades que favoreçam o uso por pessoas com deficiências visuais, motoras e cognitivas, além de usuários em contextos de uso restrito.

## Análise

A avaliação foi conduzida por meio de inspeção exploratória do aplicativo mobile AgroMart, com foco na identificação das funcionalidades de acessibilidade amplamente recomendadas por diretrizes como o WCAG 2.2 <sup>[1]</sup> e o Material Design 3 <sup>[2]</sup>.

## Execução da análise

Na Tabela 1, está documentada a execução da análise da verificação da existência ou não das principais funcionalidades de acessibilidade 

<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 1 – Conformidade do AgroMart com as principais ferramentas de acessibilidade digital</b></p>
  </font>

  <table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>Ferramenta</th>
        <th>Conformidade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Alto contraste</td>
        <td>Não possui</td>
      </tr>
      <tr>
        <td>Redimencionamento de texto</td>
        <td>Não possui</td>
      </tr>
      <tr>
        <td>Formatação de ajuda</td>
        <td>Não possui</td>
      </tr>
      <tr>
        <td>Suporte a língua de sinais</td>
        <td>Não possui</td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/julia-fortunato" target="_blank">Júlia Fortunato</a> e <a href="https://github.com/vevetin" target="_blank">Weverton Rodrigues</a></p>
  </font>

</div>

## Resultados

De acordo com os resultados indicados na Tabela 2, nenhuma das funcionalidades de acessibilidade analisadas foi identificada no aplicativo AgroMart, resultando em uma porcentagem de conformidade igual a 0%. Essa ausência de recursos essenciais evidencia uma baixa preocupação e conformidade com a inclusão digital, o que torna a aplicação pouco acessível para pessoas com deficiência visual, auditiva ou com dificuldades cognitivas.


<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 2 – Porcentagem de conformidade do AgroMart com as principais funcionalidades de acessibilidade digital</b></p>
  </font>

  <table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>Total de funcionalidades avaliadas</th>
        <th>Funcionalidades em conformidade</th>
        <th>Porcentagem de conformidade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>4</b></td>
        <td><b>0</b></td>
        <td><b>0%</b></td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/julia-fortunato" target="_blank">Júlia Fortunato</a> e <a href="https://github.com/vevetin" target="_blank">Weverton Rodrigues</a></p>
  </font>

</div>

A inexistência de funcionalidades como alto contraste, redimensionamento de texto, formatação de ajuda contextual e suporte a língua de sinais compromete seriamente a usabilidade da aplicação por públicos com necessidades específicas. Isso fere diretamente princípios fundamentais de acessibilidade digital definidos em diretrizes internacionais como as WCAG <sup>[1]</sup>, além de contrariar os valores de design centrado no usuário.

Portanto, o nível de cobertura identificado para a métrica considerada **insatisfatória (pontuação 0)**, demonstrando a necessidade imediata de melhorias na arquitetura da interface e nos mecanismos de suporte à acessibilidade digital. Tais mudanças são essenciais para garantir que o AgroMart se torne uma plataforma verdadeiramente inclusiva a todos os públicos.

## Bibliografia

> \- Mobile Client do AgroMart. Disponível em: <https://github.com/AgroMart/mobile-client>. Acesso em: 07 de julho de 2025.

## Referências Bibliográficas

- [1] W3C. Diretrizes de Acessibilidade para Conteúdo Web (WCAG) 2.2. Disponível em: <https://www.w3c.br/traducoes/wcag/wcag22-pt-BR/>. Acesso em: 7 de julho de 2025.

- [2] GOOGLE. Material Design 3: Accessibility. Disponível em: https://m3.material.io/foundations/designing/overview. Acesso em: 07 de julho de 2025.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/07/2025|Criação do documento| [Júlia Fortunato](https://github.com/julia-fortunato) <br> [Weverton Rodrigues](https://github.com/vevetin) | [Maurício Ferreira](https://github.com/mauricio-araujoo) |
|`1.2`|07/07/2025|Pequena melhoria da escrita|[Maria Clara](https://github.com/Oleari19)| [Maurício Ferreira](https://github.com/mauricio-araujoo) |
