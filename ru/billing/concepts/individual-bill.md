# Чек об оплате для физических лиц

В соответствии с [ФЗ-54 «О применении контрольно-кассовой техники»](http://base.garant.ru/12130951/) после оплаты ресурсов с помощью банковской карты вы получите чек об оплате по электронной почте.

Чек об оплате — первичный учетный документ, подтверждающий перевод денежных средств с помощью банковской карты.

Мы рекомендуем хранить все чеки — это поможет разобраться, если c каким-либо платежом возникнут проблемы.

## Сумма чека {#bill-amount}

Сумма чека соответствует сумме, списанной с привязанной банковской карты.

Итоговая сумма списания зависит от того, был ли использован [грант](../concepts/bonus-account.md) и пополнялся ли [баланс лицевого счета (ЛС)](../concepts/personal-account.md#balance) в течение расчетного периода.

Сумма списания определяется по формуле:
<br/> ![](../_assets/formula.svg)

  ---  
      
 **[!TAB Пример 1]**
 
<br/>Баланс ЛС на начало расчетного периода — 0 рублей. 
<br/>В течение всего расчетного периода на баланс ЛС поступило 0 рублей.
<br/>Сумма гранта — 1 000 рублей.
<br/>На конец расчетного периода объем потребленных ресурсов составил 5 300 рублей.
<br/>Итоговая сумма: 5 300 - (0 + 0 + 1 000) = 4 300 рублей.
<br/>В начале следующего расчетного периода с привязанной карты будет списано 4 300 рублей. Чек об оплате также будет сформирован на 4 300 рублей.
        
 **[!TAB Пример 2]**
 
<br/>Баланс ЛС на начало расчетного периода — 0 рублей. 
<br/>В течение всего расчетного периода на баланс ЛС поступило 0 рублей.
<br/>Сумма гранта — 1 000 рублей.
<br/>На конец расчетного периода объем потребленных ресурсов составил 800 рублей.
<br/>Размер гранта на конец расчетного периода составляет 200 рублей. Баланс ЛС не изменился.
<br/>В начале следующего расчетного месяца с привязанной банковской карты средства не будут списаны. Чек об оплате не будет сформирован.   
       
  ---     
  
  

## Реквизиты чека {#parameters}

Название | Описание
----- | -----
Наименование получателя | Название организации, получившей платеж.
ИНН | ИНН организации, получившей платеж.
Дата чека | Дата и время закрытия чека.
№ | Уникальный номер чека.
Смена № | Номер смены.
Наим. пр. | Информация об оказанных услугах.
НДС | Налоговая ставка.
Сумма НДС | Сумма оплаченных налогов по всем строчкам чека.
Итого | Сумма в рублях, по которой сформирован чек, с учетом НДС.
Способ оплаты | Вид взаиморасчетов и способ осуществления платежа.
№ ККТ | Регистрационный номер контрольно-кассовой техники.
№ ФН | Номер фискального накопителя.
№ ФД | Номер фискального документа.
ФП | Фискальный признак документа.
Эл. адрес получателя | Адрес электронной почты получателя платежа.
Эл. адрес отправителя | Адрес электронной почты отправителя платежа.
Сайт ФНС | Адрес сайта налоговой службы для проверки фискальных признаков.

