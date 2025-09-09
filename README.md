# projeto de consumir api
# 💱 Cotação de Moedas - Streamlit + AwesomeAPI

Este é um aplicativo web simples feito com [Streamlit](https://streamlit.io/) que permite ao usuário consultar a cotação atual de diferentes moedas em tempo real, utilizando a [AwesomeAPI](https://docs.awesomeapi.com.br/api-de-moedas).

## 🚀 Funcionalidades

- Consulta em tempo real de moedas para Real (BRL)
- Moedas disponíveis:
  - Dólar → Real (USD-BRL)
  - Euro → Real (EUR-BRL)
  - Bitcoin → Real (BTC-BRL)
  - Libra → Real (GBP-BRL)
- Exibição de:
  - Alta e baixa do dia
  - Cotação atual de compra e venda
  - Variação do dia

## 🖼️ Interface

A interface é simples e intuitiva, permitindo que o usuário selecione a moeda desejada e clique em "Buscar cotação" para ver as informações.

## 🧰 Tecnologias Utilizadas

- [Python 3.7+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Requests](https://pypi.org/project/requests/)
- [AwesomeAPI - Economia](https://docs.awesomeapi.com.br/api-de-moedas)

## 📦 Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/cotacao-moedas-streamlit.git
cd cotacao-moedas-streamlit
pip install -r requirements.txt
