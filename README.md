# 📊 Análise de Performance de Varejo: Estratégia de Desinvestimento - Challenge Alura Store (ONE - G9)

## Objetivo do projeto

Este projeto consiste em uma análise multidimensional da performance das filiais da rede do Sr. João, com o objetivo de fundamentar uma decisão de desinvestimento (venda de unidade).

Através da integração de dados financeiros e qualitativos, o estudo avalia a saúde das operações não apenas pelo faturamento bruto, mas pela eficiência na conversão de esforço logístico em valor (%Ratio) e pela taxa de fidelização e satisfação do cliente (Análise de Detratores).

Limitações: dada a ausência de dados de custo operacional, esta análise utiliza métricas de eficiência de faturamento e sentimento do consumidor como os principais proxies (indicadores substitutos) para inferir a viabilidade econômica e a saúde futura das filiais

## I. Analise exploratoria e Métricas 🕵

### 1. Faturamento 📊

  A partir de uma análise consolidada do faturamento, observa-se a Loja 1 como líder de performance (26,13% do faturamento), enquanto a Loja 4 figura como o ponto de atenção da rede (23,58%).

<img width="575" height="227" alt="image" src="https://github.com/user-attachments/assets/c2cfd9ca-48db-4351-8c28-98c67304a94c" />

  O cenário crítico da Loja 4 não se resume ao menor volume financeiro, mas à sua perda de eficiência: enquanto as demais unidades sustentaram seus patamares, a Loja 4 apresenta uma retração consistente no Ticket Médio, atingindo seu pior nível no Q1 de 2023.

<img width="575" height="308" alt="image" src="https://github.com/user-attachments/assets/b1d6c4e7-05ba-468f-a448-f58f26cf6fff" />

  Essa disparidade sugere que a operação da Loja 4 está perdendo tração comercial em um ritmo acelerado, tornando-se menos competitiva mesmo em períodos de recuperação da rede.

### 2. Vendas por categoria de produto 💵

  Observa-se que o tipo de produto com maior valor em vendas são os eletronicos, sendo responsavel por 37,7 % do total de vendas, seguido dos eletrodomesticos com 30% e dos moveis com 17%

<img width="660" height="295" alt="download" src="https://github.com/user-attachments/assets/64d3e83c-d89d-4f06-b27f-0809af1e55de" />

  No tocante ao volume de vendas, as categorias que mais vendem são moveis (19,99%), seguidos pelos eletronicos (18,78%) e brinquedos (13,67%).

<img width="660" height="295" alt="download 2" src="https://github.com/user-attachments/assets/53e45a85-e508-405a-9b9a-c1f6cd9fd3ba" />

  Para mensurar a qualidade da venda e comparar essas grandezas (valor / volume), desenvolveu-se o Índice de Eficiência da Receita (IER). Esta métrica confronta o Valor (potencial de receita) com o Volume (esforço logístico/manuseio). Calculado pela razão: '%Valor da categoria (em relação ao faturamento total)' / '%Volume  da categoria (em relação ao volume total)'. Um IER alto indica máxima geração de caixa com o mínimo de movimentação física.

<img width="575" height="354" alt="image" src="https://github.com/user-attachments/assets/3d021026-af90-4ccf-be07-b8252ea93992" />
<img width="372" height="354" alt="image" src="https://github.com/user-attachments/assets/d53b25f8-c324-4a08-bac7-c6833f3f7c39" />

  A partir do IER, podemos ver que os eletrodomesticos apresentam uma performance melhor que os eletronicos com uma margem considerável. Em contrapartida, todas as demais categorias performam muito inferiormente aos eletronicos e eletrodomesticos, padrão que se repete em todas as lojas.
  
  Um ponto critico a se notar é que cerca de 41,07% do esforço logístico (volume vendido) gera apenas 7,09% da receita (categorias Esporte,Brinquedos, Utilidades e Livros). Esse fato não é isolado e esta presente em todas as lojas

  Recomenda-se uma análise de custos sobre essas categorias para investigar se estão gerando lucro.

  Por fim, quando observado o ticket médio, nota-se que nas categorias com melhor retorno estimado (Eletronicos e Eletrodomesticos) a loja 4 performa abaixo de todas as demais.
<img width="879" height="414" alt="image" src="https://github.com/user-attachments/assets/37d84ea3-9871-4c7a-af26-d4fc26841046" />

### 3. Média de Avaliação das Lojas 📈

Na análise agregada, as médias de avaliação apresentem uma estabilidade aparente:
<img width="625" height="414" alt="media_ava" src="https://github.com/user-attachments/assets/394670dd-e3fa-4705-b179-df5e46e82a5a" />

Para investigar mais a fundo o centário, foi aplicada uma análise de detratores (quanto as notas 1 e 2 representam do total das avaliações).  Com essa métrica, revela-se um cenário alarmante: a Loja 4 apresenta a segunda maior taxa de insatisfação da rede (16,75%), o que, somado ao seu baixo desempenho financeiro, cria um cenário de baixa atratividade operacional.
<img width="625" height="214" alt="image" src="https://github.com/user-attachments/assets/8eebba75-0e62-4e60-bb3b-780aa3fe1f39" />

