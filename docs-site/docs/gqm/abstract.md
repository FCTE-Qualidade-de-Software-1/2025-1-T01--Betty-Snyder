## Abstraction Sheets - Objetivo de Medição 1: Usabilidade

<table>
  <tr>
    <th>Object</th>
    <th>Purpose</th>
    <th>Quality Focus</th>
    <th>Viewpoint</th>
  </tr>
  <tr>
    <td>Plataforma Agromart</td>
    <td>Compreender a facilidade de uso e interação do usuário com o sistema.</td>
    <td>Usabilidade e suas subcaracterísticas: adequação, reconhecibilidade, aprendizado, proteção contra erros, estética e acessibilidade.</td>
    <td>Equipe de desenvolvimento e usuários finais (agricultores e consumidores)</td>
  </tr>
  <tr>
    <th colspan="2">Quality Focus</th>
    <th colspan="2">Variation Factors</th>
  </tr>
  <tr>
    <td colspan="2">
        <ul>
            <li>Facilidade de navegação</li>
            <li>Interface intuitiva</li>
            <li>Clareza das informações exibidas</li>
            <li>Prevenção de erros</li>
            <li>Tempo médio para realizar tarefas básicas (ex: cadastro, pedido, login)</li>
            <li>Nível de acessibilidade</li>
        </ul>
    </td>
    <td colspan="2">
        <ul>
            <li>Familiaridade prévia dos usuários com tecnologia</li>
            <li>Qualidade visual e responsividade da interface</li>
            <li>Nível de clareza textual das instruções e tutoriais (labels, mensagens, botões)</li>
            <li>Faixa etária dos usuários</li>
            <li>Dispositivos utilizados (PC, celular, tablet)</li>
            <li>Tipos de deficiência visual</li>
        </ul>
    </td>
  </tr>
    <tr>
    <th colspan="2">Baseline Hypotheses (estimates)</th>
    <th colspan="2">Impact of Variation Factors</th>
  </tr>
  <tr>
    <td colspan="2">
        <ul>
            <li>80% dos usuários concluem tarefas sem dificuldades</li>
            <li>Novos usuários compreendem a plataforma com até 5 minutos de uso exploratório</li>
            <li>Tempo médio para finalizar uma compra: até 3 minutos</li>
            <li>Pelo menos 85% dos usuários reconhecem as funcionalidades básicas sem ajuda externa</li>
            <li>90% dos usuários avaliam a interface de maneira positiva</li>
            <li>95% das telas avaliadas possuem contraste adequado</li>
        </ul>
    </td>
    <td colspan="2">
        <ul>
            <li>Usuários com baixa familiaridade digital demandam mais clareza e feedback</li>
            <li>Melhor escrita e organização visual aumentam a autonomia dos usuários</li>
            <li>Podem aumentar os níveis de erros pelos usuários</li>
            <li>Jovens podem ter mais familiaridade com interfaces digitais</li>
            <li>O uso de dispositivos móveis pode afetar negativamente a experiência se o layout não for adaptado</li>
            <li>O "contraste adequado" pode não ser universal (ex.: válido para videntes, mas não para usuários com baixa visão)</li>
        </ul>
    </td>
  </tr>
</table>

## Abstraction Sheets - Objetivo de Medição 2: Confiabilidade

<table>
  <tr>
    <th>Object</th>
    <th>Purpose</th>
    <th>Quality Focus</th>
    <th>Viewpoint</th>
  </tr>
  <tr>
    <td>Plataforma Agromart</td>
    <td>Compreender a estabilidade e a capacidade de recuperação do sistema</td>
    <td>Confiabilidade e suas subcaracterísticas: maturidade, disponibilidade, tolerância a falhas, recuperabilidade.</td>
    <td>Equipe de desenvolvimento e manutenção do sistema</td>
  </tr>
  <tr>
    <th colspan="2">Quality Focus</th>
    <th colspan="2">Variation Factors</th>
  </tr>
  <tr>
    <td colspan="2">
        <ol>
            <li>Número de falhas:</li>
            <ul>
                <li>Durante uso normal pelos usuários</li>
                <li>Por tipo de falha (erro de sistema, indisponibilidade, falhas de feedback)</li>
                <li>Por frequência de ocorrência</li>
                <li>Por impacto no processo de comercialização</li>
            </ul>
            <li>Tempo médio de disponibilidade</li>
            <li>Respostas aos erros</li>
            <li>Capacidade de retomada após interrupções</li>
        </ol>
    </td>
    <td colspan="2">
        <ul>
            <li>Volume de usuários simultâneos</li>
            <li>Infraestrutura da aplicação</li>
            <li>Diferente tipos de erros e contexto dos usuários</li>
            <li>Qualidade do código e cobertura de testes</li>
        </ul>
    </td>
  </tr>
    <tr>
    <th colspan="2">Baseline Hypotheses (estimates)</th>
    <th colspan="2">Impact of Variation Factors</th>
  </tr>
  <tr>
    <td colspan="2">
        <ol>
            <li>Distribuição esperada de falhas (durante um mês de uso):</li>
            <ul>
                <li>Leves: 70% (ex: mensagens pouco claras, pequenos travamentos)</li>
                <li>Médias: 20% (ex: erros que exigem recarregar a página)</li>
                <li>Graves: 10% (ex: falha ao finalizar pedidos ou perda de dados)</li>
            </ul>
            <li>Disponibilidade mensal > 99%</li>
            <li>90% dos erros exibem mensagens claras</li>
            <li>95% dos processos retomam automaticamente após falhas</li>
        </ol>
    </td>
    <td colspan="2">
        <ul>
            <li>Alta carga de usuários pode aumentar falhas graves e lentidão</li>
            <li>Melhor infraestrutura e monitoramento aumentam a disponibilidade e a recuperabilidade.</li>
            <li>Diferentes categorias de erros exigem abordagens distintas para correção</li>
            <li>Cobertura de testes baixa pode causar aumento em falhas médias e graves</li>
        </ul>
    </td>
  </tr>
