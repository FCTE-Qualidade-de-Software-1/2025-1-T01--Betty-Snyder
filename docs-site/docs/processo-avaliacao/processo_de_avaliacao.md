## Contexto de Trabalho 

Este trabalho foi elaborado e desenvolvido no contexto da disciplina de Qualidade de Software, cujo objetivo é proporcionar aos estudantes a compreensão e a aplicação de técnicas, normas e práticas que assegurem a qualidade de produtos e processos de software ao longo de seu ciclo de vida. Como parte das atividades da disciplina, foi proposta a realização de uma análise crítica da qualidade de uma aplicação real, considerando aspectos de qualidade como usabilidade, confiabilidade, segurança, portabilidade, dentre outros.

## Aplicação Escolhida

O software avaliado neste trabalho é o **AgroMart <sup>[1]</sup>** , uma plataforma tecnológica desenvolvida durante uma hackathon na UnB-FCTE (Universidade de Brasília - Faculdade de Ciências e Tecnologias em Engenharia) em 2020, com o objetivo de apoiar a agricultura familiar por meio da conexão entre pequenos produtores e consumidores. Trata-se de uma plataforma híbrida, composta por uma interface web voltada aos produtores e um aplicativo móvel multiplataforma destinado aos consumidores. O **domínio de aplicação** do AgroMart abrange temas como agricultura familiar, comércio digital, inclusão social e consumo sustentável.

Apesar de ter funcionalidades voltadas para atividades comerciais (como venda de produtos e conexão entre produtores e consumidores), o AgroMart **não foi concebido como um software comercial no sentido tradicional** da classificação de Pressman, uma vez que foi desenvolvido em ambiente acadêmico, com foco em impacto social e sem fins lucrativos.

No entanto, de acordo com a norma IEEE 1062, o AgroMart pode ser classificado como um **COTS (Commercial Off-The-Shelf Software)**, pois é um produto padronizado, voltado a múltiplos usuários e disponibilizado como uma solução genérica, sem personalizações específicas para clientes individuais.

O **objetivo estratégico da plataforma** é se consolidar como referência em qualidade e inovação tecnológica no segmento agrícola, respondendo de forma robusta, segura e adaptável às demandas desse setor em constante transformação.

Por fim, **avaliação da qualidade** tem como objetivos principais identificar e priorizar as características mais relevantes para o seu público-alvo; orientar ações de melhoria contínua no sistema; e assegurar que o produto esteja alinhado às normas e boas práticas reconhecidas internacionalmente para qualidade de software.

## Classificação e Ênfase das Características de Qualidade

Nesta etapa inicial do processo de avaliação, foram definidos as características de qualidade a serem considerados com base nos objetivos da avaliação e no perfil do público-alvo. A análise levou em conta tanto as necessidades dos usuários finais quanto os interesses da equipe de desenvolvimento, com o propósito de identificar características críticas para a experiência de uso e o desempenho do sistema.

Foram priorizadas as características de **usabilidade** e **confiabilidade**, devido à sua relação direta com acessibilidade, facilidade de uso e estabilidade da aplicação — aspectos fundamentais para um público composto por pessoas com 30 anos ou mais, incluindo idosos e usuários com menor familiaridade tecnológica.

A seguir, apresenta-se a classificação das características de qualidade com suas respectivas ênfases, conforme os critérios da abordagem SQuaRE (ISO/IEC 25010)<sup>[2]</sup>, em uma escala de 1 a 5. A SQuaRE (Software Product Quality Requirements and Evaluation) é uma norma internacional que define um modelo de qualidade para produtos de software, estabelecendo características e subcaracterísticas que servem como referência para avaliação e especificação da qualidade de sistemas.

| Característica | Ênfase (1-5) |
|---|---|
| Usabilidade | 5 – grande interesse|
| Confiabilidade | 5 – grande interesse|
| Funcionalidade | 4 – largo interesse|
| Eficiência (Desempenho) | 2 – baixo interesse|
| Compatibilidade | 2 – baixo interesse|
| Segurança | 1 – nenhum interesse|
| Manutenibilidade | 1 – nenhum interesse|
| Portabilidade | 1 – nenhum interesse |

Essa priorização servirá como base para a especificação das métricas, definição dos critérios de julgamento e planejamento da avaliação, garantindo foco nas qualidades mais relevantes para a experiência e confiança dos usuários no produto avaliado.

## Proposta de Avaliação e Melhoria de Qualidade 

A proposta de avaliação tem como principal objetivo assegurar a qualidade da aplicação a partir das perspectivas dos usuários e desenvolvedores, considerando as características do público-alvo predominante, composto por:  

- Pessoas com idade entre **30 anos ou mais**, com ênfase no público idoso;   
- Indivíduos com **menor** familiaridade com tecnologias digitais.  

