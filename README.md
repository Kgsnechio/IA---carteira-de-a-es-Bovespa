# IA_Carteira-de-acoes_Bovespa 

Analise de balanços e DREs das empresas do BOVESPA para criação de uma inteligencia artificial que seleciona dentre as empresas quais comprar

Para prever proximas carteiras 
   - devemos criar um DF com 'Fornecedores', 'Outros Ativos Circulantes', 'Lucros/Prejuízos Acumulados', 'Resultado Antes Tributação/Participações', 'Ativo Total', 'Obrigações Sociais e Trabalhistas', 'Obrigações Fiscais', 'Custo de Bens e/ou Serviços Vendidos', 'Resultado da Equivalência Patrimonial', 'Tributos Diferidos' nos campos para cada uma das empresas naquele trimestre
   - ao rodar: ' previsao = modelo_ia.predict(df) ' ele vai retornar uma lista onde 0 representa 'Vender' e dois 'Comprar'
   - basta comparar essa lista com a lista de empresas no df
  
Para finalizar de forma eficiente esse projeto falta altomatizar a busca das informações das empresas de forma automatizada: (ia para quebra de CAPTCHA do site)

O resultado até o momento é um arquivo com uma inteligencia artificial que faz a seleção das empresas.
