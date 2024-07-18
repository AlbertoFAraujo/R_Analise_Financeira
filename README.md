![image](https://github.com/user-attachments/assets/132c1008-3e8a-4da4-9f14-0581b226ab82)

### Tecnologias utilizadas: 
| [<img align="center" alt="R_studio" height="60" width="60" src="https://github.com/AlbertoFAraujo/R_Petrobras/assets/105552990/02dff6df-07be-43dc-8b35-21d06eabf9e1">](https://posit.co/download/rstudio-desktop/) |
|:---:|
| R Studio |

- **RStudio:** Ambiente integrado para desenvolvimento em R, oferecendo ferramentas para escrita, execução e depuração de código.
<hr>

### Objetivo

O objetivo deste mini-projeto é unir duas poderosas ferramentas de análise de dados para resolver um problema de negócio: Linguagem SQL será usada para análise exploratória de dados através do pacote sqldf e Linguagem R será usada para análise estatística.

### Problema de Negócio:

Uma rede de hospitais gostaria de compreender as variáveis relacionadas aosgastoscom internações hospitalares de pacientes.Usaremos  dados  de  uma pesquisa  nacional  de  custos  hospitalares  realizada  pela  US Agency  for  Healthcare que consiste  em  registros  hospitalares  de  amostras  de  pacientes internados. Os dados fornecidos são restritos à cidade de Wisconsin e referem-se a pacientes na faixa etária de 0 a 17 anos.

Vamos separar o trabalho em duas etapas. Na etapa 1 vamos explorar os dados usando Linguagem  SQL  e  responder  10  perguntas  de  negócio.  Na  etapa  2  vamos  realizar  análise estatística com Linguagem R através do Teste ANOVA e Regressão Linear e responder 7 perguntas de negócio.

1.   Quantas raças estão representadas no dataset?
2.   Qual a idade média dos pacientes?
3.   Qual a moda da idade dos pacientes?
4.   Qual a variância da coluna idade?
5.   Qual o gasto total com internações hospitalares por idade?
6.   Qual idade gera o maior gasto total com internações hospitalares?
7.   Qual o gasto total com internações hospitalares por gênero?
8.   Qual a média de gasto com internações hospitalares por raça do paciente?
9.   Para  pacientes  acima  de  10  anos,  qual  a  média  de  gasto  total  com  internações hospitalares?
10.  Considerando o item anterior, qual idade tem média de gastos superior a 3000?


### Dicionário de dados:
- AGE: Idade do paciente
- FEMALE: Variável binária que indica se o paciente é do sexo feminino
-LOS: (Length of stay) Tempo da internação do paciente
- RACE: Raça do paciente
-TOTCHG: Custo da internação
- APRDRG: Grupo de diagnóstico refinado do paciente

>**Referências:** Formação Cientista de dados (Data Science Academy: https://www.datascienceacademy.com.br)
