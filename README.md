# Отчет о тестирование " Credit Card Number Validator"

### Было проведенно функциональное тестирование  файла CreditCardNumberValidator
Претестирвоаны номера 11 валидных карт:

 VISA 4916471118814746, MasterCard 5237479602926925, AMEX 377949848526045, Discover 6011677937457819, JCB 3529732644286613, Diners Club - North America 5468051905032352, Diners Club - Carte Blanche 30040607050408, Diners Club - International 36778518573976, Maestro 6761024173470044,Visa Electron 4917121152269823,
 InstaPayment 6389170282623445
 

Дата 28.04.2020 

Время теста 15 мин

## В результате тестирования выявлены следующие дефекты:

[Баг-репорт](https://github.com/PolyakovAlexQA/javaValidator2/issues/1)

## В процессе тестирования использовались следующие артефакты

- Баг репорт в issue

### В качестве тестовых данных использовались данные с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

## Ожидаемый результат:
- При вводе в строку String number = данных AMEX 377949848526045
Result is OK;
- При вводе в строку String number = данных Diners Club Carte Blanche 30040607050408
Result is OK;

- При вводе в строку String number = данных Diners Club - International 36778518573976
Result is OK

## Тестирование проводилось в следующем окружение

- IntelliJ IDEA Community Edition 2019.3.3 x64
- Openjdk version "11.0.7" 2020-04-14
- Windows PRO 64 бит
