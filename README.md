# Fontes de Dados  

Temos cinco arquivos de formato CSV que representam dados de vendas de produtos relacionados ao "Meganium" e uma versão atualizada chamada "Anbernic". Os arquivos estão segmentados por plataforma (Etsy, Shopee, AliExpress) ou agrupados: 

  - "Meganium_Sales_Data.csv": Arquivo principal com todas as vendas.
  - "Meganium_Sales_Data_-_AliExpress.csv", "Meganium_Sales_Data_-_Etsy.csv", "Meganium_Sales_Data_-_Shopee.csv": Segmentos por marketplace.
  - "Updated_Anbernic_Sales_Data.csv": Versão atualizada com dados renomeados como "ANBERNIC".
     

# Objetivo  

Temos que comparar os dados dos arquivos para identificar padrões de venda, performance por região, produto mais vendido, eficiência dos cupons, etc e realizar alguns prompts de insight.

# Perguntas iniciais da IA sobre os arquivos

  - Qual é o volume total de vendas por produto? E qual produto trouxe maior faturamento? Qual moeda foi utilizada para transações?
  - Qual plataforma gerou mais receita: Etsy, Shopee ou AliExpress?
  - Há diferença significativa nos valores médios por venda entre plataformas?
  - Quais meses tiveram maior número de vendas?
  - Houve sazonalidade? Como isso impacta a estratégia?
  - Qual cupom proporcionou maior desconto médio?
  - Houve correlação entre uso de cupom e aumento de quantidade vendida?
  - Quais países compraram mais?
  - Há relação entre país e tipo de produto comprado?
  - Houve mudança significativa nos preços?
  - A linha "Anbernic" parece ser uma rebranding ou uma nova geração?

 # Prompts gerados pelas perguntas

 - 1° Com base nos cinco arquivos fornecidos, especifique qual a plataforma (Etsy, Shopee ou AliExpress) mais vendeu e mostre em forma decrescente uma tabela cada plataforma "quantidade de produtos vendidos", a "receita de todos produtos vendidos (na moeda da transação)" e "5 produtos mais vendidos".
 - 2° Com base nos cinco arquivos fornecidos, forneça 5 linhas de forma decrescente para cada país uma tabela mostrando "produtos mais vendidos"(mostre a moeda utilizada), e "meses mais vendidos".
 - 3° O número de vendas aumentou após a aplicação de cupons? Procure aprofundar se existe correlação de "país x cupom", assim como "produto x cupom".
    
# Respostas e conclusão

  - Shopee foi a plataforma com maior volume de vendas e receita.
  - Países com destaque:  Canadá lidera número de vendas, seguido por EUA e Alemanha.
  - Impacto dos cupons:  Houve aumento significativo nas vendas com o uso de cupons (média de 40%), especialmente em produtos como RG 40XXV e RG35XX.
  - Sazonalidade:  Julho e agosto foram os meses com maior movimento comercial.

    O produto NEW MEGANIUM RG 40XXV  foi o mais vendido, com 37 unidades comercializadas no período analisado e com destaque no Canadá (via Shopee e Etsy). Ele aparece consistentemente em todas as plataformas e apresenta cerca de 35% dos pedidos com cupons promocionais, sugerindo melhoria comercial. A plataforma Shopee  liderou as vendas deste modelo, respondendo por cerca de 65% das transações.

# Crítica sobre as respostas e feedback

  - Mas a plataforma Shopee foi líder em todos os países?  E manteve a receita  e vendas mais altas?
    
    - Shopee liderou em Canadá, Reino Unido e globalmente  em volume total de vendas.
    - AliExpress  se destacou em vendas para EUA e Alemanha.
    - Etsy  teve desempenho forte na Austrália e no Reino Unido.
      
  - O Impacto dos cupons ocorreu em todos os países e para todos os produtos?
    
    - Cupons tiveram maior impacto no Canadá e Reino Unido .
    - Produtos como RG40XXV e RG35XX responderam melhor ao uso de cupons .
    - Nem todos os países nem todos os produtos respondem da mesma forma.    

  - Sobre a Sazonalidade, Julho e agosto foram os meses com maior movimento comercial em todos os países?

    - Julho e agosto foram meses fortes globalmente , especialmente para Canadá, Alemanha e Reino Unido .
    - EUA e Austrália mostraram picos um pouco diferentes , sugerindo que fatores locais (como feriados ou promoções) podem ter influenciado mais que a sazonalidade pura.

# Olhar crítico

É perceptível visualmente que em julho e agosto venderam muito pois agosto foi presente em 4 países (menos no Reino Unido). Mas precisamos observar que em julho foi presente apenas em 2 países (Canadá e Alemanha), assim como em novembro (Reino Unido e Canadá). Por último setembro esteve presente em 3 países (Austrália, Estados Unidos e Reino Unido). 

Ao meu ver entre julho e agosto deveriam ter menos cupons de incentivo de compra para RG35XX (mas nos outros produtos daria cupons) nos USA (porque não aderiu a cupons) e mais cupons de incentivo de compra para Austrália no mesmo período, enquanto em setembro faria uma liquidação nesses 2 países (sem esperar por outubro e novembro). No caso do Canadá e Reino Unido daria cupons de incentivo de compra ou liquidação em novembro.
     
