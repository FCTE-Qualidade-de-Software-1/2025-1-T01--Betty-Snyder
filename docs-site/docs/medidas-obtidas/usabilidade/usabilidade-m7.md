# Usabilidade - M7: Percentual de compatibilidade com leitores de tela
## Introdução

Na presente execução da análide de usabilidade do Agromart, foi definida, durante a [Fase 2](https://fcte-qualidade-de-software-1.github.io/2025-1-T01--Betty-Snyder/gqm/gqm/#selecao-das-metricas) do projeto, métricas voltadas à avaliação da experiência do usuário com enfoque mobile-first. 
Esse documento tem como objetivo sintetizar os achados referentes à métrica M7 (Percentual de compatibilidade com leitores de tela), considerada essencial para avaliar a usabilidade do sistema em dispositivos móveis.

## Referencial teórico 

De acordo com as Diretrizes de Acessibilidade para Conteúdo Web (WCAG) [1], em sua versão 2.2, os leitores de tela são tecnologias assistivas essenciais para garantir o acesso de pessoas com deficiência visual aos conteúdos digitais. A compatibilidade com leitores de tela permite que esses usuários naveguem, compreendam e interajam com sistemas de forma autônoma, por meio da conversão do conteúdo visual em áudio.

A presença de suporte adequado a leitores de tela contribui significativamente para uma experiência de navegação mais inclusiva, fluida e eficiente, especialmente para pessoas com deficiência visual. Quando bem implementado, esse recurso permite que os usuários compreendam e interajam com a interface com autonomia e confiança. A qualidade da compatibilidade envolve a análise precisa de labels descritivos, a clareza dos textos apresentados ao leitor de tela e a consistência na ordem e padrão da leitura, garantindo que a interação siga uma lógica compreensível e alinhada com a estrutura da interface.

## Análise

A análise foi realizada de forma exploratória no aplicativo mobile do AgroMart, de forma a navegar com a utilização de um leitor de telas, em específico, o TalkBack no Android. Dessa forma, a concepção foi fazer a navegação em todo o aplicativo disponível.

## Execução da análise

A execução da análise foi feita levando em consideração as principais funcionalidades de um leitor de telas: análise precisa de labels descritivos, clareza dos textos apresentados ao leitor de tela e a consistência na ordem e padrão da leitura. 

Dessa forma, a Tabela 1 apresenta a análise realizada para a M7 de Usabilidade. 

<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 1 – Avaliação da execução do leitor de telas TalkBack no aplicativo AgroMart</b></p>
  </font>

  <table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>Execução do leitor de telas</th>
        <th>Realiza de forma correta?</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Análise precisa de labels descritivos</td>
        <td>Parcialmente</td>
      </tr>
      <tr>
        <td>Clareza dos textos apresentados ao leitor de tela</td>
        <td>Sim</td>
      </tr>
      <tr>
        <td>Consistência na ordem e padrão da leitura</td>
        <td>Sim</td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/julia-fortunato" target="_blank">Júlia Fortunato</a></p>
  </font>

</div>


## Resultados

Após a execução da avaliação, é possível verificar o percentual de compatibilidade do AgroMart com o leitor de telas utilizado, o TalkBack do Android. O resultado está presente na Tabela 2. É válido enfatizar que espera-se o mesmo comportamentos em todos os leitores de telas, uma vez que, para realizar a leitura, é utilizado o código-fonte da aplicação.

<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 2 – Porcentagem de conformidade do leitor de telas com critérios de acessibilidade</b></p>
  </font>

  <table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>Total de critérios avaliados</th>
        <th>Critérios plenamente atendidos</th>
        <th>Critérios parcialmente atendidos</th>
        <th>Critérios não atendidos</th>
        <th>Porcentagem de conformidade plena</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>3</b></td>
        <td><b>2</b></td>
        <td><b>1</b></td>
        <td><b>0</b></td>
        <td><b>66,67%</b></td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/julia-fortunato" target="_blank">Júlia Fortunato</a></p>
  </font>

</div>

Pode-se perceber que o AgroMart possui boa compatibilidade com leitores de telas, com um percentual de 66,67%. Dessa forma, o nível de cobertura identificado para a métrica é considerado **Bom (pontuação 7)**. O arredondamento se dá pelo motivo da conformidade estar bem mais positiva do que negativa.

O erro que foi encontrado na análise de labels se dá na tela de edição/cadastro de endereço, no qual o leitor de telas não é capaz de realizar a leitura de uma dropbox na qual são identificadas as RAs do Distrito Federal, o que facilmente pode ser substituído por uma outra prática de programação, como uma simples entrada para o usuário informar a sua RA de residência. 

Apesar disso, o sistema se comporta de forma adequada nas demais áreas testadas, com leitura coerente dos textos, navegação consistente e identificação correta de elementos interativos, como botões e campos de formulário. Esse resultado demonstra um bom nível de atenção à compatibilidade com leitores de tela. Correções pontuais, como a implementação de labels acessíveis em componentes específicos, podem elevar ainda mais a qualidade e a inclusão no uso do aplicativo.


## Bibliografia

> \- Mobile Client do AgroMart. Disponível em: <https://github.com/AgroMart/mobile-client>. Acesso em: 07 de julho de 2025.

## Referências Bibliográficas

> W3C. Diretrizes de Acessibilidade para Conteúdo Web (WCAG) 2.2. Disponível em: <https://www.w3c.br/traducoes/wcag/wcag22-pt-BR/>. Acesso em: 7 de julho de 2025.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/07/2025|Criação do documento| [Ana Júlia](https://github.com/ailujana) |[Júlia Fortunato](https://github.com/julia-fortunato)|
|`1.1`|07/07/2025|Adição da análise| [Júlia Fortunato](https://github.com/julia-fortunato) |[Weverton Rodrigues](https://github.com/vevetin)|