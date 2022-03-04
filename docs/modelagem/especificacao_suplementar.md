# <center> Especificação Suplementar

## Histórico de versão<br>

|    Data    | Versão |                Modificação                |       Autor        |
| :-------- | :---- | :--------------------------------------- | :---------------- |
| 04/03/2022 |  0.1   | Criação do documento |  [José Luís](https://github.com/joseluis-rt)   |
| 04/03/2022 |  0.2   | Elaboração do texto |  [José Luís](https://github.com/joseluis-rt)   |
| 04/03/2022 |  0.3   | Adição de imagens |  [José Luís](https://github.com/joseluis-rt)   |


## 1. Definição
&emsp;&emsp;Este documento tem como objetivo verificar a especificação suplementar para detectar possíveis erros e defeitos antes de finalizar o projeto.
  
&emsp;&emsp;Para a especificação suplementar, será analisado a forma como foram levantados e documentados os requisitos não funcionais de usabilidade, confiabilidade, desempenho e suportabilidade. Desse modo utilizamos a metodologia FURPS+ para fazer essa verificação.
  
&emsp;&emsp;FURPS+ é básicamente um um acrónimo que representa um modelo para classificação de atributos de qualidade de software (conhecidos como requisitos funcionais e não-funcionais).

## 2. Finalidade
&emsp;&emsp;O objetivo desse documento é definir os requisitos do aplicativo Ponto Fácil. Trabalhando ao lado dos "casos de uso" na finalidade de identificar os requisitos do sistema. Explicitar os requisitos não funcionais do sistema é importante para deixar desenvolvedores e stakeholders atualizados quanto aos atributos de qualidade, usabilidade, confiabilidade, desempenho e suportabilidade.

## 3. Metodologia
&emsp;&emsp;O FURPS+ como já dito antes é um sistema para a classificação de requisitos, cada caracter representa categorias que podem ser usadas na definição de requisitos, bem como esclarece atributos de Qualidade de Software.

### 3.1 Participantes
|Integrantes |
| -- |
|[José Luís Ramos Teixeira](https://github.com/joseluis-rt)|

### 3.2 F - Funcionality (Funcionalidade)
&emsp;&emsp;Representa todo aspecto funcional do software, ou seja seus requisitos. É uma categoria com diversas subcategorias que variam de acordo com a aplicação. Sua medição considera, principalmente, o cumprimento dos requisitos especificados.
  
&emsp;&emsp;Podendo incluir:
- Conjuntos de recursos;
- Recursos;
- Segurança.

### 3.3 U - Usability (Usabilidade)
&emsp;&emsp;É o atributo que avalia a interface com o usuário. Possui diversas subcategorias.
  
&emsp;&emsp;Podendo incluir:
- Fatores humanos
- Estética
- Consistência na interface com o usuário
- Ajuda on-line e sensível ao contexto
- Assistentes e agentes
- Documentação do usuário
- Materiais de treinamento

### 3.4 R - Reliability (Confiabilidade)
&emsp;&emsp;Refere-se a integridade, conformidade e interoperabilidade do software.
  
&emsp;&emsp;Podendo incluir:
- Freqüência e gravidade de falha
- Possibilidade de recuperação
- Possibilidade de previsão
- Precisão
- Tempo médio entre falhas (MTBF)

### 3.5 P - Performance (Performance)
&emsp;&emsp;Avalia os requisitos de desempenho do software. Podendo usar como medida diversos aspectos. 
  
&emsp;&emsp;Podendo incluir:
- Velocidade
- Eficiência
- Disponibilidade
- Produtividade
- Tempo de resposta
- Tempo de recuperação
- Uso de recurso

### 3.6 S - Suportability (Suportabilidade)
&emsp;&emsp;Os requisitos de suportabilidade agrupam várias características.
  
&emsp;&emsp;Podendo incluir:
- Possibilidade de teste
- Extensibilidade
- Possibilidade de adaptação
- Possibilidade de manutenção
- Compatibilidade
- Possibilidade de configuração
- Possibilidade de serviço
- Possibilidade de instalação
- Possibilidade de localização (internacionalização)

### 3.7 "+"
&emsp;&emsp;O “+” do acrônimo engloba outros requisitos não-funcionais que devem ser lembrados.

&emsp;&emsp;São eles:
- Requisitos de Design
- Requisitos de implementação
- Requisitos de interface
- Requisitos físicos

<center>
  
<p align = "center"><img src="../../../assets/imagens/FURPS_resumo.jpg"></p><br>
  
<figcaption>Imagem 1: Modelo FURPS+ resumido</figcaption>
  
</center>

<br>

## 4.Resultados
&emsp;&emsp;Como resultado da identificação dos requisitos levantados na etapa de "elicitação de requisitos":
  
**Legenda**:

* F: Funcionalidade
* U: Usabilidade
* R: Confiablidade
* P: Perfomance
* S: Suportabilidade
* +: Outros
* RF: Requisito Funcional
* RNF: Requisito Não Funcional

<center>

| Sigla | Requisitos | Tipo de requisito |
| :------: | :-------: | :--------------:  |
| F | "O aplicativo deve garantir a segurança dos dados do usuário" | RNF04 |
| U | "O aplicativo deve ter opções de linguagem (português e inglês)" | RNF01 |
| R | - |
| P | "O aplicativo deve ser capaz de armazenar o backup em contas do Google Drive e Dropbox" e "O aplicativo deve ser capaz de calcular o saldo de horas com base no registro do ponto e tolerância" | RNF07 e RNF08 |
| S | "O Sistema deverá ser acessível por meio de dispositivos móveis" | RNF02 |
| + | "O aplicativo deve ter opções de tema (claro e escuro)" e "O Sistema deve ter layout compreensível e objetivo" | RNF03 e RNF05 |

<figcaption>Tabela 1: Divisão dos requisitos a partir da metodologia FURPS+</figcaption>

</center>

<br>


## 5. Gráfico dos Requisitos a partir do modelo FURPS+

### Gráfico
  
<center>

<p align = "center"><img src="../../../assets/imagens/FURPS_grafico.jpg"></p><br>
  
<figcaption>Gráfico 1: Categorização dos requisitos não funcionais pelo modelo FURPS+</figcaption>

</center>

<br>
  
## 6. Referências

> [1] - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13;
  
> [2] - https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html
  
> [3] - https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/concepts/requirements_62E28784.html
  
> [4] - https://qualidadebr.wordpress.com/2008/07/10/furps/

