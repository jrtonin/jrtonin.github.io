---
date: '2021-11-17T16:11:41-03:00'
draft: False
output:
  md_document:
    preserve_yaml: True
    variant: markdown
title: Conceitos de R e RStudio para o dia a dia
---

Índice
------

**[Módulo I: R e RStudio - Passos iniciais](#heading1)**

-   [1.1. Principais motivações para uso do R no dia a dia](#heading1.1)
-   [1.2. Instalando o R e o RStudio](#heading1.2)
-   [1.3. Principais fóruns para acessar material de
    suporte](#heading1.3)
    -   [1.3.1 Exercício de fixação](#heading1.3.1)
-   [1.4. Conhecendo o ambiente de trabalho do RStudio](#heading1.4)
-   [1.5. Editando scripts e ajustando o diretório de
    trabalho](#heading1.5)
    -   [1.5.1 Exercício de fixação](#heading1.5.1)
-   [1.6. Usando pacotes de dados e funções](#heading1.6)
    -   [1.6.1 Exercício de fixação](#heading1.6.1)
-   [1.7. Solicitando ajuda pelo R](#heading1.7)
    -   [1.7.1 Exercício de fixação](#heading1.7.1)
-   [1.8. Aplicando regras de programação e código limpo](#heading1.8)
-   [1.9. Avaliação da Aprendizagem](#heading1.9)

**[Módulo II: Operações matemáticas](#heading2)**

------------------------------------------------------------------------

<div id="heading1.1"/>

### 1.1. Principais motivações para uso do R no dia a dia

1.  **É completamente gratuito**: O R é uma ferramenta open source e
    está em constante desenvolvimento. Por ser um software consolidado
    no mercado e academia, e muito utilizada para a área de data
    science, há uma comunidade muito forte e atuante, que se dedica
    tanto na construção de novas versões, quanto pacotes, funções, bases
    de dados, etc.

2.  **A comunidade é forte e atuante**: A diversidade de profissionais e
    aplicações torna o R uma ferramenta com extensa rede de informações,
    seja em soluções para problemas em rotinas, pacotes e funções, e
    também cursos, boas práticas, códigos prontos e bases de dados.
    Diariamente os usuários postam informações preciosas em sites como o
    [R Project](https://www.r-project.org/),
    [R-bloggers](https://www.r-bloggers.com/), [RStudio
    Blog](https://www.rstudio.com/blog/) e
    [StackOverflow](https://pt.stackoverflow.com/).

3.  **Facilidade**: Não é necessário uma formação específica para usar
    o R. Por mais que seja amplamente difundido em cursos de exatas,
    apenas o interesse de conhecer, estruturar, organizar e estudar
    bases de dados já é uma forte motivação para utilizar a ferramenta.
    Sua lógica é orientada a objetos e permite o uso de inumeros
    formatos de dados.

4.  **Fácil integração**: O RStudio permite o uso integrado do R com
    outros softwares e linguagens de programação. Por exemplo, essa
    apostina foi desenvolvida em RMarkdown, foi exportada em formado
    Markdown para um site no GitHub, construído em Hugo e que se integra
    em bases de dados que são consultadas em SQL.

5.  **Pacotes sólidos na áerea de estatística**: Na década de 1990, dois
    pesquisadores da Universidade de Auckland sentiram a necessidade de
    desenvolver software específico para realizar experimentos
    estatísticos no laboratório. Em 2000, após ser melhorado e testado,
    a versão 1.0 foi lançada e o R tornou-se um projeto
    internacionalmente colaborativo. Devido a sua origem estar atrelado
    ao ambiente de pesquisa, hoje o R é um dos maiores repositórios de
    rotinas e pacotes estatísticos.

-   **Alabama**
-   `Alaska`
-   [Arizona](https://az.gov)
-   *Arkansas*
-   ~~California~~
