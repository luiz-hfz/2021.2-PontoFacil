# Casos de Uso


### Histórico de versão

|Data | Versão | Modificação | Autor(es)|
| -- | -- | -- | -- |
| 18.02.2022 | 0.1 | Criação do documento de Casos de Uso | [Kayro César](https://github.com/kayrocesar) |




### 1. Introdução
<div align="justify">
   Casos de uso são documentos textuais utilizados para especificar requisitos e possuem um detalhamento maior que as histórias de usuário. A recomendação é sejam escritos na fase de especificação dos requisitos e geralmente são escritos pelos próprios desenvolvedores do sistema, mas podem ser compreendidos e validados pelos usuários. (VALENTE, 2020)
</div>

### 2. Metodologia
<div align="justify">
    O primeiro aspecto a ser incluso nos casos de uso, é a utilização de uma perspectiva de um ator que deseja utilizar o sistema para atingir um determinado objetivo. O ator costuma ser um usuário humano e um elemento externo em relação ao sistema. Primeiramente, o caso de uso enumera os passos a serem realizados pelo ator e cada caso possui duas listas de passos (fluxo normal e extensões). O fluxo normal é o caminho ideal a ser percorrido pelo usuário, já as extensões representam caminhos alternativos na execução de um passo ou possíveis situações de erro. (VALENTE, 2020)
</div>
<br>


### 3. Resultados


- <b> Registrar o ponto </b> 


    - <span > <b>Ator:</b></span> Funcionário de uma empresa

    - <span ><b>Fluxo Normal:</b></span> 

        - <span style=" color:#2094f3">1 -</span> Funcionário seleciona a opção de registrar o ponto
        - <span style=" color:#2094f3">2 -</span> Funcionário informa o horário do registro do ponto
        - <span style=" color:#2094f3">3 -</span> Funcionário informa alguns dados acerca do registro do ponto
        - <span style=" color:#2094f3">4 -</span> Aplicativo salva o registro do ponto
        - <span style=" color:#2094f3">5 -</span> Aplicativo mostra que o registro do ponto foi realizado com sucesso

    - <span ><b>Extensões:</b></span> 
        - <span style=" color:#2094f3">2a -</span> Funcionário informa um horário inválido (solicitar horário novamente)
        - <span style=" color:#2094f3">4a -</span> Funcionário desiste de registrar o ponto
        - <span style=" color:#2094f3">5a -</span> Aplicativo cancela a operação
    - <span ><b>RF:</b></span> [RF01, RF02, RF03, RF08, RF18](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)

 <br>
 <br>

 - <b> Registrar falta </b> 


    - <span > <b>Ator:</b></span> Funcionário de uma empresa

    - <span ><b>Fluxo Normal:</b></span> 

        - <span style=" color:#2094f3">1 -</span> Funcionário seleciona a opção de registrar falta
        - <span style=" color:#2094f3">2 -</span> Funcionário informa a duração da sua falta (dia(s) ou horas)
        - <span style=" color:#2094f3">3 -</span> Funcionário informa alguns dados acerca do registro da falta
        - <span style=" color:#2094f3">4 -</span> Aplicativo salva o registro da falta
        - <span style=" color:#2094f3">5 -</span> Aplicativo mostra que o registro da falta foi realizado com sucesso

    - <span ><b>Extensões:</b></span> 
        - <span style=" color:#2094f3">2a -</span> Funcionário informa uma duração  (dias ou horas) inválida (solicitar duração novamente)
        - <span style=" color:#2094f3">4a -</span> Funcionário desiste de registrar o ponto
        - <span style=" color:#2094f3">5a -</span> Aplicativo cancela a operação
    - <span ><b>RF:</b></span> [RF17](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)

 <br>
 <br>

- <b> Apagar registros de pontos </b>  

    - <span > <b>Ator:</b></span> Funcionário de uma empresa

    - <span ><b>Fluxo Normal:</b></span> 

        - <span style=" color:#2094f3">1 -</span> Funcionário seleciona o registro desejado
        - <span style=" color:#2094f3">2 -</span> Funcionário seleciona a opção de apagar
        - <span style=" color:#2094f3">3 -</span> Aplicativo pergunta se o usuário tem certeza da escolha
        - <span style=" color:#2094f3">4 -</span> Aplicativo apaga o registro desejado 

    - <span ><b>Extensões:</b></span>   
        - <span style=" color:#2094f3">3a -</span> Funcionário desiste de apagar o registro desejado
        - <span style=" color:#2094f3">4a -</span> Aplicativo cancela a operação
   - <span ><b>RF:</b></span> [RF05 e RF23](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)

<br>
<br>

- <b> Ativar a notificação de alarme </b> 
       
    - <span > <b>Ator:</b></span> Funcionário de uma empresa

    - <span ><b>Fluxo Normal:</b></span> 

        - <span style=" color:#2094f3">1 -</span> Funcionário seleciona a opção para ativar a notificação de alarme
        - <span style=" color:#2094f3">2 -</span> Funcionário escolhe se deseja ativar alarme para iniciar, retornar ou encerrar o trabalho 
        - <span style=" color:#2094f3">3 -</span>Funcionário define se deseja antecipar o alarme 
        - <span style=" color:#2094f3">4 -</span> Aplicativo ativa o alarme de acordo com o especificado pelo usuário

    
     - <span ><b>RF:</b></span>  [RF28](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)

<br>
<br>

- <b> Realizar Backup dos registros </b> 
       
    - <span > <b>Ator:</b></span> Funcionário de uma empresa

    - <span ><b>Fluxo Normal:</b></span> 

        - <span style=" color:#2094f3">1 -</span> Funcionário seleciona a opção para realizar o Backup
        - <span style=" color:#2094f3">2 -</span> Funcionário seleciona o tipo de backup que deseja realizar(local ou nuvem)
        - <span style=" color:#2094f3">3 -</span> Aplicativo pergunta se o usuário tem certeza da escolha
        - <span style=" color:#2094f3">4 -</span> Aplicativo apaga o registro desejado 

    - <span ><b>Extensões:</b></span>   
        - <span style=" color:#2094f3">3a -</span> Funcionário desiste fazer o backup
        - <span style=" color:#2094f3">4a -</span> Aplicativo cancela a operação
   - <span ><b>RF:</b></span>  [RF28](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)

<br>
<br>

- <b> Gerar extrato de registros </b>  
       
    - <span > <b>Ator:</b></span> Funcionário de uma empresa

    - <span ><b>Fluxo Normal:</b></span> 

        - <span style=" color:#2094f3">1 -</span> Funcionário seleciona a opção para gerar um extrato dos seus registros
        - <span style=" color:#2094f3">2 -</span> Funcionário seleciona o intervalo de datas que o extrato deve levar em conta 
        - <span style=" color:#2094f3">2 -</span> Funcionário seleciona quais critérios devem ser incluídos no extrato 
        - <span style=" color:#2094f3">3 -</span> Aplicativo gera o extrato
        - <span style=" color:#2094f3">4 -</span> Aplicativo informa que o extrato foi gerado e pergunta se o usuário deseja abri-lo 

    - <span ><b>Extensões:</b></span>  
        - <span style=" color:#2094f3">2a -</span> Funcionário seleciona o intervalo de datas inválido (solicitar o intervalo novamente)
        - <span style=" color:#2094f3">3a -</span> Funcionário desiste fazer o backup
        - <span style=" color:#2094f3">4a -</span> Aplicativo cancela a operação
    - <span ><b>RF:</b></span> [RF32](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)

<br>
<br>

 - <b> Visualizar inconsistências nos registros de ponto </b> 
       
     - <span > <b>Ator:</b></span> Funcionário de uma empresa

     - <span ><b>Fluxo Normal:</b></span> 

         - <span style=" color:#2094f3">1 -</span> Funcionário seleciona a opção para visualizar as inconsistências nos registros de ponto
         - <span style=" color:#2094f3">2 -</span> Aplicativo exibe a lista de inconsistências (cada item da lista possui uma data) e a quantidade total das mesmas

     - <span ><b>RF:</b></span>   [RF12](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  




<div align="justify">
   
</div>









<div align="center">

</div>

### 4. Legenda

RF - Requisito Funcional


### 5. Referências

>VALENTE, Marco Túlio. Engenharia de Software Moderna: Princípios e Práticas para Desenvolvimento de Software com Produtividade, 2020.

