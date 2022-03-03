# Casos de Uso


### Histórico de versão

|Data | Versão | Modificação | Autor(es)|
| -- | -- | -- | -- |
| 18.02.2022 | 0.1 | Criação do documento de Casos de Uso | [Kayro César](https://github.com/kayrocesar) |




### 1. Introdução
<div align="justify">
   Casos de uso são documentos textuais utilizados para especificar requisitos e possuem um detalhamento maior que as histórias de usuário. A recomendação é sejam escritos na fase de especificação dos requisitos e geralmente são escritos pelos próprios desenvolvedores do sistema, mas podem ser compreendidos e validados pelos usuários. 
</div>

### 2. Metodologia
<div align="justify">
    O primeiro aspecto a ser incluso nos casos de uso, é a utilização de uma perspectiva de um ator que deseja utilizar o sistema para atingir um determinado objetivo. O ator costuma ser um usuário humano e um elemento externo em relação ao sistema. Primeiramente, o caso de uso enumera os passos a serem realizados pelo ator e cada caso possui duas listas de passos (fluxo normal e extensões). O fluxo normal é o caminho ideal a ser percorrido pelo usuário, já as extensões representam caminhos alternativos na execução de um passo ou possíveis situações de erro. 
</div>
<br>





- <b> Transferir Valores entre Contas </b>

    - <span > <b>GOAL 0:</b></span> Acessar o site da Prefeitura

        - <span ><b>GOAL 1:</b></span> Acessar a guia "Fala cidadão"

             -  <span style=" color:#2094f3">OP 1.1:</span> Deslocar o mouse até o topo no centro da página inicial
             - <span style=" color:#2094f3">OP 1.2:</span> Apertar com botão esquerdo do mouse em "Fala Cidadão"

        - <span ><b>GOAL 2:</b></span> Preencher formulário de informações

            - <span style=" color:#2094f3">OP 2.1:</span> Preencher o campo "Nome"
            - <span style=" color:#2094f3">OP 2.2:</span> Preencher o campo "Email"
            - <span style=" color:#2094f3">OP 2.3:</span> Preencher o campo "Telefone"
            - <span style=" color:#2094f3">OP 2.4:</span> Preencher o campo "Assunto"
            - <span style=" color:#2094f3">OP 2.5:</span> Preencher o campo "Mensagem"
            - <span style=" color:#2094f3">OP 2.6:</span> Anexar documento ou foto 
            - <span style=" color:#2094f3">OP 2.7:</span> Preencher o captcha
             - <span style=" color:#2094f3">OP 2.8:</span> Deslocar o mouse até o botão "Enviar"
            - <span style=" color:#2094f3">OP 2.8:</span> Apertar com o botão esquerdo do o mouse 


        Transferir Valores entre Contas

        Ator: Cliente do Banco

        Fluxo normal:

        1 - Autenticar Cliente (sublinhado)

        2 - Cliente informa agência e conta de destino da transferência

        3 - Cliente informa valor que deseja transferir

        4 - Cliente informa a data em que pretende realizar a operação

        5 - Sistema efetua transferência

        6 - Sistema pergunta se o cliente deseja realizar uma nova transferência

        Extensões:

        2a - Se conta e agência incorretas, solicitar nova conta e agência

        3a - Se valor acima do saldo atual, solicitar novo valor

        4a - Data informada deve ser a data atual ou no máximo um ano a frente

        5a - Se data informada é a data atual, transferir imediatamente

        5b - Se data informada é uma data futura, agendar transferência





### 3. Resultados

<div align="justify">
   
</div>









<div align="center">

</div>

### 4. Legenda

RF - Requisito Funcional


### 5. Referências

>VALENTE, Marco Túlio. Engenharia de Software Moderna: Princípios e Práticas para Desenvolvimento de Software com Produtividade, 2020.

