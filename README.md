# Análise de Startups Unicórnios (2012 - 2022)
Na industria, startups privadas avaliadas em mais de US$1.000.000.000 (1 bilhão) são frequentemente identificadas como "Unicórnio". Esse termo foi popularizado em 2013, pela investidora de capital de risco Aileen Lee, em seu artigo "Bem-vindo ao Clube dos Unicórnios", onde o termo "unicórnio" foi utilizado para definir as startups e empresas privadas que atingiam o valor de US$ 1 bilhão.

## Sobre o Projeto

  
Este projeto tem como objetivo analisar a evolução temporal, setorial e geográfica das startups unicórnios (empresas privadas avaliadas em mais de US$ 1 bilhão) até o mês de setembro de 2022. O estudo possui um foco especial no continente americano, contrastando seu desempenho e volume de investimentos com as demais regiões do mundo. <br>
A análise também investiga o impacto de eventos globais, especificamente a pandemia de COVID-19, na captação de capital e na entrada de novos investidores no mercado.

 

## Fonte dos Dados
O conjunto de dados utilizados (unicorns till sep 2022.csv) foi extraido da plataforma Kaggle e contém informações detalhadas sobre a avaliação, data de entrada no status de unicórnio, país, cidade, setor e investidores das startups. <br>
##### Link para o dataset: [Unicorn Startups (Kaggle)](https://www.kaggle.com/datasets/ramjasmaurya/unicorn-startups/data)

## Análise e Principais Descobertas
### 1. A Hegemonia da América e o Domínio Global

O continente americano lidera o volume financeiro global de forma isolada, acumulando um total de US$ 2,225.35 bilhões investidos em unicórnios, valor que supera amplamente o segundo colocado, a Ásia (US$ 1,060.23 bilhões).
<figure>
  <img width="1189" height="590" alt="Gráfico de valores totais investidos" src="https://github.com/user-attachments/assets/3972f3b3-f713-4b28-94d6-158daba54054" />
 <figcaption align="center"><em><strong>Figura 1:</strong> Valor total de investimentos por continente.</em></figcaption>
 </figure>
 <br>
 <br>
<br>


A evolução temporal mostra como a América se descolou do resto do mundo na geração de valor dos últimos anos:

</figure>
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/3972f3b3-f713-4b28-94d6-158daba54054" />
<figcaption align="center"><em><strong>Figura 2:</strong> Evolução Temporal: América vs. Resto do Mundo.</em></figcaption>
 </figure>
 <br>
 <br>

 



### 2. O Cenário Interno: EUA e Polos de Inovação


Dentro da América, os Estados Unidos são o motor principal da inovação. Ao analisar a empresa de maior valor por país, a startup mais valiosa identificada é a americana SpaceX, avaliada em  US$ 127,00 Bilhões.


</figure>
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/9da86b46-d19c-4268-b13b-4018a3cd0651" />
<figcaption align="center"><em><strong>Figura 3:</strong> Maiores empresas por país na América.</em></figcaption>
 </figure>
 <br>
 <br>
 <br>
 
  
As cidade de San Francisco (168 unicórnios) e Nova York (111 unicórnios) consolidam-se como os maiores polos de startups bilionárias do continente.


</figure>
<img width="1389" height="690" alt="image" src="https://github.com/user-attachments/assets/30d96eac-c63e-42a2-85fb-2b43a299b5ce" />
<figcaption align="center"><em><strong>Figura 4:</strong> Top 10 Cidades da América.</em></figcaption>
 </figure>
 <br>
 <br>


### 3. Setores em Ascensão e Distribuição de Investimentos


Os investidores tem uma clara preferência por tecnologia escalável. Os setores líderes em captação global e na América São Fintech (US$ 855,43 bilhões) e Internet Software & Services (US$ 660,93 bilhões).


</figure>
<img width="1389" height="790" alt="image" src="https://github.com/user-attachments/assets/fadff0cf-8092-4654-95d0-5c8de80594f8" />
<figcaption align="center"><em><strong>Figura 5:</strong> Top 10 Setores por Investimento.</em></figcaption>
 </figure>
 <br>
 <br>
 <br>


A evolução cumulativa desses segmentos comprova que o foco em finanças e softwares se manteve constante e dominante ao longo da última decáda.


</figure>
<img width="1385" height="690" alt="image" src="https://github.com/user-attachments/assets/f472fc57-e71c-46a8-a83e-3fd6abe98433" />
<figcaption align="center"><em><strong>Figura 6:</strong> Evolução Cumulativa dos 5 Maiores Setores.</em></figcaption>
 </figure>
 <br>
 <br>

### 4. O "Efeito Pandemia" no Capital de Risco
Contrariando as expectativas de retração geradas pela crise da COVID-19, o mercado de investimentos demonstrou forte resiliência. O número de investidores aportando capital aumentou significativamente no recorte de 2020 a 2022 em comparação com os anos anteriores.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/04e86360-fb0d-4d85-b337-1acc2a9b81c8" width="100%"> 
      <br>
      <em>Figura 7: Efeito pandemia - Heatmap Investidores (pré e pós pandemia).</em>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/22da9e01-9d98-4345-8dd1-e1984895e0ef" width="100%"> 
      <br>
      <em>Figura 8: Efeito pandemia - Heatmap Investidores (2018 a 2020 e 2020 a 2022).</em>
    </td>
  </tr>
</table>



































## Introdução
 Por definição, as startups podem ser consideradas empresas emergentes que possuem como principal objetivo a aprimoração de um modelo de negócio (X), onde a principal base para seu desenvolvimento é o uso da tecnologia. <br> <br>
Este estudo tem como objetivo analisar a evolução das startups unicórnios até o ano de 2022, com um foco no território americano, fornecendo comparações globais para contextualizar o cenário. A análise abrange a distribuição geográfica, setorial, temporal e o impacto de eventos significativos, como a pandemia de COVID-19, no ecossistema de investimentos. O dataset utilizado foi obtido do Kaggle, intitulado 'unicorns till sep 2022.csv'.









  



Com os olhos focados no continente Americano,





Este estudo tem como objetivo analisar a evolução das startups em território americano até o ano de 2022.

