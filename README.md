# Отчёт о тестировании функциональность валидации номера банковской карты *Credit Card Number Validator*

## Краткое описание
- Дата начала: 10.01.2020 г. 
- Дата окончания: 10.01.2020 г. 
было проведен *Smoke Test* функционала *Credit Card Number Validator*.

**На тестирование затрачено: 2 час.**

## В результате тестирования выявлены следующие дефекты:

### Ошибки валидации:

- https://github.com/rabmail/JavaDZ1.2/issues/1#issue-782852315
- https://github.com/rabmail/JavaDZ1.2/issues/2#issue-782854130
- https://github.com/rabmail/JavaDZ1.2/issues/3#issue-782855032
- https://github.com/rabmail/JavaDZ1.2/issues/4#issue-782855569

## В качестве тестовых данных использовались данные с сайта "freeformatter.com"

### VISA:
- 4686540469574618
- 4716249686022849
- 4556502606628040
### MasterCard:
- 5379332185734505
- 2221008060842798
- 2720999963492259
### American Express (AMEX):
- 346180939158856
- 344533551130797
- 376333218141449
### Maestro:
- 6759515202534662
- 6763349793915781
- 6304065490768283
### Visa Electron:
- 4913177231821186
- 4508583885296065
- 4844077539220178

## Тестирование производилось в следующем окружении:

### версия и разрядность ОС: 
- Windows 10 PRO, 64, версия 1909
### версия Java:
- openjdk version "11.0.9.1" 2020-11-04
- OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
- OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
### Среда тестирования:
- IntelliJ IDEA Ultimate version 2020.3.1 (build 203.6682.168)