</table>

## Rastreabilidade

A rastreabilidade entre os elementos permite compreender como diferentes fatores de qualidade, variações no contexto de uso e hipóteses de desempenho estão interligados e impactam a experiência dos usuários e a robustez do sistema. A seguir, são apresentadas duas tabelas de rastreabilidade — uma para cada objetivo de medição (usabilidade e confiabilidade) — que conectam os focos de qualidade com fatores de variação, hipóteses estabelecidas e os impactos observados dessas variações. Essa estrutura lógica facilita a visualização de como determinadas decisões de design e desenvolvimento afetam diretamente a experiência do usuário final e o comportamento da aplicação em diferentes condições.

---

### Usabilidade

| Quality Focus                         | Variation Factor                                           | Hypotheses (estimates)                                                              | Impact of Variation Factor                                                         |
|--------------------------------------|------------------------------------------------------------|--------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| Facilidade de navegação              | Qualidade visual e responsividade da interface             | Novos usuários compreendem a plataforma com até 5 minutos de uso exploratório       | Melhor escrita e organização visual aumentam a autonomia dos usuários              |
| Interface intuitiva                  | Familiaridade prévia dos usuários com tecnologia           | 80% dos usuários concluem tarefas sem dificuldades                                  | Usuários com baixa familiaridade digital demandam mais clareza e feedback          |
| Clareza das informações exibidas     | Nível de clareza textual das instruções e tutoriais        | Pelo menos 85% dos usuários reconhecem funcionalidades básicas sem ajuda externa    | Pode aumentar os níveis de erros pelos usuários                                    |
| Prevenção de erros                   | Faixa etária dos usuários                                  | 90% dos usuários avaliam a interface de maneira positiva                             | Jovens têm mais familiaridade com interfaces digitais                               |
| Acessibilidade                       | Tipos de deficiência visual                                | 95% das telas avaliadas possuem contraste adequado                                  | O contraste pode não ser universal (ex: baixa visão)                                |
| Tempo médio para realizar tarefas    | Dispositivos utilizados (PC, celular, tablet)              | Tempo médio para finalizar uma compra: até 3 minutos                                | Layout não adaptado afeta negativamente a experiência                               |

---

### Confiabilidade

| Quality Focus                         | Variation Factor                          | Hypotheses (estimates)                                                                                  | Impact of Variation Factor                                                             |
|--------------------------------------|-------------------------------------------|----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| Número de falhas por tipo e impacto  | Diferentes tipos de erros e contexto       | Distribuição esperada de falhas: 70% leves, 20% médias, 10% graves                                       | Diferentes categorias exigem abordagens distintas                                       |
| Tempo médio de disponibilidade       | Volume de usuários simultâneos            | Disponibilidade mensal > 99%                                                                             | Alta carga pode aumentar falhas graves e lentidão                                      |
| Respostas aos erros                  | Qualidade do código e cobertura de testes | 90% dos erros exibem mensagens claras                                                                   | Cobertura de testes baixa pode causar aumento em falhas médias e graves                |
| Capacidade de retomada               | Infraestrutura da aplicação               | 95% dos processos retomam automaticamente após falhas                                                    | Melhor infraestrutura e monitoramento aumentam a disponibilidade e recuperabilidade    |

## Tabela de Contribuição

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
        <td>19</td>
      </tr>
      <tr>
        <td>221022355</td>
        <td><a href="https://github.com/julia-fortunato">Júlia Rocha Fortunato</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>221008338</td>
        <td><a href="https://github.com/Oleari19">Maria Clara Oleari de Araujo</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>222007021</td>
        <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira de Araújo</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>222006356</td>
        <td><a href="https://github.com/PedroLock">Pedro Lock Martins</a></td>
        <td>5</td>
      </tr>
      <tr>
        <td>221022767</td>
        <td><a href="https://github.com/vevetin">Weverton Rodrigues da Costa Silva</a></td>
        <td>19</td>
      </tr>
    </tbody>
  </table>
</div>


## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|22/05/2025|Criação do documento|[Júlia Fortunato](https://github.com/julia-fortunato)|[Weverton Rodrigues](https://github.com/vevetin)|
|`1.1`|25/05/2025|Correção abstraction sheets|[Maurício Ferreira](https://github.com/mauricio-araujoo)|[Júlia Fortunato](https://github.com/julia-fortunato)|
|`1.2`|31/05/2025|Rastreabilidade abstraction sheets|[Ana Júlia](https://github.com/ailujana)|[Júlia Fortunato](https://github.com/julia-fortunato)|

