# Desafio Machine Learning | LAB IA-900

#### PROJETO DA DIO PARA CERTIFICAÇÃO MICROSOFT IA-900

## Dados sobre o projeto:

- _Crie um novo repositório no github com um nome a sua preferência;_
- _Crie um modelo de previsão com seus devidos pontos de extremidade configurados;_
- _Escreva o passo a passo desse processo em um readme.md de como você chegou nessa etapa;_
- _Salve nesse repositório o readme.md e o arquivo .json de pontos de extremidade;_
- _Compartilhe conosco o link desse repositório através do botão 'entregar projeto'._

##
#### Tutorial para execução desse lab: 
- [Lab01 Machine Learning ](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)
##

> ## Testar o serviço implantado
  
![image](https://github.com/littlegirl777/Dio-Microsoft-IA-900/assets/156604824/c2677a0c-d94c-4e80-b7a8-a9c8e43926ac)


![image](https://github.com/littlegirl777/Dio-Microsoft-IA-900/assets/156604824/9aa4d475-088c-4475-910c-55fab61686a6)



   ## Entrada teste e saida:
   > [!IMPORTANT]
   Testando ponto de extremidade parametros

  ```json
   {
     "Inputs": { 
       "data": [
         {
           "day": 1,
           "mnth": 1,   
           "year": 2022,
           "season": 2,
           "holiday": 0,
           "weekday": 1,
           "workingday": 1,
           "weathersit": 2, 
           "temp": 0.3, 
           "atemp": 0.3,
           "hum": 0.3,
           "windspeed": 0.3 
         }
       ]    
     },   
     "GlobalParameters": 1.0
   }
  ```
  ## 
  Resultado do teste
  
  ```json
   {
     "Results": [
       339.21702316370437
     ]
   }
  ```

## Referência:

 - [Explore Azure AI Services](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html).
 - [Explore Automated Machine Learning in Azure Machine Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html).
 
