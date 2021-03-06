# LABORATÓRIO DE EXPERIMENTAÇÃO DE SOFTWARE do curso de Engenharia de Software da PUC Minas <img align="center" alt="Victor-Python" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">

## Um Estudo das Características de Qualidade de Sistemas Java

### Hi there ! 👋🏽

Neste repositorio apresentamos como objetivo analisar aspectos da qualidade de repositórios desenvolvidos na linguagem Java, correlacionado-os com características do seu processo de desenvolvimento, sob a perspectiva de métricas de produto calculadas através da ferramenta CK

## Questões de Pesquisa: 

* RQ 01. Qual a relação entre a popularidade dos repositórios e as suas características de qualidade?
* RQ 02. Qual a relação entre a maturidade do repositórios e as suas características de qualidade ? 
* RQ 03. Qual a relação entre a atividade dos repositórios e as suas características de qualidade?  
* RQ 04. Qual a relação entre o tamanho dos repositórios e as suas características de qualidade?


## Processo de Desenvolvimento

Para realização do desafio foi utilizando a metodologia agil com os seguintes backlog para sprints:

* SP 01. Lista dos 1.000 repositórios Java + Script de Automação de clone e Coleta de Métricas + Arquivo .csv com o resultado as medições de 1 repositório
* SP 02. Arquivo .csv com o resultado de todas as medições dos 1.000 repositórios + Primeira versão do artigo final, contendo as hipóteses iniciais
* SP 03. Análise e visualização de dados + elaboração do relatório final

## Definição de métricas

Para cada questão de pesquisa, realizaremos a comparação entre as características do processo de desenvolvimento dos repositórios e os valores obtidos para as métricas definidas nesta seção. Para as métricas de processo, define-se:

* Popularidade: número de estrelas
* Tamanho: linhas de código (LOC) e linhas de comentários
* Atividade: número de releases
* Maturidade: idade (em anos) de cada repositório coletado

Por métricas de qualidade, entende-se:

* CBO: Coupling between objects
* DIT: Depth Inheritance Tree
* LCOM: Lack of Cohesion of Methods

## Requisitos

* Para utilizar o codigo acima é necessário na variavel api_token substituir a string 'place_your_token_here' pelo seu token disponibilizado  pelo github. Ex:
 
      api_token = 'seu_token_do_github'

* Para utilização dos import utilizar o interpretador python 3.9.7 