O domínio da aplicação abrange comunidades de agricultura familiar, consumidores e vendedores inseridos em um ambiente digital de compra e venda. A avaliação visa, portanto, garantir que o produto atenda às necessidades desse público, identificar pontos de melhoria relacionados à usabilidade — de modo a facilitar o acesso, a navegação e a compreensão da aplicação —, além de propor sugestões que contribuam para a manutenção da confiabilidade do sistema.

## Conexão com ODS (Objetivo de Desenvolvimento Sustentável) da ONU

A aplicação avaliada apresenta forte alinhamento com diversos Objetivos de Desenvolvimento Sustentável (ODS) propostos pela Organização das Nações Unidas (ONU)<sup>[3]</sup>, demonstrando seu potencial de impacto positivo em múltiplas dimensões sociais, econômicas e ambientais. A seguir, destacam-se os ODS com os quais a aplicação se conecta diretamente:

- **ODS 2 – Fome Zero e Agricultura Sustentável:** ao promover a valorização da agricultura familiar e facilitar a comercialização de seus produtos, a aplicação contribui para o fortalecimento de sistemas alimentares sustentáveis e o acesso à alimentação de qualidade.

- **ODS 8 – Trabalho Decente e Crescimento Econômico:** a plataforma incentiva o empreendedorismo local e a geração de renda, especialmente entre pequenos produtores rurais e comerciantes, fomentando práticas econômicas inclusivas e sustentáveis.

- **ODS 11 – Cidades e Comunidades Sustentáveis:** ao conectar produtores e consumidores de forma digital, a aplicação promove redes de consumo local e incentiva práticas comunitárias mais sustentáveis, fortalecendo a coesão social nas comunidades atendidas.

- **ODS 12 – Consumo e Produção Responsáveis:** a iniciativa estimula o consumo consciente e a valorização de produtos locais, contribuindo para cadeias de produção mais éticas, sustentáveis e transparentes.

- **ODS 15 – Vida Terrestre:** ao incentivar práticas agrícolas sustentáveis e apoiar a agricultura familiar, a aplicação colabora com a preservação de ecossistemas terrestres e o uso sustentável dos recursos naturais.


## Tabela de Contribuição

Na Tabela 1, apresenta-se a contribuição dos membros da equipe na construção do artefato.

<font size="3"><p style="text-align: center">Tabela 1 - Tabela de contribuição</p></font>

<div align="center">
  <table border="1">
    <thead>
      <tr>
        <th>Matrícula</th>
        <th>Nome completo</th>
        <th>Contribuição (%)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>221007798</td>
        <td><a href="https://github.com/ailujana">Ana Júlia Mendes Santos</a></td>
        <td>16,66</td>
      </tr>
      <tr>
        <td>221022355</td>
        <td><a href="https://github.com/julia-fortunato">Júlia Rocha Fortunato</a></td>
        <td>16,66</td>
      </tr>
      <tr>
        <td>221008338</td>
        <td><a href="https://github.com/Oleari19">Maria Clara Oleari de Araujo</a></td>
        <td>16,66</td>
      </tr>
      <tr>
        <td>222007021</td>
        <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira de Araújo</a></td>
        <td>16,66</td>
      </tr>
      <tr>
        <td>222006356</td>
        <td><a href="https://github.com/PedroLock">Pedro Lock Martins</a></td>
        <td>16,66</td>
      </tr>
      <tr>
        <td>221022767</td>
        <td><a href="https://github.com/vevetin">Weverton Rodrigues da Costa Silva</a></td>
        <td>16,66</td>
      </tr>
    </tbody>
  </table>
</div>

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a> e <a href="https://github.com/vevetin">Weverton Rodrigues</a>, 2025</p></font>

## Bibliografia
> \- ISO/IEC 25000 SQuaRE series Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE). Disponível em: <https://committee.iso.org/sites/jtc1sc7/home/projects/flagship-standards/iso-25000-square-series.html>. Acesso em: 22 de maio de 2025. 
 
> \- ISO/IEC 25010. Disponível em: <https://iso25000.com/index.php/en/iso-25000-standards/iso-25010>. Acesso em: 22 de maio de 2025.

> \- Documentação do AgroMart. Disponível em: <https://agromart.github.io/docs/docs/intro>. Acesso em: 22 de maio de 2025.

## Referências Bibliográficas

> [1] AgroMart. Disponível em: <https://github.com/AgroMart>. Acesso em: 22 de maio de 2025.

> [2] ISO/IEC 25010. Disponível em: <https://iso25000.com/index.php/en/iso-25000-standards/iso-25010>. Acesso em: 22 de maio de 2025.

> [3] ONU. Objetivos de Desenvolvimento Sustentável. Disponível em: <https://brasil.un.org/pt-br/sdgs>. Acesso em: 22 de maio de 2025.


## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|22/05/2025|Criação do documento| [Júlia Fortunato](https://github.com/julia-fortunato) e [Weverton Rodrigues](https://github.com/vevetin) |[Ana Júlia](https://github.com/ailujana)|