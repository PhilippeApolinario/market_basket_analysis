# Análise de Cesta de Compras com Algoritmo Apriori (MBA - Market Basket Analysis)

## 1. Introdução

Este projeto utiliza a técnica de **Market Basket Analysis (MBA)**, ou Análise de Cesta de Compras, para identificar padrões de compra e associações entre itens frequentemente adquiridos juntos. Esta técnica é amplamente aplicada no varejo e e-commerce para entender o comportamento de compra dos consumidores e otimizar estratégias de marketing e estoque.

## 2. Objetivo

O objetivo deste projeto é aplicar o algoritmo Apriori para descobrir regras de associação entre produtos, otimizando estratégias de vendas, como promoções direcionadas e layout de lojas. Além disso, o projeto visa melhorar a recomendação de produtos em plataformas de e-commerce.

## 3. Fonte de Dados

Os dados utilizados no projeto foram extraídos de um conjunto de dados de transações de um varejista, contendo informações sobre pedidos, produtos, corredores, e departamentos. Os dados foram processados utilizando a biblioteca Pandas e Dask para lidar com grandes volumes de dados de forma eficiente.

## 4. Principais Análises Realizadas

Algumas das principais análises realizadas neste projeto incluem:

- **Identificação de Padrões de Compra**: Descoberta de itens frequentemente comprados juntos.
- **Análise de Reorder por Corredor e Departamento**: Avaliação das taxas de reordenação para otimizar o layout e o estoque.
- **Regras de Associação**: Aplicação do algoritmo Apriori para gerar regras de associação entre produtos.
- **Análise de Horários de Pico e Dias da Semana**: Identificação dos períodos com maior volume de pedidos.
- **Análise de Produtos Mais Reordenados**: Identificação dos produtos com maior taxa de recompra.

## 5. Resultados

A análise da cesta de compras forneceu insights valiosos sobre o comportamento de compra dos consumidores, permitindo otimizar estratégias de marketing e estoque. A aplicação do algoritmo Apriori revelou associações úteis entre produtos, que podem ser utilizadas para melhorar a experiência do cliente e aumentar as vendas.

## Estrutura do Projeto

- **data/**: Contém os arquivos de dados utilizados no projeto.
- **Notebook** com o código de análise e visualização.

## Utilização

### Dependências

- **Sistema Operacional**:
  - Windows 10 ou 11
  - Ubuntu 24.04 LTS (Noble Numbat)

- **Bibliotecas Python**:
  - Pandas
  - Dask
  - Matplotlib
  - Datetime
  - Efficient-Apriori

## Instalação

**Clone o repositório:**
```bash
git clone https://github.com/PhilippeApolinario/market_basket_analysis.git
cd market_basket_analysis
```
**Crie um ambiente virtual e ative-o:**
```bash
python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`
```
**Instale as dependências:**
```bash
pip install -r requirements.txt
```

## Uso

**Carregue os dados:**  
Os dados devem ser colocados na pasta **data/**.

**Execute o notebook:**  
Abra **market_basket_analysis.ipynb** para visualizar e executar as análises.

## Autores

Nome dos desenvolvedores do projeto e informações para contato.

Philippe Apolinário    
[@PhilippeApolinario](https://www.linkedin.com/in/philipperapolinario/)

## Histórico de Versões

- **0.1**
  - Primeira versão do projeto.

## Contribuição

**1. Faça um fork do projeto.**
   
**2. Crie uma branch para sua feature:** 
```bash
git checkout -b feature/nova-feature
``` 
**3. Faça commit das suas mudanças:**
```bash
git commit -am 'Adiciona nova feature'
```
**4. Faça push para a branch:** 
```bash
git push origin feature/nova-feature
```
**5. Abra um Pull Request.**

## Licença de Uso

Este projeto está licenciado sob a [Licença MIT](LICENSE.md) - consulte o arquivo LICENSE.md para mais detalhes.

Certifique-se de que suas alterações sigam o estilo e as diretrizes do projeto. Agradecemos pela sua contribuição!
