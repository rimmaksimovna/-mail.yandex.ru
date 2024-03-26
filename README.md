# Анализ почтовых сервсисов iRedMail, Mail server.

### Анализ сервиса iRedMail:
Пакет iRedMail — это полноценный почтовый сервер, работающий на базе postfix, который можно установить и настроить на VDS-сервере. При использовании собственного почтового сервера вы сможете организовать работу с почтой полностью по своему усмотрению, а также не будете сталкиваться с какими-либо ограничениями на количество отправляемых сообщений.
#### 1. Описание сервиса:
   - Назначение: iRedMail - это интегрированное программное обеспечение для построения корпоративной почтовой инфраструктуры с использованием Open Source технологий.
   - Функциональность: Обеспечивает функции электронной почты, включая SMTP, IMAP, веб-интерфейс, администрирование пользователей, защиту от спама и вирусов.
#### 2. Преимущества iRedMail:
   - Бесплатность и открытый исходный код: iRedMail основан на Open Source технологиях, что позволяет использовать его бесплатно и участвовать в его развитии.
   - Простота установки: Удобный механизм установки и настройки, который позволяет быстро развернуть почтовый сервер.
   - Надежность и безопасность: Обеспечивает стабильную работу почтового сервера и механизмы защиты данных.
#### 3. Недостатки iRedMail:
   - Сложность настройки: Для некоторых пользователей настройка iRedMail может показаться сложной из-за отсутствия графического интерфейса.
   - Техническая поддержка: Отсутствие официальной технической поддержки может затруднить решение возникающих проблем.
   - Масштабируемость: Возможны ограничения по масштабированию и расширению функциональности в случае увеличения требований к почтовому серверу.
#### 4. Интеграция с GitHub:
   - Возможности интеграции: Для совместного использования с GitHub iRedMail может использоваться для уведомлений по электронной почте, обмена информацией через защищенные каналы и т. д.
   - Конфиденциальность и безопасность: Использование iRedMail для обмена информацией с GitHub требует обеспечения высокого уровня безопасности и конфиденциальности данных.
#### 5. Перспективы развития iRedMail:
   - Улучшение пользовательского опыта: Развитие пользовательского интерфейса и упрощение настройки для повышения удобства использования.
   - Расширение функциональности: Добавление новых возможностей, расширение поддерживаемых протоколов и интеграций для улучшения работы с другими сервисами.
#### 6. Клиенты и использование:
   - Целевая аудитория: Корпоративные клиенты, администраторы IT-систем, организации, и малый и средний бизнес, ищущие решения построения почтовой инфраструктуры.
   - Использование iRedMail: Может быть использован в различных организациях для создания стабильной и надежной почтовой инфраструктуры.
### Общий вывод:
iRedMail - это мощное и гибкое решение для построения корпоративной почтовой инфраструктуры. Преимущества включают бесплатность, надежность и простоту установки,но следует учесть некоторые недостатки, такие как сложность настройки и ограничения масштабирования. Интеграция с GitHub и другими сервисами может улучшить совместную работу и обмен информацией в организации.




### Анализ сервиса Stalwart Mail Server:
#### 1. Описание сервиса: 
- Stalwart Mail Server – это почтовый сервер, предназначенный для надежной и безопасной почтовой инфраструктуры в организации.
- Разработан на основе JMAP, современного протокола для доступа к электронной почте и другим данным. Stalwart JMAP - это сервер с открытым исходным кодом JSON Meta Application Protocol, разработанный для обеспечения надежности, безопасности и масштабируемости.
- Масштабируется до миллионов пользователей благодаря FoundationDB.
- Безопасный. Написан на Rust.
#### 2. Функциональности:
   - SMTP и POP3/IMAP: Обеспечивает функционал протоколов SMTP для отправки писем и POP3/IMAP для получения писем.
   - Антивирусная защита и фильтрация спама: Встроенные механизмы защиты от вирусов и спам-писем для обеспечения безопасности почтового обмена.
   - Администрирование пользователей и групп: Позволяет администраторам управлять доступом, квотами почтовых ящиков и другими настройками.
