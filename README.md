Sumário:
========

- [Grupo](#grupo)
- [Links](#links)
- [Introdução](#introdução)
- [Desenvolvimento](#desenvolvimento)
  1. [Sprints](#sprints)
  2. [Requisitos](#requisitos)
  3. [Tabela Canvas](#tabela-canvas)
  4. [Planejamento](#planejamento)
      * [DFD](#dfd)
      * [MER](#mer)
      * [Conceitos Iniciais](#conceitos-iniciais-do-site)
- [Bibliografia Utilizada](#bibliografia)
- [Imagens](#imagens-externas-utilizadas)

-------------------------------------------------------------------------------

# Grupo

|   Cargo   |  Nome  |  R.A.  |
|   :---:   |  :---: |  :---: |
|  Scrum Master  |  Pedro Henrique Silva Domingues  |  22.218.019-2  |
|  P.O.  |  Rafael Felipe Lino  |  22.118.182-9  |
|  Dev. Team  |  João Victor da Silva Couto  | 22.118.022-7  |
|  Dev. Team  |  Kaike Rodrigues Zuanetti  |  22.118.116-7  |
|  Dev. Team  |  Felipe Maciel de Sousa  |  22.218.042-4  |

-------------------------------------------------------------------------------

# Links

- [Trello](https://trello.com/b/rQ9d7zP6/eng-software) - Kanban com a organização das tarefas
- [Site](https://12pedro07.github.io) - Link de facil acesso ao site hospedado no próprio github
- [Forms](https://docs.google.com/forms/d/1uBkIgZ2C1a4m5CCoAonrmNfk55EAgYLl1q4AhJtLzbQ/edit#responses) - Dados coletados via google forms

-------------------------------------------------------------------------------

# Introdução

   O intuito deste trabalho é aprender e aplicar conceitos de engenharia de software e metodologia ágil. Assim sendo, devemos desenvolver um projeto que aplique os conceitos aprendidos ao decorrer de seu desenvolvimento.
   
   Nosso projeto constitui-se na construção de um site chamado "Passei no Guilherme!", o qual possui foco acadêmico e objetivo de auxilio a professores e principalmente alunos. Nosso foco é criar uma plataforma na qual alunos possam compreender o conteúdo de disciplinas como análise e complexidade, algoritmos e estrutura de dados de forma completa, interativa e visual, para que a compreensão de conceitos abstratos e normalmente de dificil compreensão para a maioria dos estudantes, torne-se mais interessante e simples.
   
   O site sera hospedado no GitHub e desenvolvido utilizando HTML, CSS e Java Script.
  
-------------------------------------------------------------------------------

# Desenvolvimento

## Sprints
  
  Todas as sprints podem ser acompanhadas no [Trello](https://trello.com/b/rQ9d7zP6/eng-software), mas estão também aqui resumidas.
  
  ### Primeira Sprint (04/03 ~ 18/03)
  
  Realizamos na primeira sprint a montagem dos primeiros diagramas de desenvolvimento, preparamos também um modelo de design inicial que utilizaremos como base para as sprints decorrentes.
  
  ### Segunda Sprint (18/03 ~ 01/04)
  
  Na segunda Sprint pesquisamos e escrevemos a teoria relativa a cada um dos algoritmos, para que seja realizada a montagem das páginas no site, como pode ser identificado no DFD nível 2 que refina "página do algoritmo".
  
  ### Terceira Sprint (01/04 ~ 15/04)
  
  Na terceira Sprint terminamos a escrita que foi iniciada na segunda sprint, juntamos imagens, gifs e demais arquivos necessários para o site e iniciamos a programação e modelagem do site. Junto a isso, começamos a realizar a montagem dos diagramas de teste.
  
  ### Quarta Sprint (15/04 ~ 29/04)
  
  ### Quinta Sprint (29/04 ~ 13/05)

## Requisitos

  O primeiro passo do desenvolvimento foi o levantamento dos requisitos, para isso foram criadas 8 perguntas que nos auxiliaram a compreender as preferencias dos clientes. Estas foram disponibilizadas via [google forms](#links) para serem preenchidas em escala likert e por foi o formulario criado foi divulgado com auxilio do professor Guilherme Wachs.

## Tabela Canvas

  Após o levantamento dos requisitos, para criar o planejamento inicial do projeto o grupo fez o levantamento de uma tabela canvas com base no modelo sebrae, como ilustrado abaixo.

![Tabela Canvas](/imagensEdiagramas/TabelaCanvas.jpg)

## Planejamento

  Para controle de entregas, tempo e divisão de tarefas, foi criado um [quadro kanban na plataforma trello](#links).

  Tendo os requisitos e o canvas, foi possivel refinar o planejamento do projeto. Portanto durante a primeira sprint o grupo se concentrou em criar o dfd e montar um mvp, um esqueleto inicial para para servir de base para o restante do periodo de desenvolvimento, como pode ser observado nas proximas subsessões.

### DFD

  O DFD (Diagrama de Fluxo de Dados) é responsavel por auxiliar a visualização do fluxo dos dados em meio ao processo do software desenvolvido. Este diagrama possui diversos níveis (iniciando de zero) e quanto maior este nível, mais refinada é a informação contida no diagrama.
  
|   Nível 0   |  Nível 1  |
|   :---:   |  :---: |
|  ![DFD0](/imagensEdiagramas/DFD0.jpg)  |  ![DFD1](/imagensEdiagramas/DFD1.jpg)  |

|   Nível 2 - Refina página do algoritmo   |
|   :---:   |
|  ![DFD2](/imagensEdiagramas/DFD2_pagAlgo.jpg)  |

-------------------------------------------------------------------------------

### MER

  O MER ou Diagrama de Entidade-Relacionamento é responsável por indicar como as entidades do projeto devem interagir entre sí, para o nosso propósito, utilizamos o MER para mostrar que, por exemplo, o usuário está conectado com a página de simulação com a relação de 1:N, ou seja, qualquer quantidade N de usuários pode acessar a 1 mesma pagina de simulação.
  
![MER](/imagensEdiagramas/MER.png)

-------------------------------------------------------------------------------

### Conceitos iniciais do site

  Aqui estão os diagramas de como foi pensado a construção e estrutura do site.

|   Conceito da Home   |  Conceito das sub-páginas  |
|   :---:   |  :---: |
|  ![Home Page](/imagensEdiagramas/Layout%20Homepage.png)  |  ![Pagina de um algoritmo](/imagensEdiagramas/Layout%20Merge%20Subpage.png)  |

### Ponto de função

|    Fatores de Ajuste              |Grau de Interferência|              
                                                                   
|1. | Backup                          |0|                             
|2. | Comunicação                     |0|                           
|3. | Processamento distribuído       |0|                           
|4. | Desempenho                      |5|                          
|5. | Ambiente operacional            |0|                         
|6. | Entradas on-line                |1|
|7. | Telas/operações múltiplas on    |5|
|8. | Atualização/recuperação de a    |1|
|9. | Entrada/saída/consulta compl    |1|
|10.| Processamento complexo          |1|
|11.| Código reutilizável             |5|
|12.| Converão e instalação           |0|
|13.| Portabilidade                   |0|
|14.| Manutenibilidade                |0|
|   |Total dos Fatores de Ajuste|     |15|



|    |           |Total de pontos|        |68|


# Bibliografia

- [Canvas Sebrae](https://www.sebraecanvas.com/#/) - Consultado em 03/03/2020

# Imagens externas utilizadas

- [GIF - quicksort](https://en.wikipedia.org/wiki/Quicksort) - Consultado em 27/03/2020
- [GIF - quicksort (partição)](https://gfycat.com/pleasantcloseeyelashpitviper) - Consultado em 26/03
