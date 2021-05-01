# Bem-vindo ao desafio

<div align="center">
  <img src="https://credenciamentodigital.getnet.com.br/assets/img/269c8ccd8dca4060be3846282431968f.png" width="300px"/>
</div>

## Informações gerais:

https://reqres.in/ - Documentação
URI = https://reqres.in/api/

## Avaliação:
### 1 - Realizar ao menos um script de cobertura de testes em Rest-Assured da API 
[Projeto Automação API](https://github.com/LuisFelipeSeabra/prova_renner/tree/master/AutomationProject)


### 2 - Escrever a tecnica utilizada para cobertura do cenário de testes utilizado
Foi utilizada a técnica “Operator Coverage” para verificação da cobertura de testes, que basicamente é o cálculo da Quantidade de operações da API que estão automatizados/ Quantidade total de operações da API REST.

#### Resultado da cobertura:
##### Dados:
* QtdAut = Quantidade de operações da API estão automatizados = 7
* QtdTot = Quantidade total de operações da API REST = 15
##### Cálculo:
* QtdAut/ QtdTot = 7/15 = 0,47
```
Ou seja, 47% dos testes de operação estão cobertos pela automação de testes.
```

## Estruturação do Projeto:
```
├── /ReqresAPI                                        # Projeto                                                                                          
    ├── src/main/java                                 #                                                                                                         
        ├── br.df.lseabra.core                        # Pacote de Core                                                                                        
            ├── BaseTest.java                         # classe que será extendida pelas classes de teste
            ├── Constantes.java                       # Interface contendo porta, Url e Content type
        ├── br.df.lseabra.test                        # Pacote de Testes
            ├── RegisterTest.java                     #Classe com testes refrentes a "Register"
            ├── UserTest.java                         #Classe com testes refrentes a "User"
        ├── br.df.lseabra.suite                       # Pacote de Suite
            ├── Suite.java                            #Suite de testes
```
## Executar o Teste
Executar pela IDE de sua preferência o arquivo: 
```
Suite.java                                     # Suite de teste para quando há login de cliente ao entrar no site
```

## Tecnologia:

Tecnologias utilizadas no projeto:
  * JRE 1.8.0_281
  * Maven
  * io.rest-assured 4.0.0 
  * groovy 3.0.5
  * Eclipse