#### 3. Преимущества:
   - Высокая безопасность: Stalwart Mail Server обеспечивает высокий уровень защиты данных благодаря встроенным средствам безопасности.
   - Гибкость и настраиваемость: Позволяет адаптировать параметры и функционал под требования конкретной организации.
   - Надежность работы: Обеспечивает стабильную и непрерывную работу почтового сервера.
#### 4. Недостатки:
   - Сложность настройки: Из-за расширенных возможностей может потребоваться определенный уровень компетенций для настройки и обслуживания.
   - Требование к вычислительным ресурсам: Могут потребоваться достаточные вычислительные ресурсы для обеспечения эффективной работы сервера.
#### 5. Интеграция:
   - Взаимодействие с другими сервисами: Возможность интеграции с другими сервисами и приложениями для повышения эффективности работы организации.
   - Совместимость с почтовыми клиентами: Обеспечивает совместимость с широким спектром почтовых клиентов для удобного использования.
#### 6. Перспективы развития:
   - Улучшение интерфейса и удобства использования: Развитие пользовательского интерфейса для повышения удобства работы с почтовым сервером.
   - Добавление новых функциональностей: Постоянное обновление и расширение функций для соответствия современным требованиям.
### Общий вывод:
Stalwart Mail Server является мощным инструментом для организации почтовой инфраструктуры, обладающим высоким уровнем безопасности, гибкостью настроек и надежной работой. Однако для эффективного использования может потребоваться определенный уровень IT-компетенций и ресурсов. При правильной настройке и обслуживании, Stalwart Mail Server способен обеспечить эффективный почтовый обмен в организации.



