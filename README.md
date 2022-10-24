# Pesquisa de Preços
 Demonstração de conhecimentos sobre Automação de Processos, Automação Web e Dataframes para automatizar pesquisa de preços de produtos específicos em sites de compras

### Descrição dos arquivos:
- Pesquisa de Preços.ipynb - arquivo Jupyter onde se encontra a resolução do projeto
- Tabelas de Preços - pasta de tabelas em formato Excel geradas após a busca, contendo informações sobre as ofertas encontradas
- buscas.xlsx - tabela em formato Excel, com produtos requisitados para busca de preços, e filtros a serem aplicados na busca

### Passo a passo:
- Importar arquivos e bibliotecas
- Criar navegador: usar o Selenium para criar um navegador do Google Chrome para realizar buscas no Buscapé e no Google Shopping (exemplos de alguns dos vários sites de compras disponíveis para esse projeto)
- Abrir dataframe de buscas a serem feitas: abrir buscas.xlsx com o Pandas
- Pegar ofertas no Google Shopping de apenas um produto (iPhone): código de referência a ser usado para o próximo passo
- Pegar oferta de vários produtos no Google Shopping: automatizar busca com todos os produtos em buscas.xlsx no Google Shopping e criar uma planilha com as ofertas encontradas
- Pegar ofertas no Buscapé de apenas um produto (iPhone): código de referência a ser usado para o próximo passo
- Pegar oferta de vários produtos no Buscapé: automatizar busca com todos os produtos em buscas.xlsx no Buscapé e criar uma planilha com as ofertas encontradas
- Fechar o navegador, por não estar mais sendo usado
- Salvar planilhas em uma pasta de backup: criar uma pasta de backup ("Tabela de Preços"), e salvar planilhas de ofertas do Google Shopping e do Buscapé nessa pasta
- Enviar e-mail para área de compras: enviar e-mail com planilhas de ofertas para a área de compras de uma empresa hipotética