Enquanto o volume de detratores da Loja 1 (líder em vendas) exige uma revisão urgente de processos de escala, a situação da Loja 4 é mais crítica por ser cumulativa: ela falha em gerar receita e falha em satisfazer o cliente. Em um cenário de otimização de ativos, a Loja 4 se consolida como o principal gargalo da rede, onde o investimento necessário para recuperar a imagem e o faturamento dificilmente trará o retorno esperado. Portanto, o aspecto qualitativo ratifica a recomendação de venda imediata da filial.

### 4. Produtos mais e menos vendidos 📦

A análise do mix de produtos confirma a fragilidade da Loja 4. Enquanto a rede traciona seu faturamento através de itens de alto ticket (Geladeiras e Lavadoras), a Loja 4 apresenta um descompasso estratégico: seus itens mais vendidos são de baixo valor agregado (Livros e Utilidades), enquanto os 'motores de receita' da companhia figuram entre os seus menos vendidos.

<img width="1015" height="320" alt="image" src="https://github.com/user-attachments/assets/b96aaa43-4dda-4484-91ed-d2a8acbfb5ee" />
<img width="1015" height="288" alt="image" src="https://github.com/user-attachments/assets/773826d5-19df-469e-9e9b-d776ad0eca0c" />

Além do baixo faturamento, essa configuração implica em ineficiência operacional: a filial concentra seu esforço logístico e espaço de armazenamento em categorias como Móveis, que possuem alto custo de ocupação e menor retorno relativo, sem converter as vendas premium que justificariam tal operação. Em suma, a Loja 4 opera com o custo de uma loja de departamentos, mas com o ticket médio de uma loja de conveniência.

### 5. Eficiência logística - frete médio por Loja 🚅

A análise de eficiência logística revela um paradoxo: embora a Loja 4 tenha o menor frete absoluto (R$ 31,28), ela detém um dos maiores Pesos Logísticos (5,54%).

<img width="499" height="244" alt="image" src="https://github.com/user-attachments/assets/9d49b88a-b5b4-49d8-a027-717cdec4358e" />

Dado que o frete é custeado pelo cliente, esse indicador atua como uma barreira de conversão invisível. Enquanto as outras lojas diluem o custo de transporte em produtos de alto valor, a Loja 4 sobrecarrega o consumidor com um custo de frete proporcionalmente alto para itens de baixo ticket. Isso reforça a tese de que a filial está mal posicionada: ela não atrai vendas de alto valor e torna as vendas de baixo valor menos competitivas para o bolso do cliente

## II. Conclusão Final e Recomendações 📋
Após uma análise profunda das dimensões financeiras, operacionais e qualitativas da rede, a recomendação estratégica para o Sr. João é o desinvestimento (venda) da Loja 4.

### 1. Justificação da Recomendação (O Caso da Loja 4)
A Loja 4 apresenta um quadro de ineficiência estrutural, suportado pelos seguintes pilares:

* **Baixa Conversão de Valor**: Embora o volume de vendas seja equiparável ao das outras unidades, a Loja 4 detém o menor Ticket Médio da rede. A filial falha em converter itens "motores de receita" (Eletrodomésticos e Eletrónicos), concentrando o seu esforço em categorias de baixo valor agregado.

*   **Desequilíbrio Logístico:** A unidade apresenta o menor frete absoluto, mas o maior Peso Logístico (5,54%). Como o frete é pago pelo cliente, este custo atua como uma barreira invisível que impede a venda de produtos mais caros, tornando a loja menos competitiva no seu mercado local.

*   **Fragilidade Qualitativa:** A Loja 4 possui a segunda maior taxa de detratores (16,75%). Ao contrário de lojas de alto volume, onde o erro é uma questão de escala, na Loja 4 a insatisfação é um sintoma de ineficiência operacional que não se justifica pelo retorno financeiro.

### 2. Observação Crítica: Gestão de Risco na Loja 1

Embora a Loja 1 seja a líder em faturamento, a análise de satisfação revelou um sinal de alerta: **a maior taxa de insatisfação da rede (17,17%).**

**Recomendação:** Antes de reinvestir o capital da venda da Loja 4, recomenda-se uma auditoria de processos na Loja 1 para evitar que o faturamento seja comprometido pela perda de reputação a longo prazo.

### 3. Veredito Técnico
A Loja 4 opera hoje com o **custo de uma loja de departamentos, mas com a rentabilidade de uma loja de conveniência**. A manutenção desta unidade representa um custo de oportunidade alto, visto que o esforço logístico e de pessoal não se traduz em margem ou saúde de marca.

**Ação Recomendada:** Proceder com a liquidação do estoque e venda da licença da filial 4, focando recursos na otimização logística das demais unidades.

