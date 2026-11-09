# Curso de Docker da Geek University
## curso sql e nosql:
    https://www.udemy.com/course/curso-de-banco-de-dados-do-basico-ao-avancado/learn/lecture/13007686#overview
## Curso de K8s:
    https://www.udemy.com/course/kubernetes-do-basico-ao-avancado/?couponCode=KEEPLEARNING

## 26/10/26:
    Aula inicial

## 29/10/26:
    YAML = Yet another Markup Language
    geralmente chave: valor (um espaço somente) identar com dois espaços
    tem estilo bloco e estilo flow 
    dif entre yaml e yml
### escalares:
    string, numero etc é escalar 
    qdo nao faz conta com o numero eh por colocar entre aspas 
    soh da pra pular linha com \n com "42\n" e não com aspas simples 
### remove todos menos o container com um determinado id - docker ps -aq | grep -v ceabf1dbc1f5 | xargs -r docker rm -f

## 02/11/26
    containeres n persistem dados 

## 03/11/26    
    num projeto de apenas um arquivo usamos Dockerfile sem arquivo, agora se tivermos separados por serviço podemos ter banco.dockerfile, web.dockerfile etc

## 08/11/26
    docker compoose
    escala vertical upgrade fisico, horizontal replicamos a msm maquina ou serviço n vezes

