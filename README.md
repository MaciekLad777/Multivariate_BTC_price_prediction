# Multivariate_BTC_price_prediction



**Projekt zawiera proces tworzenia sekwencyjnego modelu przewidującego cenę BTC w stosunku do USD, od pobierania i preprocessowania danych, poprzez ich dalszą analizę oraz uzupełnianie, aż do ostatecznego szkolenia i testowania finalnego modelu.**


# Dane

1.Cena BTC/USD, podstawowe dane

2.Ceny mniej lub bardziej powiązanych z BTC coinów (USD)
	
	-AVAX-Avalanche
	-BCH-Bitcoin Cash
	-BNB-Binance coin
	-Doge
	-ETH-Ethereum
	
3.Sentyment, określający nastawienie kupujących. Czy są skłonni do zakupu czy nie.
	
	https://alternative.me/crypto/api/
	
4.Wiadomości z twittera w temacie BTC

5.BTC w stosunku  do najważniejszych walut światowych
	
	-CAD-Dolar Kanadyjski
	-CNY-Juan Chiński
	-EUR-Euro
	-GBP-Funt Szterling
	-JPY-Jen Japoński

6.Market Volume tzn. wartość transakcji wykonanych za pomocą BTC.

7.Wartość rynków giełdowych
	
	-NYSE
	-NASDAQ
	-LSE


# Notebooks



**CRYPTO_data_preprocessing.ipynb** - 
Pobieranie i wstępna analiza danych, Zmiana kształtu, długości oraz ilości rekordów.


**CRYPTO_model_training.ipynb** - 
Analiza wpływu poszczególnych danych na cenę BTC.
Testowanie modeli z różnymi danymi
Trenowanie finalnego modelu


**CRYPTO_volume_model.ipynb** - 
Uzupełnianie brakujących danych kolumny Market Volume


**CRYPTO_twitter_sentiment.ipynb** - 
Analiza sentymentu w stosunku do BTC na podstawie tweetów (PORZUCONE Z POWODU ZBYT MAŁEJ ILOŚCI DANYCH)
