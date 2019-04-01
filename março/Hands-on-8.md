—
tags: hacking-health, espirito-santo
—

# Hacking Health: Hands-on #8 
Dia 2019-03-30

## Diário de bordo
- Café
- Aula de histologia e anatomia em ofltamologia com Vinicius Araújo e Willer Fiorott
- Mortalidade infantil com Fabiano Filho
- Engenharia de dados com Gustavo Rocha e Rafael Conceição
- Extração de dados com Lucas Alves
- Impletação do Data Package para dados do DATASUS SIHSUS

## Links

### Bases de dados
 Arquivos de dados: http://www2.datasus.gov.br/DATASUS/index.php?area=0901
- [Banco de dados por estado/ano](http://bit.ly/dadosimnasc) ok = está no drive (http://bit.ly/dadosimnasc)
- [SIM](http://www2.datasus.gov.br/DATASUS/index.php?area=0901&item=1&acao=28&pad=31655) ok!
- [SINASC](http://www2.datasus.gov.br/DATASUS/index.php?area=0901&item=1&acao=26&pad=31655) ok!
- [SISPRENATAL](http://www2.datasus.gov.br/DATASUS/index.php?area=0901&item=1&acao=29&pad=31655) (?)
- SIA [Info](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=19122), [Dados](http://www2.datasus.gov.br/DATASUS/index.php?area=0901&item=1&acao=22&pad=31655) (?)
- SIH: [Info](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633), [Dados](http://www2.datasus.gov.br/DATASUS/index.php?area=0901&item=1&acao=25) (?)
- [Dicionário de dados](http://bit.ly/simnasc)

[microdatasus](https://github.com/rfsaldanha/microdatasus)
: O pacote para o R microdatasus apresenta funções para download dos arquivos de microdados do DataSUS (formato DBC), leitura dos arquivos através do pacote [read.dbc](https://cran.r-project.org/web/packages/read.dbc/index.html) e pré-processamento para utilização. Nesta última etapa, os rótulos e formato das variáveis são atribuídos e tratados.




### Engenharia de dados
- https://frictionlessdata.io/data-packages/
- http://odo.pydata.org/en/latest/csv.html

### Visualização de dados
- https://public.tableau.com/en-us/s/
- https://pair-code.github.io/facets/

### Ciência de dados
- https://github.com/IDSIA/sacred
- https://www.youtube.com/watch?v=J8xfuCcXZu8
- https://github.com/fabianofilho/dojohealth

[Comet.ml – Machine Learning Experiment Management](https://www.kdnuggets.com/2018/04/comet-ml-machine-learning-experiment-management.html)
: This article presents comet.ml – a platform that allows tracking machine learning experiments with an emphasis on collaboration and knowledge sharing.

### Visão computacional

[imgaug](https://github.com/aleju/imgaug)
: This python library helps you with augmenting images for your machine learning projects. It converts a set of input images into a new, much larger set of slightly altered images.

## Perguntas

### Mortalidade infantil
- Qual é a quantidade de dias em media entre o nascimento e morte de cada estado?


## Glossário

### Medicina

Histologia
: Área biomédica que estuda os tecidos biológicos. Na biologia são estudados tecidos animais e de plantas (histologia animal e vegetal, respectivamente), analisando sua estrutura, origem e diferenciação.

### Tecnologia