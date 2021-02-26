## Testes em Diferentes Contextos

* ### Ciclos de Vida de Desenvolvimento no Contexto Ágil e Tradicional
  Para que uma aplicação seja desenvolvida, ela passa por um processo composto por atividades. 
  Há dois modelos de processos bastante populares, o Tradicional e o Ágil.
  
  #### Características do modelo tradicional:
    * O processo é faseado e de escopo fechado;
      * Fase de planejamento, fase para design, fase de desenvolvimento, etc... Cada fase com um time diferente.
    * Preciso colocar todo o meu foco no cumprimento de minha atividade primária, que é produzir artefatos e testar aplicações, 
     baseando-se nas documentações e requisitos fornecidos por fases anteriores.
    * O software só chega ao usuário final ao final de todo o processo de desenvolvimento.
    
     <p align="center"><img src="https://dkrn4sk0rn31v.cloudfront.net/2018/01/08121228/modelo-cascata.png" width="500px"> </p>
    
    #### Processo de testes no modelo tradicional:
     <table>
      <thead>
        <th>Fase</th>
        <th>Atividades</th>
        <th>Artefatos</th>
      </thead>
      <tr>
        <td> <b>Documentação</b> </td>
        <td> Revisar documentação</td>
        <td> Plano de teste e caso de teste</td>
      </tr>
      <tr>
        <td> <b>Codificação</b> </td>
        <td> Revisar código fonte </td>
        <td> Testes de unidade e testes de integração </td>
      </tr>
      <tr>
        <td> <b>Testes</b> </td>
        <td> Executar os casos de testes já criados, automatizar testes e gerir inconsistências e retestar </td>
        <td> Log de testes, reporte de inconsistências e scripts de teste automatizado </td>
      </tr>
      <tr>
        <td> <b>Homologação</b> </td>
        <td> Auxiliar os usuários nos testes de aceitação </td>
        <td> Reporte inconsistências </td>
      </tr>
      <tr>
        <td> <b>Entrega</b> </td>
        <td> Versionar o testware, emetir relatórios de fechamento dos testes e monitorar a aplicação em produção </td>
        <td> Reporte inconsistências e relatório de resumo dos testes </td>
      </tr>
    </table>
     
  
  #### Características do modelo ágil:
    * Um único time trabalhando junto para desenvolver o software como um todo;
    * Entrega contínua com base em funcionalidades;
    * Pode ocorrer mudanças;
    * Não sou o guardião da qualidade do produto. Eu compartilho as responsabilidades de teste com o 
    time de desenvolvimento e os mentoro na aplicação de testes desde a concepção a entrega em produção. 
    Todos precisam automatizar testes, por isso eu crio e ajudo meu time a codificar esses testes.
     
     <p align="center"><img src="https://miro.medium.com/max/626/0*2FyNxlm6vr8QXJJp.png" width="500px"></p>
     
     
     #### Processo de testes no modelo tradicional:
     <table>
      <thead>
        <th>Fase</th>
        <th>Atividades</th>
        <th>Artefatos</th>
      </thead>
      <tr>
        <td> <b>Desenho</b> </td>
        <td> Discussões quanto a viabilidade, revisão de artefatos e levantamento de riscos </td>
        <td> Mapas mentais </td>
      </tr>
      <tr>
        <td> <b>Refinamento</b> </td>
        <td> Colaboração na definição de critérios de aceitação, revisão de artefatos, estimativas de esforço em teste, 
          levantamento de riscos e atualização do plano de testes</td>
        <td> Mapas mentais </td>
      </tr>
      <tr>
        <td> <b>Planejamento</b> </td>
        <td> Estimativas de esforço em testes </td>
        <td> Tarefas de teste </td>
      </tr>
      <tr>
        <td> <b>Códificação e Testes </b> </td>
        <td> Executar tarefas de teste, executar testes exploratorios, automatizar testes,
          dar suporte aos desenvolvedores na escrita e gerir inconsistências e retestando </td>
        <td> Reporte de inconsistencias e scripts de teste automatizado,
          testes de unidade e integração </td>
      </tr>
      <tr>
        <td> <b>Entrega</b> </td>
        <td> Colabor para qualidade dos processos de entrega, monitorar a aplicação em produção e
          monitorando execução dos serpts de teste automatizados </td>
        <td> Reporte de inconsistências </td>
      </tr>
    </table>
  
 ______________________________
 <p align="center"><i>Todos os textos são de autoria do Júlio de Lima retirados do treinamento em Teste de Software.</i></p>