### Динамика популярности сервисов (синий - iRedMail, красный - Stalwart):
![2024-03-26_13-02-14](https://github.com/rimmaksimovna/-mail.yandex.ru/assets/164010124/8a30df2e-c244-42fe-abdb-98e4f7cc20c5)


###### Таблица 1. Аналитика с Github:
||Watch|Fork|Star|Tags|
|--|--|--|--|--|
|iRedMail|38|199|1.3k|42|
|Stalwart|27|91|2.4k|19|

 По параметру наблюдения не сильно, но лидирует iRedMail, такое количество пользователей отслеживает динамику проекта.
 Примерно в два раза больше пользователей использовали в своих проектах исходную информацию об iRedMail, к Stalwart такой интерес не наблдюается.
 По количеству "подписок" более, чем на одну тысячу пользователей лидирует Stalwart. 

# СОГЛАШЕНИЕ ОБ УРОВНЕ ОБСЛУЖИВАНИЯ (SLA)
## 
##### **Дата публикации: 19 марта 2024 года**
## 
##### Настоящее Соглашение состоит из Общих условий предоставления сервером гарантий Доступности Сервисов и Уровней обслуживания отдельных Сервисов.
##### Соглашение является приложением к Оферте. Во всём остальном, что не предусмотрено Соглашением, Стороны руководствуются условиями Оферты.
##### Термины в Соглашении означают:
1. Сервер - Средство предоставления Ценностей Клиенту, которые обеспечивают достижение им желаемых результатов, без обладания специфическими издержками и рисками, предоставляемый Заказчику в рамках Заказа им услуг. 
2. Заказчик - Предприятие, подразделение предприятия или сотрудник предприятия (по контексту), получающие Услуги от Исполнителя.
3. Исполнитель - Предприятие, подразделение предприятия или сотрудник предприятия (поконтексту), предоставляющие Услуги Заказчику.
4. Пользователь - Сотрудник Клиента, ответственный за эксплуатацию оборудования и ПО, находящегося на обслуживании.
5. Специалист - Сотрудник Исполнителя, уполномоченный на исполнение услуг в рамках настоящего Соглашения.
6. ПО - Программное Обеспечение.
7. Панель управления - программно-аппаратный комплекс Исполнителя, представляющий собой специализированный пользовательский интерфейс для настройки и/или управления Сервером, системой, службой, сервисом и др.
8. Программа - программа для, с помощью которой оказываются отдельные виды Услуг, на условиях соответствующих Приложений.
9. Техническая поддержка - услуга по настройке, обслуживанию (администрированию) Операционной системы, Программ, Программного обеспечения Заказчика и Сервера, предоставленного Исполнителем, за исключением программирования (изменение функционального программного обеспечения), веб-дизайна, отладки пользовательских скриптов.
10. Информационная Система (ИС) - Информационная Система: программно-аппаратный комплекс для создания, хранения, получения, обработки и систематизации информации в рамках определенных задач.
11. Проблема - Корневая причина регулярно повторяющихся или особо критичных Инцидентов, подлежащая устранению максимально эффективным способом.
12. Обращение - Зарегистрированное в системе управления заявками обращение Пользователя, содержащее описание потребности.
13. Заявка - Зарегистрированное и классифицированное Обращение Пользователя, принятое к исполнению.
14. Запрос на изменение - Заявка, исполнение которой требует внесения изменений в текущую конфигурацию инфраструктуры (оборудование, ОС, ПО, права и т.п.).
15. Запрос на обслуживание - Заявка, на выполнение установленных типовых работ, по утвержденным регламентам, не требующих дополнительных согласований.
16. Задача - Составляющий элемент Заявки, формулирующий задание на исполнение типовых работ.
17. Время реакции - Период времени, с момента регистрации Обращения до начала исполнения Заявки.
18. Время решения - Период времени, с момента передачи Заявки на исполнение, до момента закрытия Заявки.
19. Время простоя Сервиса (прерывание Сервиса)- Период времени, с момента возникновения нарушений оговоренных условий эксплуатации Сервиса, до его полного восстановления.
20. Время бесперебойной работы Сервиса - Период времени между прерываниями Сервиса.
21. Мониторинг сервиса - Система постоянного наблюдения за явлениями и процессами, проходящими в Сервисе.
# 
## 1. Уровни обслуживания:

1.1. 99.9% доступности сервиса: гарантия доступности сервиса на уровне не менее чем 99.9% в течение месяца.

1.2. Реакция на Проблемы: Время реакции на Проблему в течение 1 часа с момента обнаружения их.

1.3. Время восстановления: Время простоя сервиса после Проблемы – не более 4 часов.

1.4. Планы регулярного обслуживания: Еженедельное плановое обслуживание согласно расписанию, которое будет опубликовано заранее.

1.5. Служба поддержки: Поставщик предоставляет 24/7 службу поддержки для оперативного реагирования на Обращения и Проблемы пользователей.

1.6. Мониторинг сервиса: постоянный Мониторинг сервиса и инфраструктуры для раннего выявления потенциальных проблем.

1.7. Резервное копирование: Регулярное резервное копирование данных и обеспечение их безопасности.

1.8. Исполнитель вправе запросить учетные данные доступа к Серверу или сайту Заказчика, если для обработки Заявки требуется произвести на них определенные действия. Заказчик обязуется изменить предоставленные учетные данные сразу после обработки Заявки. Исполнитель не несет ответственности за действия, совершенные с использованием учетных данных Заказчика, после обработки Заявки, если Заказчик не изменил данные.
# 
## 2. Обязательства сторон:
2.1 Поставщик обязуется:
  - Обеспечить высокий уровень доступности сервиса.
  - Быстро реагировать на инциденты и восстанавливать работоспособность системы.
  - Предоставлять высококвалифицированную поддержку пользователям.
  - Своевременно информировать пользователей о плановых работах.
2.2 Заказчик обязуется:
  - Извещать о любых проблемах и инцидентах, касающихся работы сервиса.
  - Следовать инструкциям и рекомендациям по использованию сервиса.
  - Соблюдать правила безопасности и конфиденциальности информации.
#
## 3. Порядок и сроки Технической поддержки, показатели уровня доступности Услуг
3.1. Объем работ и срок выполнения Заявки зависит от их типа и выбранного Заказчиком уровня Технической поддержки, которые определяются согласно Таблицам 1-2 Соглашения.
###### Таблица 1.  Типы Заявки:
|Тип Заявка|Описание|
|--|--|
|Инцидент|Заявка на восстановление доступа к Услуге и/или нормального (штатного) функционирования Программ. Примеры: полная недоступность Услуги в связи с неисправностью оборудования, сети, инженерных систем и инфраструктуры Исполнителя, недоступность Программ, сбой в функционировании программного обеспечения, отказ аппаратных средств и др. Обработка инцидентов: 1. В случае появления информации об Инциденте (от Заказчика или от служб мониторинга Исполнителя) последний определяет причину Инцидента и зону ответственности в течение Срока реагирования. 2.Если Инцидент произошел в зоне ответственности Исполнителя, последний самостоятельно ликвидирует его причину.|
|Заявка на обслуживание|1. Перезагрузка Сервера по требованию Заказчика (при невозможности клиента самостоятельного управления сервером через Панель управления); 2. Восстановление Сервера из резервной копии (при невозможности клиента самостоятельного управления сервером через Панель управления); 3. Помощь в изменении опций Тарифа.|
|Заявка на восстановление Сервера|Заявка на восстановление Сервера из резервной копии.|
|Заявка на предоставление информации|Заявка на предоставление технической информации об Услугах, включая отчёты по объёму трафика, журналы доступа, версии ПО и т. д., в зависимости от программ для ЭВМ и наличия технической возможности.|
###### Таблица 2. Максимальные сроки выполнения Заявок для различных уровней Технической поддержки:
|Тип Заявки|Время реагирования, часы|Уровень технической поддержки и Время решения Заявки, часы|Время обслуживания (круглосуточно/рабочие)|
|--|--|--|--|
|Инцидент|1|8|круглосуточно|
|Заявка на обслуживание|2|16|рабочие часы|
|Заявка на предоставление информации|4|24|рабочие часы|
|Заявка на предоставление информации|4|24|рабочие часы|
# 
3.2. Исполнитель осуществляет резервное копирование всех Серверов Заказчика с периодичностью один раз в сутки.

3.3. Восстановление Сервера осуществляет сам Заказчик. Срок восстановления зависит от уровня Технической поддержки.

3.4. Восстановление Сервера Заказчика из резервной копии происходит, после получения Исполнителем соответствующей Заявки от Заказчика.

3.5. Во всех случаях Заказчик обязуется самостоятельно нести ответственность за приобретение лицензий, активацию и иные действия, необходимые для правомерного использования Программного обеспечения Заказчика и Операционной системы. Заказчик признает и соглашается с тем, что Исполнитель не несет ответственность за правомерность использования Заказчиком Программного обеспечения Заказчика и Операционной системы.
# 
## 4. Стоимость Технической поддержки и порядок расчетов.
4.1. Техническая поддержка полностью включена в стоимость услуг и не требует дополнительной оплаты.

4.2. В случае, если Техническая поддержка в отчетном периоде начинается не с первого числа календарного месяца, ее стоимость уменьшается пропорционально количеству дней, оставшихся до конца отчетного периода.

4.3. Порядок расчетов осуществляется в соответствии с договором.
# 
## 5. Процедура изменения SLA:
5.1. Процедура изменения: любые изменения в SLA вносятся по согласованию обеих сторон путем письменного уведомления.

5.2. Вступление в силу изменений: изменения вступают в силу после согласованного срока уведомления.
#
##
# 6. Заключительные положения:
6.1. Это Соглашение об уровне обслуживания является обязательным для всех Пользователей и Поставщиков Сервиса.

6.2. Любые споры, касающиеся нарушения SLA, разрешаются путем переговоров и согласования между сторонами.

6.3. Это Соглашение об уровне обслуживания представляет обязательства Поставщика и Заказчика и обеспечивает прозрачность и ответственность за качество предоставляемого IT-сервиса.
## Реквизиты Исполнителя:
ООО "SLA-SLA"

Юридический и почтовый адрес: г. Москва, Рязанский проспект 99к6

ОГРН 12345678124

ИНН 7777777777

КПП 0987654321

Тел.: 7(902)920-20-19
