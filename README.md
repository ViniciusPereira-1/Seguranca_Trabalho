# Dashboard Seguranca_Trabalho
Dashboard em Excel exemplificando sua aplicação dentro da área de Segurança do Trabalho (dados fictícios)
_______________________________________________________________________________________________
## Estruturação de nomeação:
### Intervalos e Macros
*bd_Main* -> Refere-se a Base de Dados em sua totalidade.

*seg_XXXX* -> Refere-se às segmentações de dados.

*macro_XXXX* -> Refere-se às macros.

*graph_XXXX* -> Nomeação de alguns gráficos

### Tabelas

*tab_XXXX* -> Tabelas regulares.

*tabD_XXXX* -> Tabelas Dinâmicas.

# VERSÃO ATUAL
### 1.1 - Funcionalidades e botões adicionais

  **Referentes à Dashboard**
  *Implementações:*
  - O gráfico de Número de acidentes agora possui dois botões "Simplificado" e "Detalhado".
    - Os botões alternam entre mostrar as informações apenas por departamento, ou mostrá-las também divididas por turno.

  - O gráfico de Custo Mensal agora possui um botão "Otimizar Escala".
    - O botão chama uma Macro que ajusta o valor máximo da escala do Eixo Y do gráfico conforme a seleção, facilitando a leitura (especialmente em valores pequenos).
    
  - A seleção de filtro por Local do Dano demonstra visualmente, em um imagem de corpo humano, qual a parte selecionada.
  - A seleção de filtro por Tipo de Relato agora é realizada através de botões em forma de imagem, que mudam de forma conforme a seleção.
  - A seleção de filtro por Gênero  agora é realizada através de botões em forma de imagem.

 **Referentes à Pasta de Trabalho**
 - A Planilha "Tabelas de Apoio" foi criada para a implementação de funcionalidades extras da Dashboard. Assim como a Planilha de "Tabelas de Análise", a posição dos dados é fundamental para o funcionamento adequado de todas as macros, exigindo que estas NÃO sejam alteradas de local por quem desconheça como realizar os ajustes necessários.

  *Pendentes:*
  - Planilha de Índice;
_______________________________________________________________________________________________
### HISTÓRICO
### 1.0 - Dashboard funcional

  - A Dashboard está funcional.
  - Todos os gráficos dinâmicos e filtros estão devidamente linkados e formatados.
  - As Planilhas de Tabelas de Dados e Tabelas de Apoio foram coloridas com Cinza, indicando que o usuário deve evitar utilizá-las manualmente.
