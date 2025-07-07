# Confiabilidade - M2: Percentual de requisitos que possuem testes automatizados associados

## Introdução

Na presente execução da análise de confiabilidade do Agromart, foi definida, durante a [Fase 2](../../gqm/gqm.md#seleção-das-métricas) do projeto, métricas que seriam utilizadas para avaliação do software. Logo, este documento tem como objetivo sintetizar os achados da métrica M2 de confiabilidade do Agromart: Percentual de requisitos com testes automatizados associados.


## Referencial teórico 

Para executar a avaliação, o meterial utilizado para a medição foi o PSM, com a aplicação do framework CID [1]. Tendo em vista a completude da especificação de medida da cobertura de testes automatizados, serão analisadas duas medidas derivadas: porcentagem de requisitos testados por automação e porcentagem de requisitos não testados.

Essa escolha se justifica uma vez que, queremos compreender o percentual de requisitos que são testados por automação, fazendo com que a confiabilidade do sistema persista durante o desenvolvimento do software, de acordo com os requisitos elicitados.


## Análise 

Dessa forma, a avaliação será feita de forma manual, com a análise dos [testes implementados](https://github.com/AgroMart/api/tree/devel/tests) na API do AgroMart, além da documentação de todos os [requisitos elicitados](https://agromart.github.io/docs/docs/requisitos/priorizacao/moscow) do AgroMart, com foco nos requisitos funcionais.

Assim, foi verificado o requisito e identificado se existe ou não um teste automatizado para o mesmo.

Os critérios de julgamento e níveis de pontuação da métrica serão utilizados conforme especificados na [Fase 2](../../gqm/gqm.md#níveis-de-pontuação-das-métricas).

### Execução da análise
Na Tabela 1, está presente a análise realizada sobre a cobertura de testes automatizados para os requisitos elicitados. 

A organização da tabela está feita de acordo com o requisito e existência ou não de um teste automatizado.

<font size="3"><p style="text-align: center">Tabela 1 – Avaliação e pontuação dos critérios de aceitação das histórias de usuário do Agromart</p></font>
<table border="1">
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Existe um teste automatizado referente a esse requisito?</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RF-1</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-2</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-3</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-4</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-5</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-6</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-7</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-8</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-10</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-11</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-12</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-13</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-14</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-15</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-16</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-17</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-18</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-19</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-20</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-21</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-22</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-23</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>RF-24</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-25</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-26</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>RF-27</td>
      <td>Não</td>
    </tr>

  </tbody>
</table>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>


## Resultados 

nao existe testes de carrinho, algumas funções de must não possuem testes associados 



<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 2 – Quantidade de requisitos</b></p>
  </font>

  <table border="1" style="margin: 0 auto;">
    <thead>
      <tr>
        <th>Requisitos funcionais totais</th>
        <th>Requisitos priorizados como "Won't have"</th>
        <th>Total de requisitos funcionais avaliados</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>27</td>
        <td>3</td>
        <td>24</td>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/julia-fortunato" target="_blank">Júlia Fortunato</a></p>
  </font>

</div>

<div style="text-align: center">

  <font size="3">
    <p><b>Tabela 2 – Distribuição da análise dos testes automatizados</b></p>
  </font>

  <table border="1" style="margin: 0 auto;">
    <thead>
      <tr>
        <th>Pontuação</th>
        <th>Quantidade</th>
        <th>Porcentagem</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>0/4</td>
        <td>19</td>
        <td>73,08%</td>
      </tr>
      <tr>
        <td>1/4</td>
        <td>1</td>
        <td>3,85%</td>
      </tr>
      <tr>
        <td>2/4</td>
        <td>0</td>
        <td>0,00%</td>
      </tr>
      <tr>
        <td>3/4</td>
        <td>6</td>
        <td>23,07%</td>
      </tr>
      <tr>
        <td>4/4</td>
        <td>0</td>
        <td>0,00%</td>
      </tr>
      <tr>
        <th>Total</th>
        <th>26</th>
        <th>100%</th>
      </tr>
    </tbody>
  </table>

  <font size="3">
    <p><b>Autor:</b> <a href="https://github.com/julia-fortunato" target="_blank">Júlia Fortunato</a></p>
  </font>

</div>


## Bibliografia

> \- Suíte de testes do AgroMart. Disponível em: <https://github.com/AgroMart/api/tree/devel/tests>. Acesso em: 07 de julho de 2025.


‌

## Referências Bibliográficas

> [1] JONES, C. et al. Practical Software and Systems Measurement Continuous Iterative Development Measurement Framework Part 2: Measurement Specifications and Enterprise Measures Editors. [s.l: s.n.]. Disponível em: <https://www.ndia.org/-/media/sites/ndia/divisions/systems-engineering/studies-and-reports/cid-measurement-framework-part-2---v2-1.pdf>. Acesso em: 07 de julho de 2025.



## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/07/2025|Criação do documento| [Júlia Fortunato](https://github.com/julia-fortunato) ||