# btcbruter_script
Инструмент для брутфоорса BTC кошельков

**Системные требования**
- python3
- модули python: bit, requests,ecdsa

**Запуск**
- chmod + x bitforce.py
- ./bitforce.py
Команды для установки зависимостей упущены!!!
Для запуска и корректной установки необходимо склонировать данный реппозиторий и установить все зависимости из подраздела "системные требования".

**Результат работы**
В случаи успеха брутфорса и успеха проверки кошелька, Вы увидите примерную информацию:

```bash
Address: 6485454Ijkkgssdfgsgh78fg7hd8h87dfh78
Private Key: 985eytrtetghotre5yt8545ti9436596jrey5496456345689
Wallet Import Format Private Key: Hj456fghG67GGH67568YYUYII777tuyieru7UTYt
Public Key: 7485JKRFJERTWE43954HRWEQHFFF787878FF8675FTASERER03E923ER2R
Balance: 0.2
```
**И что мне с закрытыми(приватными) ключами делать дальше?**

Смотри сюда.
Закрытый ключ – это хитрая форма криптографии, которая дает пользователю право доступа к его криптовалюте. 
Это буквенно-цифровой пароль/номер, который представляет собой 256-битный набор данных, который генерируеться, когда вы создаете кошелек. 
Это неотъемлемый аспект криптовалюты.
Секретный Ключ нужен для того, чтобы можно было пользоваться своим кошельком на других устройствах. 
Дабы получить доступ к баблу, его нужно импортировать в нужный сервис или нужный кошелек(Trust Wallet. Electrum и т.д).
