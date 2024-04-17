# RH Attrition Analysis 

## Objetivo do Estudo:
Este estudo visa analisar a rotatividade de colaboradores em uma empresa, fornecendo insights para o departamento de Recursos Humanos desenvolver estratégias eficazes de retenção de talentos.

## Importância da Rotatividade de Colaboradores:
A rotatividade de funcionários pode esgotar recursos internos e impactar negativamente a produtividade. Este projeto visa compreender os fatores que contribuem para a rotatividade e fornecer recomendações para mitigar esse problema.

## Tecnologias Utilizadas:

### Análise em Python
Utilizamos Python, juntamente com as bibliotecas Plotly e Seaborn, para analisar os dados. A documentação e análises foram feitas diretamente no notebook. 
Veja mais detalhes abaixo:
 - 🔗 [Notebook](https://nbviewer.org/github/milexias/hr-attrition/blob/main/attrition_analysis.ipynb)

**Prévia de alguns insights obtidos:**

A taxa de rotatividade de 16% é considerada alta, indicando a necessidade de investigar os motivos por trás da saída dos funcionários.
<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/ex_funcionarios.png"/>
</p>

Vamos olhar os índices de satisfação dos funcionários atuais para tentarmos entender os motivos de tamanha rotatividade.

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/satisfacao_geral.png"/>
</p>

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/ambiente_trabalho.png"/>
</p>

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/estado_civil.png"/>
</p>

Funcionários com baixa satisfação e status civil de solteiro ou divorciado têm maior probabilidade de deixar a empresa.

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/renda_genero.png"/>
</p>

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/renda_educacao.png"/>
</p>

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/renda_area_atuacao.png"/>
</p>

Não há disparidades salariais por gênero, mas a remuneração está correlacionada com o nível educacional.

Podemos perceber também que a distribuição salarial é bem próxima nas diferentes áreas, se sobressaindo a área de Recursos Humanos com a maior variação salarial. 

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/idade_funcionarios.png"/>
</p>

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/idade_anos_trabalho.png"/>
</p>

Uma distribuição equilibrada de idades indica uma força de trabalho diversificada.

### Dashboard em Power BI

Desenvolvemos um dashboard para fornecer uma visão geral do perfil dos funcionários que deixaram a empresa. 

<p align="center">
  <img src="https://github.com/milexias/hr-attrition/blob/main/imagens/dash_hr_attrition.png"/>
</p>

Faça o download do Dashboard para explorar mais detalhes.
 - 🔗 [Dashboard](https://github.com/milexias/hr-attrition/blob/main/Hr_Attrition.pbix)

## Fonte de Dados:
Os dados foram coletados do Kaggle e categorizados para análise.

**Links para me acharem:**
* [LinkedIn](https://www.linkedin.com/in/alexia-ssantos/)
* [GitHub](https://github.com/milexias)
