## 3.1.28 (2025-08-29)
* https://task.uralsib.ru/browse/UCM-57658
* Убрать снятие баннеров и блок экранов при неуспешной 109

## 3.1.27 (2025-08-25)
* https://task.uralsib.ru/browse/UCM-56503
* AFS для WAIT_DIALER_PERFORM

## 3.1.26 (2025-08-19)
* [UCM-56826](https://task.uralsib.ru/browse/UCM-56826)
* Доработка 104/110. Снятие незакрываемого баннера и блокирующего экрана

## 3.1.25.4 (2025-08-19)
* [UCM-57379](https://task.uralsib.ru/browse/UCM-57379)
* При переходе в XAFS_DECLINED сначала уведомляем пользователя, затем переводим в DECLINED

## 3.1.25.3 (2025-08-19)
* [UCM-57346](https://task.uralsib.ru/browse/UCM-57346)
* Исправлена NPE при форматировании даты при переходе в DECLINED операции внесения наличных по QR в АТМ 

## 3.1.25.2 (2025-08-15)
#### https://task.uralsib.ru/browse/UC-57398
* Для операций 37, 38, 39 добавлен переход CHECK_STATUS -> CRIF_IS_WAIT

## 3.1.25.1 (2025-08-15)
#### https://task.uralsib.ru/browse/UCM-56640
* При создании заявки на кредит или КК добавлен поиск значения в аттрибуте CONSENT_ON_SENDING

## 3.1.25 (2025-08-13)
#### https://task.uralsib.ru/browse/UCM-57127
* Перевод операции 66 в статус OMNI_IS_WAIT

## 3.1.24 (2025-08-13)
* [UCM-57075](https://task.uralsib.ru/browse/UCM-57075)
  * Актуализирован делэй запроса статуса для воркфлоу DOC_FROM_CRIF при статусе APPROVED_MKK

## 3.1.23.9 (2025-08-13)
* [UCM-56751](https://task.uralsib.ru/browse/UCM-56751)
* Изменено тело для пуша в статусе DECLINED для операции внесения наличных по QR в АТМ

## 3.1.23.8 (2025-08-14)
#### https://task.uralsib.ru/browse/UCM-57140
* Доработка отправки номера для иностранных граждан

## 3.1.23.7 (2025-08-13)
#### https://task.uralsib.ru/browse/UCM-37113
* Подготовка к удалению spring-ws-core

## 3.1.23.6 (2025-08-12)
* [UCM-56751](https://task.uralsib.ru/browse/UCM-56751)
* Доработана замена AMOUNT в шаблоне письма, смс, пуша при уведомлениях клиента для операций у которых amount = null

## 3.1.23.5 (2025-08-12)
#### https://task.uralsib.ru/browse/UCM-56742
* Доработан WF CITYPLUS: (дополнены обве верси флоу)
  * Для START, DECLINED, ANALYSIS добавлена работа с начислениями city+

## 3.1.23.4 (2025-08-12)
* [UCM-56672](https://task.uralsib.ru/browse/UCM-56672)
Заменен атрибут 110 и 104 операции дайлера

## 3.1.23.3 (2025-08-11)
* [UCM-56672](https://task.uralsib.ru/browse/UCM-56672)
* Добавлены атрибуты 110 и 104 операции дайлера

## 3.1.23.2 (2025-08-06)
* [UCM-53887](https://task.uralsib.ru/browse/UCM-53887)
* доработки по дайлеру ч5

## 3.1.23.1 (2025-08-06)
* [UCM-53887](https://task.uralsib.ru/browse/UCM-53887)
* доработки по дайлеру ч4

## 3.1.23 (2025-08-11)
* [UCM-55973](https://task.uralsib.ru/browse/UCM-55973)
* Для 66 OPEN_DIGITAL_CREDITCARD введдены статусы PREWAIT_CLIENT_DESICION, WAIT_CLIENT_DESICION

## 3.1.22 (2025-08-05)
* [UCM-55975](https://task.uralsib.ru/browse/UCM-55975)
* Изменение 99_CARD_EVENT

## 3.1.21 (2025-08-05)
#### https://task.uralsib.ru/browse/UCM-55969
* При создании заявки на КК добавлены параметры oid, esiaConnect, bltConsent, bltConsentDate

## 3.1.20.6 (2025-08-07)
* [UCM-56709](https://task.uralsib.ru/browse/UCM-56709)
* Исправлен баг заполнения amount для отказанных операций по внесению наличных в АТМ по QR

## 3.1.20.4 (2025-08-06)
* [UCM-53887](https://task.uralsib.ru/browse/UCM-53887)
* Доработка 104 (CHANGE PHONE). Добавление логики с Дайлером (багфикс)

## 3.1.20.3 (2025-08-06)
* [UCM-56641](https://task.uralsib.ru/browse/UCM-56641)
* доработки по дайлеру ч3

## 3.1.20.3 (2025-08-06)
* [UCM-56641](https://task.uralsib.ru/browse/UCM-56641)
* доработки по дайлеру ч2

## 3.1.20.2 (2025-08-06)
* [UCM-54725](https://task.uralsib.ru/browse/UCM-54725)
* Исправлено тело события для отправки в кафку по операции внесения наличных в АТМ по QR ATM_CASH_IN

## 3.1.20.1 (2025-08-06)
* [UCM-56641](https://task.uralsib.ru/browse/UCM-56641)
* доработки по дайлеру

## 3.1.20 (2025-08-04)
* [UCM-55976](https://task.uralsib.ru/browse/UCM-55976)
* Для internal/cards/credit/order-status сохраняем до аттрибуты приходящие от ОМНИ

## 3.1.19 (2025-08-01)
* [UCM-55974](https://task.uralsib.ru/browse/UCM-55974)
* Полуние и обработка статуса о решении клиента о доходе по заявке КК

## 3.1.18 (2025-08-01)
* [UCM-53887](https://task.uralsib.ru/browse/UCM-53887)
* Доработка 104 (CHANGE PHONE). Добавление логики с Дайлером

## 3.1.17 (2025-07-31)
* [UCM-53816](https://task.uralsib.ru/browse/UCM-53816) 
  * Доработан рест POST /internal/dialer/process-operation приходит JSON строка вместо объекта

## 3.1.16 (2025-07-29)
* [UCM-51650](https://task.uralsib.ru/browse/UCM-51650)
  [semgrep] SSL host verification turned off, Insecure SSL protocol and Insecure Trust Manager

## 3.1.15 (2025-07-30)
* [UCM-53816](https://task.uralsib.ru/browse/UCM-53816)
* Доработка 110. Добавление логики с Дайлером

## 3.1.14 (2025-07-29)
* [UCM-55823](https://task.uralsib.ru/browse/UCM-55823)
* Отправка события в AFS по 110 операции в статусе DECLINED_MISSED_CALL

## 3.1.13 (2025-07-25)
* [UCM-41061](https://task.uralsib.ru/browse/UCM-41061)
* Убрана старая логика обработки C2B операций (c2b_kafka_status_available = false)

## 3.1.12 (2025-07-22)
* [UCM-50775](https://task.uralsib.ru/browse/UCM-50775)
* Рефакторинг Симпл трансфер на паттерн command:
* Добавлены тесты для каждого из статусов
* В коммандах SendRtlDocument, WaitAccountOpening, WaitRtlPerform вынесены методы для лучшей читаемости

## 3.1.11.1 (2025-07-30)
#### https://task.uralsib.ru/browse/UCM-55831
* Обновление коммона
* Поправлены тесты

## 3.1.11 (2025-07-23)
* [UCM-51078](https://task.uralsib.ru/browse/UCM-51078)
* Актуализирован тип дат у DTO (переход с LocalDateTime на OffsetDateTime)

## 3.1.10 (2025-07-22)
#### https://task.uralsib.ru/browse/UCM-56038
* Доработка CLOSING_CARD.WAIT_PERIOD_RTL - проверяем статус у карты, если вышло время ожидания.
#### https://task.uralsib.ru/browse/UCM-54929
* Поправлен OMNI_IS_WAIT для операций 67 типа, для 9ФЗ (режим охлаждения выдачи кредитов) 

## 3.1.9 (2025-07-21)
#### https://task.uralsib.ru/browse/UCM-54928
#### https://task.uralsib.ru/browse/UCM-54929
#### https://task.uralsib.ru/browse/UCM-55133
* Доработка операций 66 и 67 типа, для 9ФЗ (режим охлаждения выдачи кредитов) 

## 3.1.8 (2025-07-18)
#### https://task.uralsib.ru/browse/UCM-47227
* Убрано дублирование ивентов 81 операции

## 3.1.7 (2025-07-13)
#### https://task.uralsib.ru/browse/UCM-53073
* Очереди создаются с типом quorum вместо classic. Реализовано через флаг, для возможного отката на classic

## 3.1.6.2 (2025-07-16)
* [UCM-54788](https://task.uralsib.ru/browse/UCM-54788)
* Реализована обработка WF ATM_CASH_IN
* Добавлены тесты
* Небольшие исправления в WF ATM_CASH_OUT

## 3.1.6.1 (2025-07-15)
* [UCM-53959](https://task.uralsib.ru/browse/UCM-53959)
* Реализована обработка WF ATM_CASH_OUT 
* Добавлены тесты

## 3.1.6 (2025-07-09)
* [UCM-54940](https://task.uralsib.ru/browse/UCM-54940)
* [UCM-54941](https://task.uralsib.ru/browse/UCM-54941)
* [UCM-54948](https://task.uralsib.ru/browse/UCM-54948)
* Добавлен flow CRIF_IS_WAIT для операций 37,38,39 

## 3.1.5 (2025-07-07)
* [UCM-50774](https://task.uralsib.ru/browse/UCM-50774)
* [UCM-50773](https://task.uralsib.ru/browse/UCM-50773)
* Рефакторинг Симпл трансфер на паттерн command:
* Все статусы разнесены по command
* Общие части вынесены в SimpleTransferService
* Приведение кода к сонару

## 3.1.4 (2025-07-07) 
#### https://task.uralsib.ru/browse/UCM-54407
* Ошибка в работе 104 операции. Неправильно передаются данные в CHANGE_PHONE

## 3.1.3 (2025-06-30)
* [UCM-54006](https://task.uralsib.ru/browse/UCM-54006)
  * Исправление отправки документа в ритейл статусе воркфлоу CHECK_CREATE_DNT
  * Добавлены тесты
  
## 3.1.2 (2025-06-27)
* [UCM-50742](https://task.uralsib.ru/browse/UCM-50742)
  * Корректировки в статусах воркфлоу DOC_FROM_CRIF и CRIF для микрокредитов

## 3.1.1 (2025-06-25)
#### https://task.uralsib.ru/browse/UCM-53630
* Удаление статуса OPERATOR_APPROVED_OLD_NUMBER в 104

## 3.1.0(2025-05-23) 
#### https://task.uralsib.ru/browse/UCM-50785
* Подключен history-event-starter

## 3.0.13.1 (2025-06-25)
[UCM-53955](https://task.uralsib.ru/browse/UCM-53955)
* Добавлены заготовки обработчиков для WF ATM_CASH_OUT и ATM_CASH_IN

## 3.0.13 (2025-06-23)
#### https://task.uralsib.ru/browse/UCM-53947
* Реализована поддержка отложенных операций СБП

## 3.0.12 (2025-06-20)
#### https://task.uralsib.ru/browse/UCM-53442
* формирование и отправка событий в AFS для операции изменения номера телефона

## 3.0.11 (2025-06-20)
#### https://task.uralsib.ru/browse/UCM-53600
* формирование и отправка событий в AFS для операции создания ДНТ

## 3.0.10 (2025-06-19)
#### https://task.uralsib.ru/browse/UCM-53104
* Доработка обогащения запроса в OMNI(согласия) на прямую и через kafkagate для анкет на кредиты и КК.
* Требования цб

## 3.0.9 (2025-06-18)
#### https://task.uralsib.ru/browse/UCM-53596
* Добавить новый статус DECLINED_MISSED_CALL для 104 и 110 операции

## 3.0.8 (2025-06-18)
#### https://task.uralsib.ru/browse/UCM-53602
* Доработка sbp c2g

## 3.0.7 (2025-06-11)
#### https://task.uralsib.ru/browse/UCM-52624
* Отправка, в очередь на анализ, операций которые не смогли достучаться до operation.

## 3.0.6 (2025-06-10)
#### https://task.uralsib.ru/browse/UCM-50784
* [TechDebt] Покрытие unit test C2G

## 3.0.5 (2025-06-06)
#### https://task.uralsib.ru/browse/UCM-53034
* [TechDebt] Убрать старый флоу по СБП

## 3.0.4 (2025-05-28)
#### https://task.uralsib.ru/browse/UCM-52574
* Доработать 104 операцию. Добавить новые статусы для создания ДНТ

## 3.0.3 (2025-06-03)
#### https://task.uralsib.ru/browse/UCM-53160
* Оптимизация логики отправки push в WF SBP

## 3.0.2 (2025-05-28)
#### https://task.uralsib.ru/browse/UCM-52626
* Доработка 110 операции

## 3.0.1.2 (2025-05-28)
#### https://task.uralsib.ru/browse/UCM-52225
* откат всех правок CHANGE_PHONE

## 3.0.1.1 (2025-05-20)
#### https://task.uralsib.ru/browse/UCM-52225
* Изменение логики отправки смс при статусе обновления номера телефона CHANGE_PHONE ч.2

## 3.0.1 (2025-05-19)
* [UCM-50989](https://task.uralsib.ru/browse/UCM-50989) keyvalue (неправильное использование)

## 3.0.0.1 (2025-05-20)
#### https://task.uralsib.ru/browse/UCM-52225
* Изменение логики отправки смс при статусе обновления номера телефона CHANGE_PHONE

## 3.0.0 (2025-05-17)
#### https://task.uralsib.ru/browse/UCM-51016
* Переход на opentelemetry вместо brave. Обновлен parent до 2.0.6-SNAPSHOT
* Удален uralsib-jaeger-starter

## 2.4.163 (2025-05-14)
#### https://task.uralsib.ru/browse/UCM-52384
* Доработка workflow 10 операции по передаче параметров в POST /internal/c2g/transfer - перенос обработки атрибута на уровень процессинга

## 2.4.162 (2025-05-13)
#### https://task.uralsib.ru/browse/UCM-52384
* Доработка workflow 10 операции по передаче параметров в POST /internal/c2g/transfer

## 2.4.161.3 (2025-05-13)
#### https://task.uralsib.ru/browse/UCM-51926
* багфикс в CHANGE_PHONE.DECLINED

## 2.4.161.2 (2025-05-13)
#### https://task.uralsib.ru/browse/UCM-51926
* добавил логи в CHANGE_PHONE.DECLINED

## 2.4.161.1 (2025-05-13)
#### https://task.uralsib.ru/browse/UCM-51926
* добавил логи в CHANGE_PHONE.DECLINED

## 2.4.161.1 (2025-05-12)
* [UCM-52159](https://task.uralsib.ru/browse/UCM-52159)
  * Переход на SCK

## 2.4.161 (2025-05-07)
#### https://task.uralsib.ru/browse/UCM-52006
* 80 операция - добавить причину отклонения

## 2.4.160 (2025-05-06)
#### https://task.uralsib.ru/browse/UCM-52005
* Выяснить почему происходит расхолдирование средств и добавить в тест причин отказа

## 2.4.159 (2025-05-05)
#### https://task.uralsib.ru/browse/UCM-52007
* При холдировании средств добавить причину отказа в холдировании

## 2.4.158 (2025-05-05)
#### https://task.uralsib.ru/browse/UCM-51926
* Отправка пуша при статусе обновления номера телефона DECLINED

## 2.4.157.1 (2025-05-06)
* [UCM-52225](https://task.uralsib.ru/browse/UCM-52225)
  * Изменение логики отправки смс при статусе обновления номера телефона CHANGE_PHONE

## 2.4.157 (2025-04-29)
* [UCM-51999](https://task.uralsib.ru/browse/UCM-51999)
  * Добавить атрибут DECLINED_FROM для операций, отклоненных из SBP микросервиса

## 2.4.156 (2025-04-28)
* [UCM-50497](https://task.uralsib.ru/browse/UCM-50497)
  * Добавлен признак one click для заявки на кредитную карту в OMNI

## 2.4.155 (2025-04-28)
[UCM-52048](https://task.uralsib.ru/browse/UCM-52048)
* Фикс сохранения атрибутов для 81 и 102 операций

## 2.4.154.2 (2025-05-21)
[UCM-53185](https://task.uralsib.ru/browse/UCM-53185)
* Хотфикс обработки C2B операций

## 2.4.154.1 (2025-05-19)
[UCM-52945](https://task.uralsib.ru/browse/UCM-52945)
* Хотфикс обработки C2B операций

## 2.4.154 (2025-04-23)
[UCM-44035](https://task.uralsib.ru/browse/UCM-44035)
* Удален фича флаг и логика обработки 'is_allert_neded'

## 2.4.153 (2025-04-14)
[UCM-49511](https://task.uralsib.ru/browse/UCM-49511)
* Выпилить интеграцию финцерт + рефакторинг 8 и 82 операции флоу

## 2.4.152 (2025-04-07)
[UCM-51170](https://task.uralsib.ru/browse/UCM-51170)
* Удалена старая логика отправки документа в Ритейл

## 2.4.151 (2025-04-03)
[UCM-48869](https://task.uralsib.ru/browse/UCM-48869)
* Разработать 72 ENABLE_WEBAUTHN_CONFIRMATION_WEB

## 2.4.150.3 (2025-04-04)
#### https://task.uralsib.ru/browse/UCM-50111
* Фикс флоу 80 и 84 операции

## 2.4.150.2 (2025-04-02)
#### https://task.uralsib.ru/browse/UCM-50381
* Фикс флоу 80 и 84 операции

## 2.4.150.1 (2025-04-01)
#### https://task.uralsib.ru/browse/UCM-50880
* Проверки по отправке пушей "Оплати ЖКХ" и "Оплати мобильную связь" не производятся, если тогл отправки пушей выключен

## 2.4.150 (2025-04-01)
#### https://task.uralsib.ru/browse/UCM-50699
* Изменена логика проверки AFS (xAFS) статуса для 80 и 84 операции 

## 2.4.149 (2025-03-28)
#### https://task.uralsib.ru/browse/UCM-48705
* Добавлена логика отправки пуша "Оплати ЖКХ" для операций СБП (8 тип) при переходе в статус COMPLETED 

## 2.4.148 (2025-03-27)
#### https://task.uralsib.ru/browse/UCM-39077
* В WF104::CHECK_CHANGE_PHONE и WF104::CHANGE_PHONE добавлены условия на CLIENT_ID (+логи)

## 2.4.147 (2025-03-27)
#### https://task.uralsib.ru/browse/UCM-38882
* xAFS. Привязка счета СБП 102. Изменение воркфлоу и создание события в формате history_event

## 2.4.146 (2025-03-26)
#### https://task.uralsib.ru/browse/UCM-39077
* В WF104::CHECK_CHANGE_PHONE и WF104::CHANGE_PHONE добавлены условия на CLIENT_ID (+логи)

## 2.4.145 (2025-03-26)
#### https://task.uralsib.ru/browse/UCM-42768
* Доработка WF 104 по изменению ДНТ

## 2.4.144 (2025-03-27)
#### https://task.uralsib.ru/browse/UCM-50606
* Исправлена отправка писем по операциям (был NPE если нет отчества)

## 2.4.143 (2025-03-21)
#### https://task.uralsib.ru/browse/UCM-39077
* в GET /phone-number/change/available/{phone} добавлен отбор по x-client-id 

## 2.4.142 (2025-03-21)
#### https://task.uralsib.ru/browse/UCM-49881
* В флоу DEPOSIT_OPENING добавлена отправка промокода в Ритейл

## 2.4.141.6 (2025-03-19)
#### https://task.uralsib.ru/browse/UCM-50304
* C2G. фикс старта операции

## 2.4.141.5 (2025-03-18)
#### https://task.uralsib.ru/browse/UCM-50196
* C2G. фикс старта операции

## 2.4.141.4 (2025-03-17)
#### https://task.uralsib.ru/browse/UCM-50118
* C2G. фикс старта операции

## 2.4.141.3 (2025-03-13)
#### https://task.uralsib.ru/browse/UCM-49847
* C2G. фикс старта операции

## 2.4.141.2 (2025-03-13)
#### https://task.uralsib.ru/browse/UCM-49884
* SBP.COMPLETED:
  * Исправлен тип даты отправляемого сообщения в очередь (PayMobileConnectionCommunicationData)

## 2.4.141.1 (2025-03-12)
#### https://task.uralsib.ru/browse/UCM-49873
* C2G. Бэк отправляет в вебсокет статус PROCESSING не дожидаясь ответа из кафки

## 2.4.141 (2025-03-12)
#### https://task.uralsib.ru/browse/UCM-49855
* Фикс заполнения атрибута sndAccountNumber для C2G_SBP

## 2.4.140 (2025-03-12)
#### https://task.uralsib.ru/browse/UCM-49696
* Доработан WF C2G_SBP.START

## 2.4.139 (2025-03-11)
#### https://task.uralsib.ru/browse/UCM-49606
* Доработка парсинга парметра PAYMENT_TERM

## 2.4.138 (2025-03-10)
#### https://task.uralsib.ru/browse/UCM-49558
* Доработан WF C2G_SBP.START

## 2.4.137 (2025-03-07)
#### https://task.uralsib.ru/browse/UCM-48640
* Доработан WF SBP.COMPLETED:
  * Исправлена текстовка лога

## 2.4.136 (2025-03-07)
#### https://task.uralsib.ru/browse/UCM-48640
* Доработан WF SBP.COMPLETED:
  * Расширено логирование для отправки пуша

## 2.4.135 (2025-03-05)
[UCM-41086](https://task.uralsib.ru/browse/UCM-41086)
* Добавлена логика отправки документа по 4 типу операции в формате XML

## 2.4.134 (2025-03-05)
#### https://task.uralsib.ru/browse/UCM-49326
* Добавить новый параметр КПП (SndActualPayerOrgRegCode) в платеж C2G
  
## 2.4.133 (2025-03-05)
#### https://task.uralsib.ru/browse/UCM-48640
* Доработан WF SBP.COMPLETED:
  * Добавлена отправка сообщения в очередь которую читает trigger-communication

## 2.4.132.4 (2025-02-21)
[UCM-48299](https://task.uralsib.ru/browse/UCM-48299)
* C2G. C2G. Абракадабра в логах метода POST notification-transport/internal/notification-push

## 2.4.132.3 (2025-02-20)
[UCM-48362](https://task.uralsib.ru/browse/UCM-48362)
* C2G. Исправила логирование во флоу

## 2.4.132.2 (2025-02-18)
[UCM-48518](https://task.uralsib.ru/browse/UCM-48518)
* Для операций 88 и 89 пин для установки в Ритейл передается в поле PinSerialize

## 2.4.132.1 (2025-02-17)
[UCM-48730](https://task.uralsib.ru/browse/UCM-48730
* В WF10::Completed исправлено заполнение параметров вызова mvs/internal/charges/deletion 

## 2.4.132 (2025-02-18)
[UCM-48362](https://task.uralsib.ru/browse/UCM-48362)
* C2G. Доработка флоу 10 операции

## 2.4.131 (2025-02-03)
[UCM-48374](https://task.uralsib.ru/browse/UCM-48374)
* В WF10::Completed добавлен вызов PATCH mvs/internal/charges/deletion

## 2.4.130 (2025-02-03)
[UCM-48117](https://task.uralsib.ru/browse/UCM-48117)
*  Убрана настройка таймаута Feign из кода приложения

## 2.4.129 (2025-02-03)
[UCM-47981](https://task.uralsib.ru/browse/UCM-47981)
*  UCM-47981 В WF 10 ОП добавлена передача атрибутов для XAFS

## 2.4.128 (2025-02-03)
[UCM-47981](https://task.uralsib.ru/browse/UCM-47981)
* В WF 84 убрана передача параметра devicePrint в omnigate

## 2.4.127.15 (2025-02-05)
* [UCM-48284](https://task.uralsib.ru/browse/UCM-48284)
  * Функционал, связанный с периодом охлаждения по закрытию карту закрыт флагом 

## 2.4.127.14 (2025-02-03)
[UCM-48222](https://task.uralsib.ru/browse/UCM-48222)
* C2G. в 10 ОП если если statusNspk=CONFIRMED то не происходит перехода операции в статус COMPLETED

## 2.4.127.13 (2025-02-03)
[UCM-48199](https://task.uralsib.ru/browse/UCM-48199)
* C2G. Изменить тип ID тарифа с integer на Long

## 2.4.127.12 (2025-01-31)
[UCM-47273](https://task.uralsib.ru/browse/UCM-47273)
* C2G. Разработка WF операции - ошибка в названии атрибута

## 2.4.127.11 (2025-01-31)
* [UCM-48033](https://task.uralsib.ru/browse/UCM-48033)
  * Исправлено определение времени ожидания статуса от ритейла по закрытию карты

## 2.4.127.10 (2025-01-31)
* [UCM-48033](https://task.uralsib.ru/browse/UCM-48033)
  * Исправлено условие перевода операции на закрытие карты в COMPLETED

## 2.4.127.9 (2025-01-31) 
* [UCM-48033](https://task.uralsib.ru/browse/UCM-48033)
  * Удален неиспользуемый статус воркфлоу закрытия карты REPEAT_WAIT_RTL
  * Реализован статус воркфлоу WAIT_PERIOD_RTL - ожидание статуса заявки на закрытие карты от Retail в тибко

## 2.4.127.8 (2025-01-31)
[UCM-47273](https://task.uralsib.ru/browse/UCM-47273)
* C2G. Разработка WF операции

## 2.4.127.7 (2025-01-30)
[UCM-47273](https://task.uralsib.ru/browse/UCM-47273)
* C2G. Разработка WF операции

## 2.4.127.6 (2025-01-30)
[UCM-47273](https://task.uralsib.ru/browse/UCM-47273)
* C2G. Разработка WF операции

## 2.4.127.5 (2025-01-30)
[UCM-44456](https://task.uralsib.ru/browse/UCM-44456)
* Доработан RetailClient, добавлен заголовок "Content-Type: application/json; charset=utf-8":
  * POST /internal/send-document
  * POST /internal/v2/send-document
  
## 2.4.127.4 (2025-01-30)
[UCM-47273](https://task.uralsib.ru/browse/UCM-47273)
* C2G. Разработка WF операции

## 2.4.127.3 (2025-01-29)
[UCM-47931](https://task.uralsib.ru/browse/UCM-47931)
* Фикс заполнения атрибутов для C2B
  
## 2.4.127.2 (2025-01-29)
* https://task.uralsib.ru/browse/UCM-47939
  * WF CITYPLUS.CHECK_CHANNEL:
    * Исправлена ошибка, которая приводила к двойной проверке и переходу в статусы
  
## 2.4.127.1 (2025-01-28)
* https://task.uralsib.ru/browse/UCM-41086
  * Доработка WF SBP. Добавление логики отправки документа в Ритейл в формате xml

## 2.4.127 (2025-01-27)
* https://task.uralsib.ru/browse/UCM-47595
  * Доработка WF CARD_SERVICES_LINKER. Для MY_INSURANCE (27 тип операции) сохраняется параметр MY_INSURANCE_DATE в CARD_DATA (мс products).

## 2.4.126.1 (2025-01-27)
* [UCM-47295](https://task.uralsib.ru/browse/UCM-47295)
  * Добавлена транзакционная обертка для удаления попытки из БД (без транзакции не работает)

## 2.4.126 (2025-01-27)
[UCM-47728](https://task.uralsib.ru/browse/UCM-47728)
* Добавлен временный фикс полей при создании операций C2B

## 2.4.125 (2025-01-24)
* [UCM-47295](https://task.uralsib.ru/browse/UCM-47295)
  * Реализован метод обработки статуса заявки на закрытие карты из Tibco
  * Реализован ручной сброс для счётчика попыток запросов статуса у IBSO Retail и продолжение ожидания по операции закрытия карты

## 2.4.124 (2025-01-24)
[UCM-47640](https://task.uralsib.ru/browse/UCM-47640)
* Доработан WF CITYPLUS.CHECK_CHANNEL:
  * изменена проверка по источнику оплаты

## 2.4.123 (2025-01-23)
[UCM-47314](https://task.uralsib.ru/browse/UCM-47314)
* Подправлен вызов DELETE запроса "/internal/card/service-options/{cardId}"

## 2.4.122 (2025-01-20)
[UCM-47186](https://task.uralsib.ru/browse/UCM-47186)
* убрать UPDATE риск-индикаторов в черновиках операций

## 2.4.121 (2025-01-16)
[UCM-47314](https://task.uralsib.ru/browse/UCM-47314)
* Доработан WF CARD_SERVICES_LINKER. В новой ветке функционала добавлена логика очистки кэша, т.к. планируется отправлять отклики из Ритейла в ДБО в случае если операция совершена вне ДБО

## 2.4.120 (2025-01-15)
* [UCM-47481](https://task.uralsib.ru/browse/UCM-47481)
  * Исправление ивентов логирования случаев ошибок при отправке заявок на кредит и кредитную карту в КРИФ

## 2.4.119 (2025-01-13)
[UCM-47314](https://task.uralsib.ru/browse/UCM-47314)
* Доработан WF CARD_SERVICES_LINKER. Добавлен флаг отключения выполнения метода updateCardServiceOptionsInfo

## 2.4.118.4 (2025-01-10)
[UCM-47354](https://task.uralsib.ru/browse/UCM-47354)
* Исправление метода получения статуса c2b операций из омни

## 2.4.118.3 (2025-01-09)
[UCM-47041](https://task.uralsib.ru/browse/UCM-47041)
* Исключено заполнение deeplink в пуше при изменении лимитного плана

## 2.4.118.2 (2024-12-25)
[UCM-45526](https://task.uralsib.ru/browse/UCM-45526)
* Удален конфиг sber_hold_enable, т.к. не используется

## 2.4.118.1 (2024-12-24)
[UCM-47010](https://task.uralsib.ru/browse/UCM-47010)
* Добавление всех типов операций WF DEPOSIT_CLOSING для работы с XAFS

## 2.4.118 (2024-12-23)
[UCM-35918](https://task.uralsib.ru/browse/UCM-35918)
* Добавление в WF CARD_ISSUE логики для работы с XAFS

## 2.4.117 (2024-12-19)
[UCM-45678](https://task.uralsib.ru/browse/UCM-45678)
* Изменены имена дополнительных атрибутов Ситиплюс операций для отправки в AFS
* Скорректированы условия заполнения атрибутов для отправки в AFS
* Скорректированы и добавлены тесты
* Добавлено доп логирование при отправке операций в AFS

## 2.4.116 (2024-12-19)
[UCM-46957](https://task.uralsib.ru/browse/UCM-46957)
* исправить ошибку в json

## 2.4.115 (2024-12-16)
[UCM-45847](https://task.uralsib.ru/browse/UCM-45847)
* Переходить в статус XAFS, XAFS_WAIT_STATUS могут только операции с operationTypeId =2,3,4,5

## 2.4.114 (2024-12-09)
[UCM-46459](https://task.uralsib.ru/browse/UCM-46459)
* Временно убрал заполнение DeviceFingerprint

## 2.4.113 (2024-12-06)
[UCM-46401](https://task.uralsib.ru/browse/UCM-46401)
* Вернул заполнение DeviceFingerprint

## 2.4.112.18 (2024-12-19)
* [UCM-46885](https://task.uralsib.ru/browse/UCM-46885)
  * Исправление работы ожидания xafs резолюции, для случая, когда дернули XAFS_WAIT_STATUS вручную - теперь продолжаем ждать, а не переходим к следующему статусу

## 2.4.112.17 (2024-12-10)
[UCM-46613](https://task.uralsib.ru/browse/UCM-46613)
* Не передается Наименование подписки при создании

## 2.4.112.16 (2024-12-10)
[UCM-46540](https://task.uralsib.ru/browse/UCM-46540)
* добавить неразрывные пробелы в 81 операцию

## 2.4.112.15 (2024-12-05)
[UCM-46401](https://task.uralsib.ru/browse/UCM-46401)
* Временно убрал заполнение DeviceFingerprint
  
## 2.4.112.14 (2024-12-05)
[UCM-46221](https://task.uralsib.ru/browse/UCM-46221)
* Сохранение атрибутов для xAFS

## 2.4.112.13 (2024-12-05)
* [UCM-46380](https://task.uralsib.ru/browse/UCM-46380)
  * CITYPLUS.CHECK_CHANNEL:
    * Условие isCredit теперь рассчитывается правильно
  
## 2.4.112.12 (2024-12-05)
* [UCM-35126](https://task.uralsib.ru/browse/UCM-35126)
  * Создавать синхронное событие для перевода me2me СБП 81 - изменила локаль на 11
  
## 2.4.112.11 (2024-12-05)
* [UCM-46262](https://task.uralsib.ru/browse/UCM-46262)
  * Исправление для удаления маркерного атрибута ожидания перед выгрузкой документов на кредит

## 2.4.112.10 (2024-12-05)
* [UCM-35126](https://task.uralsib.ru/browse/UCM-35126)
  * Создавать синхронное событие для перевода me2me СБП 81 - скедулер в статусе requestMoney

## 2.4.112.9 (2024-12-04)
* [UCM-35126](https://task.uralsib.ru/browse/UCM-35126)
  * Создавать синхронное событие для перевода me2me СБП 81 - логирование

## 2.4.112.8 (2024-12-04)
* [UCM-46262](https://task.uralsib.ru/browse/UCM-46262)
  * Исправление для удаления маркерного атрибута ожидания перед выгрузкой документов на кредит 
  
## 2.4.112.7 (2024-12-04)
* [UCM-35126](https://task.uralsib.ru/browse/UCM-35126)
  * Создавать синхронное событие для перевода me2me СБП 81 - запись атрибута при отклонении операции

## 2.4.112.6 (2024-12-04)
* [UCM-46262](https://task.uralsib.ru/browse/UCM-46262)
  * Для получения документов на кредит явно разделены способы ожидания для follow up, изменения параметров и первоначального запроса документов

## 2.4.112.5 (2024-12-04)
[UCM-46221](https://task.uralsib.ru/browse/UCM-46221)
* Сохранение атрибутов для xAFS

## 2.4.112.4 (2024-12-03)
* [UCM-35126](https://task.uralsib.ru/browse/UCM-35126)
  * Создавать синхронное событие для перевода me2me СБП 81

## 2.4.112.3 (2024-12-03)
* [UCM-46262](https://task.uralsib.ru/browse/UCM-46262)
  * Для получения документов на кредит по измененным параметрам добавлено ожидание перед загрузкой 

## 2.4.112.2 (2024-12-02)
[UCM-35919](https://task.uralsib.ru/browse/UCM-35919)
* Для WF CARD_ISSUE_DIGITAL и добавлена логика для работы с XAFS

## 2.4.112.1 (2024-12-02)
[UCM-34518](https://task.uralsib.ru/browse/UCM-34518)
* Для WF OPENING_DEBIT_CARD_DELIVERY и добавлена логика для работы с XAFS

## 2.4.112 (2024-11-26)
* [UCM-43156](https://task.uralsib.ru/browse/UCM-43156)
* WF CITYPLUS.CHECK_CHANNEL:
  * Полностью изменена логика шага

## 2.4.111 (2024-11-22)
* [UCM-45736](https://task.uralsib.ru/browse/UCM-45736
* В запросы тибко добавить данные из профиля

## 2.4.110 (2024-11-18)
* [UCM-34530](https://task.uralsib.ru/browse/UCM-34530)
  * Добавлена обработка события ошибки при получении списка документов на кредит
* [UCM-45501](https://task.uralsib.ru/browse/UCM-45501)
  * Исправление логирования события ошибке при отправке таймаута подписания в криф для 38 операции

## 2.4.109.9 (2024-11-25)
* [UCM-45521](https://task.uralsib.ru/browse/UCM-45521)
* Исправлено формирование history event`a для операции cityplus

## 2.4.109.8 (2024-11-22)
* [UCM-45894](https://task.uralsib.ru/browse/UCM-45894
* При расхолдировании атрибуту IS_AMOUNT_HOLD присваивать N

## 2.4.109.7 (2024-11-20)
* [UCM-45746](https://task.uralsib.ru/browse/UCM-45746
* Исправить что Операция 8 не движется по статусам

## 2.4.109.6 (2024-11-18)
* [UCM-45306](https://task.uralsib.ru/browse/UCM-45306
* Исправлен code для события при обработки статуса XAFS на OPERATION_PROCESSING$SYSTEM$XAFS_EVENT для WF Ситиплюс
 
## 2.4.109.5 (2024-11-15)
* [UCM-45614](https://task.uralsib.ru/browse/UCM-45614
* Добавлено заполнение "aggregatorName" при отправке запроса в  POST retailgate/internal/hold-amount/city и /internal/unhold-amount-city

## 2.4.109.4 (2024-11-14)
* [UCM-45521](https://task.uralsib.ru/browse/UCM-45521)
* Исправлено формирование history event`a для операции cityplus  
* Исправлено формирование history event`a для операции сбп  

## 2.4.109.3 (2024-11-13)
* [UCM-45434](https://task.uralsib.ru/browse/UCM-45434)
  * Добавлен перевод кредитных операций в статус DECLINED_BY_BANK_SYSTEM после наступление таймаута подписания документов 

## 2.4.109.2 (2024-11-13)
* [UCM-44837](https://task.uralsib.ru/browse/UCM-44837)
  * В события из тибко протащить данные из профиля

## 2.4.109.1 (2024-11-11)
* [UCM-45405](https://task.uralsib.ru/browse/UCM-45405)
  * При изменении параметров переводим операцию в статус получения документов после подписания

## 2.4.109 (2024-11-11)
* https://task.uralsib.ru/browse/UCM-45387
* Сохраняем параметры карты на 10 минут в keyvalue, чтобы фронт мог сделать запрос, если через веб-сокет сообщение не дошло. 

## 2.4.108 (2024-11-09)
[UCM-43836](https://task.uralsib.ru/browse/UCM-43836)
* Изменен WF сити+ операций в части холдирования средств по шлюзу Тинькофф
* В документ отправки в ритейл добавлен атрибут toTinkoff

## 2.4.107 (2024-11-06)
[UCM-44606](https://task.uralsib.ru/browse/UCM-44606)
[UCM-44564](https://task.uralsib.ru/browse/UCM-44564)
* WF CITYPLUS. COMPLETED:
  * Добавлена отправка сообщения в очередь которую читает trigger-communication

## 2.4.106 (2024-11-06)
[UCM-44537](https://task.uralsib.ru/browse/UCM-44537)
* Исправление сбп процессинга статуса Refused от Тибко

## 2.4.105 (2024-11-06)
[UCM-40986](https://task.uralsib.ru/browse/UCM-40986)
* рефакторинг сбп процессинг на патерн команда - устранила замечания

## 2.4.104 (2024-10-29)
[UCM-40986](https://task.uralsib.ru/browse/UCM-40986)
* рефакторинг сбп процессинг на патерн команда - шаблон, без тестов

## 2.4.103 (2024-10-30)
[UCM-41004](https://task.uralsib.ru/browse/UCM-41004)
* Заменен code для события при обработки статуса XAFS с OPERATION$SYSTEM$OPERATION.CHANGE_STATUS на OPERATION_PROCESSING$SYSTEM$XAFS_EVENT

## 2.4.102 (2024-10-22)
[UCM-41086](https://task.uralsib.ru/browse/UCM-41086)
* Отправка документа в Ритейл в формате XML

## 2.4.101 (2024-10-22)
[UCM-43515](https://task.uralsib.ru/browse/UCM-43515)
* Корректировка обработки статуса WAIT_RTL_PERFORM операции 109 Обновления паспортных данных

## 2.4.100 (2024-10-21)
[UCM-44480](https://task.uralsib.ru/browse/UCM-44480)
* Отправка пуша при статусе обновления паспортных данных COMPLETED

## 2.4.99.7 (2024-10-31)
[UCM-45007](https://task.uralsib.ru/browse/UCM-45007)
* Исправлена проблема в WF SIMPLE_TRANSFER:
  * Обработка afsVerificationTimeExpired и afsQueueTimeExpired не могла быть корректно исполнена из-за того, что сравнивался ENUM и STRING

## 2.4.99.6 (2024-10-22)
[UCM-41224](https://task.uralsib.ru/browse/UCM-41224)
* Фикс обработки статуса AFS в новом флоу cityplus

## 2.4.99.5 (2024-10-22)
[UCM-35129](https://task.uralsib.ru/browse/UCM-35129)
* XAFS. Доработка воркфлоу CHANGE_PHONE (добавил заполение operation в AfsContent)

# 2.4.99.4 (2024-10-22)
## 2.4.99.3 (2024-10-23)
* https://task.uralsib.ru/browse/UCM-44623
* Смена имени параметра deliveryWay на deliveryMethod, т.к. омни не смотрит на deliveryWay.

## 2.4.99.2 (2024-10-22)
[UCM-35129](https://task.uralsib.ru/browse/UCM-35129)
* XAFS. Доработка воркфлоу CHANGE_PHONE (багфикс перехода START->CHECK_POSTPONE)

## 2.4.99.1 (2024-10-22)
[UCM-35129](https://task.uralsib.ru/browse/UCM-35129)
* XAFS. Доработка воркфлоу CHANGE_PHONE (багфикс перехода START->XAFS)

## 2.4.99 (2024-10-18)
* [UCM-43950](https://task.uralsib.ru/browse/UCM-43950)
  * Если атрибут SIGN_TYPE не указан (для обратной совместимости) считаем что тип подписания Signed
  * Для оповещения КРИФа о подписании документов на кредит используем данные о подписании с фронта (атрибут SIGN_TYPE)

## 2.4.98 (2024-10-12)
[UCM-35129](https://task.uralsib.ru/browse/UCM-35129)
* XAFS. Доработка воркфлоу CHANGE_PHONE

## 2.4.97 (2024-10-17)
[UCM-42288](https://task.uralsib.ru/browse/UCM-42288)
* Изменения в WF 2 и 50 типа операции, добавление нового статуса и уведомления
* Рефакторинг: метод для отправки уведомлений в статусе AFS_DECLINED вынесен на уровень ProcessorService

## 2.4.96 (2024-10-11)
* [UCM-43946](https://task.uralsib.ru/browse/UCM-43946)
  * Удаление атрибутов документов по кредиту происходит всегда при переходе в статус DOWNLOAD_DOCS, т.к. затем могут прийти новые документы после изменения параметров кредита

## 2.4.95.2 (2024-10-16)
* [UCM-42976](https://task.uralsib.ru/browse/UCM-42976)
  * Исправление для атрибута обязательности подписания документа на КН если КРИФ его не присылает 

## 2.4.95.1 (2024-10-08)
[UCM-44072](https://task.uralsib.ru/browse/UCM-44072)
* WF CITYPLUS. XAFS_WAIT_STATUS:
  * При проверке статуса ревью теперь осуществляется переход в CHECK_CHANNEL

## 2.4.95 (2024-10-01)
[UCM-41567](https://task.uralsib.ru/browse/UCM-41567)
* Доработка флоу операций c2b 

## 2.4.94 (2024-09-26)
[UCM-42206](https://task.uralsib.ru/browse/UCM-42206)
* Доработка флоу операций 8, 11, 82 типов
* Доработка нотификации клиента при подтверждении/отклонении операции оператором

## 2.4.93 (2024-09-25)
[UCM-43416](https://task.uralsib.ru/browse/UCM-42955)
* Отправка пуша при статусе обновления паспортных данных DECLINED

## 2.4.92 (2024-09-25)
[UCM-34519](https://task.uralsib.ru/browse/UCM-34519)
* Для операции 32 (закрытие депозита) добавлена логика для работы с XAFS + небольшой рефакторинг замечаний Сонара

## 2.4.91 (2024-09-25)
[UCM-41224](https://task.uralsib.ru/browse/UCM-41224)
* Флоу операции ситиплюс переведен на паттерн команда

## 2.4.90 (2024-09-24)
[UCM-43416](https://task.uralsib.ru/browse/UCM-43416)
* Изменен источник данных SignatureHash при отправке документа в Ритейл для операций открытия счета/депозита

## 2.4.89 (2024-09-23)
* [UCM-43417](https://task.uralsib.ru/browse/UCM-43417)
* Добавлена логика отправки параметра PROMO при формировании документа в Ритейл операции с типом 31

## 2.4.88 (2024-09-23)
* [UCM-42976](https://task.uralsib.ru/browse/UCM-42976)
  * Реализовано сохранение флага необходимости подписания из криф по документам на кредит

## 2.4.87 (2024-09-18)
[UCM-42630](https://task.uralsib.ru/browse/UCM-42630)
* записывать информацию об отклонении оп 8,11,81,82 в атрибуты - поправила из-за комона 

## 2.4.86 (2024-09-17)
[UCM-41086](https://task.uralsib.ru/browse/UCM-41086)
* Отправка документа операций с типами 11, 32, 31 в Ритейл в формате XML

## 2.4.85 (2024-09-13)
[UCM-42630](https://task.uralsib.ru/browse/UCM-42630)
* записывать информацию об отклонении оп 8,11,81,82 в атрибуты

## 2.4.84 (2024-09-13)
[UCM-42064](https://task.uralsib.ru/browse/UCM-42064)
* Добавлена обработка повторного отказа по операциям СБП

## 2.4.83 (2024-09-13)
#### https://task.uralsib.ru/browse/UCM-38327
* Переход на opentelemetry вместо brave. Обновлен parent до 2.0.6-SNAPSHOT
* Удален uralsib-jaeger-starter
* ОТКАТ изменений т.к. имеются проблемы

## 2.4.82 (2024-09-11)
[UCM-42985](https://task.uralsib.ru/browse/42985)
* Фикс добавлена обработка недостающего статуса

## 2.4.81.4 (2024-09-11)
[UCM-43069](https://task.uralsib.ru/browse/43069)
* Добавлен потерянный return в методе findCardDetail

## 2.4.81.3 (2024-09-11)
[UCM-41086](https://task.uralsib.ru/browse/41086)
* Отправка документа операций с типом 1, 2, 3, 7 в Ритейл в формате XML

## 2.4.81.2 (2024-09-11)
[UCM-43002](https://task.uralsib.ru/browse/43002)
* Фикс сокрытия баннера

## 2.4.81.1 (2024-09-10)
[UCM-35095](https://task.uralsib.ru/browse/UCM-35095)
* Изменена логика метода logAfs для операций CityPlus

## 2.4.81 (2024-09-06)
[UCM-42269](https://task.uralsib.ru/browse/UCM-42269)
* Доработана логика отправки XAFS для операций CityPlus

## 2.4.80 (2024-09-04)
[UCM-42585](https://task.uralsib.ru/browse/UCM-42585)
* Доработано снятие баннера в разных статусах 109 операции

## 2.4.79 (2024-09-04)
[UCM-42461](https://task.uralsib.ru/browse/UCM-42461)
* Изменение телефона СБП в ДБО. Новая 111 операция

## 2.4.78 (2024-08-30)
[UCM-42204](https://task.uralsib.ru/browse/UCM-42204)
* Переименовать Константы в воркфлоу

## 2.4.77 (2024-09-03)
[UCM-41525](https://task.uralsib.ru/browse/UCM-41525)
* При отправке кредитных заявок в ОМНИ добавлена логика формирования данных с учетом нового атрибута PAYER_IPADDRESS

## 2.4.76.4 (2024-09-04)
[UCM-42862](https://task.uralsib.ru/browse/UCM-42862)
* Исправлена отправка флага oneClick в ОМНИ для заявки на КК

## 2.4.76.3 (2024-08-28)
[UCM-42486](https://task.uralsib.ru/browse/UCM-42486)
* Исправлен код события для логирования взаимодействий с xAFS

## 2.4.76.2 (2024-08-23)
[UCM-42269](https://task.uralsib.ru/browse/UCM-42269)
* WF CITYPLUS проверка XAFS:
  * Формируется кастомное событие на основе базового (OPERATION_PROCESSING$OPERATION$CITY_PLUS_SYSTEM)
* ProductsService:
  * Убраны неиспользуемые функции:
    * saveStatusToCardData
    * createProductDataId
    * convertToBaseDataList
    
## 2.4.76.1 (2024-08-21)
[UCM-41009](https://task.uralsib.ru/browse/UCM-41009)
* Выход из скачивания документов при повторной отправке параметров из криф

## 2.4.76 (2024-08-16)
* [UCM-41645](https://task.uralsib.ru/browse/UCM-41645)
  * Исправлено значение канала отправки отклика в ЕБПП на DBO, если пришел канал WEB
* [UCM-41524](https://task.uralsib.ru/browse/UCM-41524)
  * Убран устаревший фича-флаг, переключающий режим работы с параметрами кредита
  * Для кредитных операций добавлен воркфлоу статус SEND_SIGNING_RESULT для отправки результата подписания документов в КРИФ

## 2.4.75 (2024-08-16)
https://task.uralsib.ru/browse/UCM-42055
* Доработка статуса WAIT_RETAIL_FOR_COMPLETED - для 22 типа проверяем что id уралсиб бонуса появился у клиента.

## 2.4.74 (2024-08-15)
[UCM-34526](https://task.uralsib.ru/browse/UCM-34526)
* При обработке статуса CHECK_POSTPONE переходим в статус XAFS если включен фичатогл xafs_workflow_simple_transfer
* В SIMPLE_TRANSFER добавлены новые статусы XAFS, XAFS_WAIT_STATUS
* Рефакторинг. Вынос метода createEventToAnalyze на уровень antifraud сервиса. Небольшие правки замечаний по сонару

## 2.4.73 (2024-08-15)
[UCM-41009](https://task.uralsib.ru/browse/UCM-41009)
* Исправление ожидания перед выполнением команд
* Удален неиспользуемый атрибут и соответствующие javadocs

## 2.4.72 (2024-08-14)
[UCM-41009](https://task.uralsib.ru/browse/UCM-41009)
* Для воркфлоу CRIF и DOC_FROM_CRIF реализована работа с follow up (улучшение условий по кредиту)
* Вынесен сервис ожидания перед выполнением команд ExecutionWaitingService
* Вынесен сервис по работе с кредитными документами CreditDocumentsService (используется для общего функционала выгрузки документов)

## 2.4.71 (2024-08-13)
[UCM-40857](https://task.uralsib.ru/browse/UCM-40857)
* Добавление логики передачи SignatureHash в Ритейл при открытии вклада или счета

## 2.4.70 (2024-08-12)
[UCM-37665](https://task.uralsib.ru/browse/UCM-37665)
* Удален устаревший и удаленный метод из микросервиса operation

## 2.4.69 (2024-08-12)
[UCM-40486](https://task.uralsib.ru/browse/UCM-40486)
* Добавлена логика отправки параметра ProductCode в kafka на основании атрибута IR_DELIVERY_CODE

## 2.4.68 (2024-08-01)
[UCM-41664](https://task.uralsib.ru/browse/UCM-41664)
* Отправка RTM/History event для 81 операции

## 2.4.67.5 (2024-08-02)
[UCM-41779](https://task.uralsib.ru/browse/UCM-41779)
* Исправлено сохранение атрибута BUSINESS_VALUE для 11 типа операции

## 2.4.67.4 (2024-08-01)
[UCM-41726](https://task.uralsib.ru/browse/UCM-41726)
* Исправлена ошибка NullPointerException по 11 типу операции

## 2.4.67.3 (2024-07-31)
[UCM-41674](https://task.uralsib.ru/browse/UCM-41674)
* Для доп. номера телефона смотрим новый атрибут при отправке заявки на КК в ОМНИ

## 2.4.67.2 (2024-07-30)
#### https://task.uralsib.ru/browse/UCM-40471
* Исправлено обработка статусов из омни для OPEN_SERVICE_PACK (59)

## 2.4.67.1 (2024-07-29)
#### https://task.uralsib.ru/browse/UCM-40471
* Исправление заполнения ДТО при отправке в омни OPEN_SERVICE_PACK (59)

## 2.4.67 (2024-07-26)
[UCM-40471](https://task.uralsib.ru/browse/UCM-40471)
* Добавлены доп. атрибуты для АФС Спланк при процессинге 11 типа операций (CITYPLUS)

## 2.4.66 (2024-07-24)
[UCM-40335](https://task.uralsib.ru/browse/UCM-40335)
* Добавлена логика отправки запроса в AFS для операций 130 и 131, исправление замечаний Сонара

## 2.4.65 (2024-07-19)
[UCM-38345](https://task.uralsib.ru/browse/UCM-38345)
* в CHANGE_PHONE добавлен вызов /internal/mobile/block-token-by-profile

## 2.4.64 (2024-07-11)
[UCM-40164](https://task.uralsib.ru/browse/UCM-40164)
* Добавлены e-mail уведомления, пуш и смс об отказе операции AFS_DECLINED для 80 и 84 типа операций
 
## 2.4.63 (2024-07-08)
[UCM-40620](https://task.uralsib.ru/browse/UCM-40620)
* Реализована новая логика обработки операций 80 и 84 типа

## 2.4.62.13 (2024-07-16)
[UCM-41231](https://task.uralsib.ru/browse/UCM-41231)
* Удалены лишние символы из шаблона пуш/смс уведомления для AFS_DECLINED

## 2.4.62.12 (2024-07-15)
[UCM-40164](https://task.uralsib.ru/browse/UCM-40164)
* Поправила условие по отправки пушей для AFS_DECLINED

## 2.4.62.11 (2024-07-15)
[UCM-41152](https://task.uralsib.ru/browse/UCM-41152)
* В пуше для AFS_DECLINED слово "Банк" заменено на "банк"

## 2.4.62.10 (2024-07-12)
[UCM-41186](https://task.uralsib.ru/browse/UCM-41186)
* Исправлена ошибка некорректного перехода статуса 2 и 50 операции 38 при таймауте в статусе AFS_VISUAL_CONTROL

## 2.4.62.9 (2024-07-12)
[UCM-41158](https://task.uralsib.ru/browse/UCM-41158)
* Исправлена ошибка некорректного перехода статуса операции 38 при обработке ответа из XAFS v2

## 2.4.62.8 (2024-07-12)
[UCM-41158](https://task.uralsib.ru/browse/UCM-41158)
* Исправлена ошибка некорректного перехода статуса операции 38 при обработке ответа из XAFS

## 2.4.62.7 (2024-07-11)
[UCM-41125](https://task.uralsib.ru/browse/UCM-41125)
* Добавлена отправка атрибута "additionalCheckAfs" в AFS

## 2.4.62.6 (2024-07-11)
#### https://task.uralsib.ru/browse/UCM-40962
* WF CITYPLUS (XAFS,XAFS_WAIT_STATUS) исправлены баги:
  * При поиске бизнес атрибута (использовался attributeId, а должен был paramId)
  * При поиске атрибутов CATEGORY_ID (использовался attributeId, а должен value т.е. значение атрибута)

## 2.4.62.5 (2024-07-10)
[UCM-40164](https://task.uralsib.ru/browse/UCM-40164)
* Добавлены e-mail уведомления, пуш и смс об отказе операции AFS_DECLINED

## 2.4.62.4 (2024-07-09)
[UCM-40314](https://task.uralsib.ru/browse/UCM-40314)
* Исправлена ошибка при обработке ответа из AFS

## 2.4.62.3 (2024-07-09)
[UCM-32434](https://task.uralsib.ru/browse/UCM-32434)
* добавлен internal в ProfileClient -- profile/profiles/{profileId}/contacts

## 2.4.62.2 (2024-07-09)
#### https://task.uralsib.ru/browse/UCM-40587
* исправлено заполнение поля embosName для 59 типа операции
#### https://task.uralsib.ru/browse/UCM-40588
* учет 59 типа при обработке события из кафки по статусу доставки
#### https://task.uralsib.ru/browse/UCM-40470
* отключение отправки email для workflow = CARD_SERVICES_LINKER

## 2.4.62.1 (2024-07-09)
[UCM-40319](https://task.uralsib.ru/browse/UCM-40319)
* Изменен WF 50 операции для работы со статусом AFS_DECLINED

## 2.4.62 (2024-07-08)
[UCM-32434](https://task.uralsib.ru/browse/UCM-32434)
* deprecated метод GET/profile/internal/contacts-by-profile заменен на актуальный

## 2.4.61 (2024-07-05)
#### https://task.uralsib.ru/browse/UCM-35096
* WF CITYPLUS:
  * Добавлена обработка шага XAFS
  * Добавлена обработка шага XAFS_WAIT_STATUS

## 2.4.60 (2024-07-04)
[UCM-40485](https://task.uralsib.ru/browse/UCM-40485)
* 369 ФЗ. Доработка описаний статусов DECLINED, OPERATOR_APPROVED, AFS_VISUAL_CONTROL в WF 
 
## 2.4.59 (2024-07-04) 
* https://task.uralsib.ru/browse/UCM-40599
* Доработка OPEN_SERVICE_PACK (59) и его воркфлоу

## 2.4.58 (2024-07-02)
[UCM-40599](https://task.uralsib.ru/browse/UCM-40599)
* Доработка по 369 ФЗ. 8 операция

## 2.4.57 (2024-07-02)
[UCM-40314](https://task.uralsib.ru/browse/UCM-40314)
* Изменения в WF операции 2. Добавлен статус AFS_DECLINED

## 2.4.56 (2024-07-01)
[UCM-34510](https://task.uralsib.ru/browse/UCM-34510)
* добавить отправку в хафс 82 SBP_ME2ME (Перевод по СБП по инициативе получателя)

## 2.4.55 (2024-06-27)
[UCM-40627](https://task.uralsib.ru/browse/UCM-40627)
* удален SoapCityConnector, вызовы заменены на обращение к cityplusgate

## 2.4.54 (2024-06-28)
[UCM-37119](https://task.uralsib.ru/browse/UCM-37119)
* Исправлена работа с джобой таумаутов для всех воркфлоу с реализованным xAFS
* Общая функциональность обработки xafs статусов вынесена в AntiFraudProcessingService

## 2.4.53 (2024-06-27)
[UCM-34510](https://task.uralsib.ru/browse/UCM-34510)
* xAFS. измененено флоу для вейт статуса

## 2.4.52 (2024-06-27)
[UCM-34510](https://task.uralsib.ru/browse/UCM-34510)
* xAFS. Создавать синхронное событие для перевода c2c СБП 8,82

## 2.4.51 (2024-06-26)
[UCM-34517](https://task.uralsib.ru/browse/UCM-34517)
* Добавлено логирование в хистори для анализа в xAFS

## 2.4.50 (2024-06-25)
[UCM-34517](https://task.uralsib.ru/browse/UCM-34517)
* Добавлены обработчики воркфлоу статусов xAFS для заявки на кредитную карту (63 и 67 тип операции)

## 2.4.49 (2024-06-19)
[UCM-37119](https://task.uralsib.ru/browse/UCM-37119)
* Добавлены тесты на функционал получения резолюции от xafs
* Исправлен маппинг
* Кастомный обработчик исключений заменен на стандартный из common

## 2.4.48.6 (2024-07-02)
[UCM-32434](https://task.uralsib.ru/browse/UCM-32434)
* откат -- deprecated метод GET/profile/internal/contacts-by-profile заменен на актуальный

## 2.4.48.5 (2024-06-20)
[UCM-34513](https://task.uralsib.ru/browse/UCM-34513)
* В воркфлоу 37, 38, 39 добалены шаги:
  * XAFS
  * XAFS_WAIT_STATUS

## 2.4.48.4 (2024-06-20)
[UCM-34524](https://task.uralsib.ru/browse/UCM-34524)
* wf card2card:
  * Добавлен шаг XAFS
  * Добавлен шаг XAFS_WAIT_STATUS

## 2.4.48.3 (2024-06-19)
[UCM-37646](https://task.uralsib.ru/browse/UCM-37646)
* Переименование поля. Ошибка в спеке

## 2.4.48.2 (2024-06-18)
[UCM-40385](https://task.uralsib.ru/browse/UCM-40385)
* Исправление. PUSH_DISABLE пустой deviceId

## 2.4.48.1 (2024-06-17)
[UCM-37156](https://task.uralsib.ru/browse/UCM-37156)
* Написание хэдера изменено на капс - REFERER

## 2.4.48 (2024-06-17)
[UCM-40161](https://task.uralsib.ru/browse/UCM-40161)
* Изменен воркфлоу 11 типа операции

## 2.4.47 (2024-06-17)
[UCM-40322](https://task.uralsib.ru/browse/UCM-40322)
* Реализация workflow 20 и 36 типа операций

## 2.4.46 (2024-06-14)
[UCM-40267](https://task.uralsib.ru/browse/UCM-40267)
* Реализовано сохранение причины ошибки из Ретейла, при изменении ПД

## 2.4.45 (2024-06-11)
[UCM-36829](https://task.uralsib.ru/browse/UCM-36829)
* Отправка отклика APL в ЕБПП при отправке заявки на КК
* Изменена очередность отправки отклика APL в ЕБПП во всех местах где он отправляется

## 2.4.44 (2024-06-10)
[UCM-39360](https://task.uralsib.ru/browse/UCM-39360)
* Отправка флага ONE_CLICK в омни для заявки на КК

## 2.4.43 (2024-06-10)
[UCM-32434](https://task.uralsib.ru/browse/UCM-32434)
* deprecated метод GET/profile/internal/contacts-by-profile заменен на актуальный

## 2.4.42 (2024-06-10)
* [UCM-37119](https://task.uralsib.ru/browse/UCM-37119)
  * Реализован эндпойнт для обработки резолюции от xAFS
  * Поиск нужного обработчика вынесен в отдельный сервис
* [UCM-34517](https://task.uralsib.ru/browse/UCM-34517)
  * Добавлены обработчики воркфлоу статусов xAFS для заявки на цифровую кредитную карту (66 тип операции)

## 2.4.41.4 (2024-06-10)
[UCM-40144](https://task.uralsib.ru/browse/UCM-40144)
* Исправлен заголовок и графема в пуше для статуса DECLINED
 
## 2.4.41.3 (2024-06-06)
[UCM-39921](https://task.uralsib.ru/browse/UCM-39921)
* Добавлен пуш для СБП для DECLINED. Добавлен пробел в письме по AFS_VISUAL_CONTROL
 
## 2.4.41.2 (2024-05-31)
[UCM-39921](https://task.uralsib.ru/browse/UCM-39921)
* В пуш уведомлении и в email RUB заменен на графему ₽

## 2.4.41.1 (2024-05-27)
[UCM-38340](https://task.uralsib.ru/browse/UCM-38340)
* Изменен шаблон для email оповещения при переходе в статус  AFS_VISUAL_CONTROL

## 2.4.41 (2024-05-27)
[UCM-39038](https://task.uralsib.ru/browse/UCM-39038)
* Статус TO_DECLINED сделан реальным
* переработана логика определения стадии статуса при отмене заявки
* [UCM-39606](https://task.uralsib.ru/browse/UCM-39606) - 67 тип операции переводится в WAIT_OMNI_DECISION

## 2.4.40 (2024-05-24)
[UCM-38340](https://task.uralsib.ru/browse/UCM-38340)
* Баг на мастере по форматированию даты пуша

## 2.4.39 (2024-05-23)
[UCM-39137](https://task.uralsib.ru/browse/UCM-39137)
* Снять баннер изменения ПД при переводе операции 109 в COMPLETED

## 2.4.38 (2024-05-22)
[UCM-38340](https://task.uralsib.ru/browse/UCM-38340)
* Рефакторинг после код-ревью для отправки пушей и эл писем для операций в статусах AFS VISUAL CONTROL, DECLINED

## 2.4.37 (2024-05-21)
[UCM-38340](https://task.uralsib.ru/browse/UCM-38340)
* Добавление в WF операций отправку пушей, когда операция переходит в статус AFS VISUAL CONTROL

## 2.4.36.2 (2024-05-31)
* Редеплой

## 2.4.36.1 (2024-05-13)
[UCM-39151](https://task.uralsib.ru/browse/UCM-39151)
* При обработке операции с типом 84 в состояниях START и REPEAT_REQUEST исправлена логика передачи атрибута DevicePrint в Xafs

## 2.4.36 (2024-05-03)
[UCM-36489](https://task.uralsib.ru/browse/UCM-36489)
* При обработке операции с типом 84 в состояниях START и REPEAT_REQUEST добавлена логика передачи новых атрибутов в Xafs

## 2.4.35 (2024-04-22)
[UCM-37646](https://task.uralsib.ru/browse/UCM-37646)
* Изменено UNKNOWN_DEVICE_ID на NO_FOUND_WEB_DEVICE_ID; добавлено поле WEB_DEVICE_TOKEN

## 2.4.34 (2024-04-18)
[UCM-34330](https://task.uralsib.ru/browse/UCM-34330)
* Очистить error логи в operation-processing

## 2.4.33 (2024-04-22)
[UCM-38038](https://task.uralsib.ru/browse/UCM-38038)
* + UCM-38039 Добавлен статус CHECK_STATUS для 64, 68 типа операции. Для 67 также переработан CHECK_STATUS.

## 2.4.32 (2024-04-22)
[UCM-38593](https://task.uralsib.ru/browse/UCM-38593)
* Обработка ситуации с отсутствием данных у клиента при отправке данных в АФС

## 2.4.31.1 (2024-04-15)
[UCM-38266](https://task.uralsib.ru/browse/UCM-38266)
* Изменен ответ OmniCreditCardMapper, добавлена отправка причины неудачи в history, добавлены тесты

## 2.4.31 (2024-04-10)
[UCM-38292](https://task.uralsib.ru/browse/UCM-38292)
* СИТИ+. Доработка документа для ритейла

## 2.4.30.6 (2024-04-26)
[UCM-38292](https://task.uralsib.ru/browse/UCM-38292)
* Значение канала теперь получаю не из параметра операции, а из канала

## 2.4.30.5 (2024-04-26)
[UCM-38292](https://task.uralsib.ru/browse/UCM-38292)
* СИТИ+. Доработка документа для ритейла

## 2.4.30.4 (2024-04-15)
[UCM-37606](https://task.uralsib.ru/browse/UCM-37606)
* Доработка статуса WAIT_DECISION по операциям заказа карт с курьерской доставкой
* Учет повторных переводов в статус TO_DECLINED

## 2.4.30.3 (2024-04-12)
[UCM-38465](https://task.uralsib.ru/browse/UCM-38465)
* SIMPLE_TRANSFER. Шаг отправки документа в Ритейл:
  * Установка атрибута IS_ME2ME перенесена в отдельную функцию

## 2.4.30.2 (2024-04-12)
[UCM-38465](https://task.uralsib.ru/browse/UCM-38465)
* SIMPLE_TRANSFER. Шаг отправки документа в Ритейл:
  * Поиск параметра переименован с IS_ME2ME -> ISME2ME (т.к. при получении атрибута в коде зачем-то происходит реплейс с "_" на "")

## 2.4.30.1 (2024-04-10)
[UCM-38154](https://task.uralsib.ru/browse/UCM-38154)
* Изменено получение sessionId при формировании дто в OmniCreditCardOrderMapper

## 2.4.30 (2024-04-04)
[UCM-36595](https://task.uralsib.ru/browse/UCM-36595)
* Учет атрибута SIGN_DOCS_IN_DBO в воркфлоу CRIF

## 2.4.29 (2024-04-01)
[UCM-34772](https://task.uralsib.ru/browse/UCM-34772)
* WORKFLOW операции 71 DISABLE_PUSH_NOTIFICATION_WEB (Отключение пушей в Web)

## 2.4.28 (2024-04-02)
[UCM-37189](https://task.uralsib.ru/browse/UCM-37189)
* С2Б СБП. Передавать признак SBP_OPER_CATEGORY в ОМНИ в запросе на платеж.

## 2.4.27 (2024-04-02)
[UCM-37227](https://task.uralsib.ru/browse/UCM-37227)
* SIMPLE_TRANSFER. Шаг отправки документа в Ритейл:
  * При наличии атрибута IS_ME2ME заполняется поле для ритейловского документа IS_ME2ME

## 2.4.26 (2024-03-29)
[UCM-37588](https://task.uralsib.ru/browse/UCM-37588)
* для операций SBP (8 и 82), на шаге отправки документа в ритейл добавлено заполнение параметра SBP_OPER_CATEGORY

## 2.4.25.1 (2024-03-29)
[UCM-37457](https://task.uralsib.ru/browse/UCM-37457)
* Добавил javaTimeModule для сериализации при отправке в History

## 2.4.25 (2024-03-19)
[UCM-37194](https://task.uralsib.ru/browse/UCM-37194)
* UCM-37194 СИТИ+ по номеру телефона. Запрос на списание

## 2.4.24.6 (2024-04-03)
[UCM-38154](https://task.uralsib.ru/browse/UCM-38154)
* Исправлено формирование variables useragent OmniCreditCardOrderMapper

## 2.4.24.5 (2024-04-03)
[UCM-38154](https://task.uralsib.ru/browse/UCM-38154)
* Исправлено формирование variables OmniCreditCardOrderMapper при отсутствии сессиии

## 2.4.24.4 (2024-04-03)
[UCM-38154](https://task.uralsib.ru/browse/UCM-38154)
* Добавлена проверка при получении сессии OmniCreditCardOrderMapper

## 2.4.24.3 (2024-03-21)
[UCM-37620](https://task.uralsib.ru/browse/UCM-37620)
* Исправлено обогащения regionName в DeliveryAddressMapper 

## 2.4.24.2 (2024-03-21)
[UCM-37620](https://task.uralsib.ru/browse/UCM-37620)
* Добавил обязательность и доп возможность обогащения regionName в DeliveryAddressMapper 

## 2.4.24.1 (2024-03-19)
[UCM-37515](https://task.uralsib.ru/browse/UCM-37515)
* Добавил явное обогащение isInsured в OmniCreditCardOrderMapper 

## 2.4.24 (2024-03-11)
[UCM-34771](https://task.uralsib.ru/browse/UCM-34771)
* флоу операции 70 типа (подключение пушей в веб)

## 2.4.23 (2024-02-26)
[UCM-36467](https://task.uralsib.ru/browse/UCM-36467)
* С2С/Ме2Ме добавить отправку атрибутов в ритейл (холдирование) и в золотую корону через тибко (подтверждение)

## 2.4.22.11 (2024-03-15)
[UCM-37447](https://task.uralsib.ru/browse/UCM-37447)
* Добавлено условие отправки в crif по ОМНИ (перевод КК на ОМНИ).

## 2.4.22.10 (2024-03-14)
[UCM-37432](https://task.uralsib.ru/browse/UCM-37432)
* Изменено формирование consentOnSending для OmniCreditCardOrder для отправки КК в ОМНИ.

## 2.4.22.9 (2024-03-13)
[UCM-37346](https://task.uralsib.ru/browse/UCM-37346)
* Добвалено формирование DELIVERY_ADDRESS из значений атрибутов.

## 2.4.22.8 (2024-03-12)
[UCM-37346](https://task.uralsib.ru/browse/UCM-37346)
* Добвалено формирование REGISTRATION_ADDRESS из значений атрибутов.

## 2.4.22.7 (2024-03-11)
[UCM-37071](https://task.uralsib.ru/browse/UCM-37071)
* Реализована отправка KLADR адреса доставки в омни для заявки на доставку КК

## 2.4.22.6 (2024-01-05)
[UCM-37089](https://task.uralsib.ru/browse/UCM-37089)
* Добавлено значение OmniCreditCardOrder для заявки КК в ОМНИ

## 2.4.22.5 (2024-01-01)
[UCM-36975](https://task.uralsib.ru/browse/UCM-36975)
* Исправлено формирование дат на OffsetDateTime КК в ОМНИ

## 2.4.22.4 (2024-02-29)
[UCM-36975](https://task.uralsib.ru/browse/UCM-36975)
* Исправлено формирование даты переменной update для отправки в омни

## 2.4.22.3 (2024-02-27)
[UCM-34637](https://task.uralsib.ru/browse/UCM-34637)
* Исправлено формирование дат сообщения для отправки заявки КК в ОМНИ

## 2.4.22.2 (2024-02-27)
[UCM-34637](https://task.uralsib.ru/browse/UCM-34637)
* Исправлено формирование сообщения для отправки заявки КК в ОМНИ

## 2.4.22.1 (2024-02-26)
[UCM-34637](https://task.uralsib.ru/browse/UCM-34637)
* Добавлена отправка ключа сообщения при отправки заявки КК в ОМНИ

## 2.4.22 (2024-02-22)
[UCM-34644](https://task.uralsib.ru/browse/UCM-34644)
* Реализация статуса CHECH_STATUS для 53 типа операции

## 2.4.21 (2024-02-21)
[UCM-34211](https://task.uralsib.ru/browse/UCM-34211) [UCM-36805](https://task.uralsib.ru/browse/UCM-36805)
* WORKFLOW операции 110 CREATE_DNT (создание ДНТ)
* Формирование и отправка событий в AFS для операции создания ДНТ

## 2.4.20 (2024-02-20)
[UCM-36770](https://task.uralsib.ru/browse/UCM-36770)
* Реализован воркфлоу статус ожидания решения по заявке на КК из ОМНИ (WAIT_OMNI_DECISION)

## 2.4.19 (2024-02-15)
[UCM-34330](https://task.uralsib.ru/browse/UCM-34330)
* Очистить error логи в operation-processing

## 2.4.18.7 (2024-02-22)
[UCM-35221](https://task.uralsib.ru/browse/UCM-35221)
* фикс валидации и отправки аттрибута

## 2.4.18.6 (2024-02-09)
[UCM-36240](https://task.uralsib.ru/browse/UCM-36240)
* Обработка псевдо-статуса TO_DECLINED

## 2.4.18.5 (2024-02-08)
[UCM-36325](https://task.uralsib.ru/browse/UCM-36325)
* Исправлена ошибка не заполнения omniDeliveryStatus

## 2.4.18.4 (2024-02-08)
[UCM-36240](https://task.uralsib.ru/browse/UCM-36240)
* В declined переводим если имеется CancellationReason

## 2.4.18.3 (2024-02-08)
* Пересборка с новым common (исправления десериализации некоторых объектов)

## 2.4.18.2 (2024-02-06)
[UCM-34639](https://task.uralsib.ru/browse/UCM-34639)
* Реализован воркфлоу для получения актуального статуса заявки на КК из ОМНИ

## 2.4.18.1 (2024-02-05)
[UCM-34638](https://task.uralsib.ru/browse/UCM-34638)
* Реализовано получение статуса заявки от омни

## 2.4.18 (2024-02-05)
[UCM-33890](https://task.uralsib.ru/browse/UCM-33890)
* Для статусной модели добавлен тип операции OPENING_CREDIT_CARD_DELIVERY.
* [UCM-36228] (https://task.uralsib.ru/browse/UCM-36228) 
* Добавление статуса delivery_status_stage_1 для "нулевого" виджета статуса курьерской доставки

## 2.4.17 (2024-02-02)
[UCM-34637](https://task.uralsib.ru/browse/UCM-34637)
* Реализована возможность отправлять заявки на КК через ОМНИ, изменения закрыты флагом

## 2.4.16 (2024-01-31)
[UCM-34640](https://task.uralsib.ru/browse/UCM-34640)
* Реализована возможность отправлять заявки на КК через ОМНИ, изменения закрыты флагом
* Убрано использование OperationClient в бизнес-слое, использован OperationService

## 2.4.15 (2024-01-31)
[UCM-36168](https://task.uralsib.ru/browse/UCM-36168)
* Исправление отправки данных в ретейл и афс

## 2.4.14 (2024-01-29)
[UCM-35493](https://task.uralsib.ru/browse/UCM-35493)
* common fix

## 2.4.13 (2024-01-29)
[UCM-35493](https://task.uralsib.ru/browse/UCM-35493)
* (CITYPLUS.RTLTRANSFER) добавлено заполнение параметра CITYCATEGORY

## 2.4.12.2 (2024-01-19)
[UCM-35819](https://task.uralsib.ru/browse/UCM-35819)
* Исправление заполнения аттрибутов операции 109 типа

## 2.4.12.1 (2024-01-19)
[UCM-33890](https://task.uralsib.ru/browse/UCM-33890)
* Доработка обработки статусов из омни по выпуску/перевыпуску карт

## 2.4.12 (2023-12-20)
[UCM-33107](https://task.uralsib.ru/browse/UCM-33107)
* Доработка кредитных вокрфлоу с учетом новых типов кредитных анкет

## 2.4.11.3 (2023-12-26)
[UCM-35420](https://task.uralsib.ru/browse/UCM-35420)
* Фикс названия поля для ретейла

## 2.4.11.1 (2023-12-22)
[UCM-35371](https://task.uralsib.ru/browse/UCM-35371)
* Фикс отправки данных операции изменения паспорта в ретейл 

## 2.4.11 (2023-12-18)
[UCM-33790](https://task.uralsib.ru/browse/UCM-33790)
* Отправка данных операции изменения паспорта в АФС  

## 2.4.10 (2023-12-11)
[UCM-34796](https://task.uralsib.ru/browse/UCM-34796)
* Реализована отправка атрибута BRANCH в омни

## 2.4.9 (2023-12-07)
[UCM-33778](https://task.uralsib.ru/browse/UCM-33778)
[UCM-34962](https://task.uralsib.ru/browse/UCM-34962)
* Редактирование ПД. Добавить новый тип операции

## 2.4.8.2 (2023-12-15)
[UCM-35165](https://task.uralsib.ru/browse/UCM-35165)
* Пересборка сервиса для подтягивания новых изменений коммона

## 2.4.8.1 (2023-11-22)
[UCM-34666](https://task.uralsib.ru/browse/UCM-34666)
* Исправлен баг - в заявке в ОМНИ время доставки отправляется некорректно

## 2.4.8 (2023-11-22)
[UCM-33709](https://task.uralsib.ru/browse/UCM-33709)
* Убрал лишние поля из заказа справки для госслужащищ

## 2.4.7 (2023-11-22)
[UCM-33709](https://task.uralsib.ru/browse/UCM-33709)
* Отредактирован флоу для операций ORDER_REFERENCE_CIVIL_SERVANTS

## 2.4.6 (2023-11-20)
[UCM-33888](https://task.uralsib.ru/browse/UCM-33888)
* добавлен POST /internal/debit-card-order-status
* UCM-33890 - добавлен POST /internal/card-delivery-status
* UCM-33905 - добавлен POST /internal/debit-card-reissue-status

## 2.4.5 (2023-11-08)
[UCM-33778](https://task.uralsib.ru/browse/UCM-33778)
* Редактирование ПД. Добавить новый тип операции

## 2.4.4 (2023-11-08)
[UCM-34088](https://task.uralsib.ru/browse/UCM-34088)
* CRIF: в APPROVED_MKK обрабатываем статус от крифа CANCEL

## 2.4.3 (2023-11-01)
[UCM-33709](https://task.uralsib.ru/browse/UCM-33709)
* Создан флоу для операций ORDER_REFERENCE_CIVIL_SERVANTS

## 2.4.2 (2023-11-01)
[UCM-33883](https://task.uralsib.ru/browse/UCM-33883)
* Расширение dto OrderStatusDto

## 2.4.1 (2023-10-26)
[UCM-32777](https://task.uralsib.ru/browse/UCM-32777)
* Рефакторинг UNISTREAM_SEND:
  * Переход от switch/case на интерфейс Command

## 2.4.0.3 (2023-10-31)
[UCM-34027](https://task.uralsib.ru/browse/UCM-34027)
* WF UNISTREAM_REFUND(122):
  * CHECK_STATUS теперь ожидает статус не "REFUND", а "NEW"

## 2.4.0.2 (2023-10-24)
[UCM-33614](https://task.uralsib.ru/browse/UCM-33614)
* Убрана устаревшая проверка templateDKO для CRIF.CRIF_APPROVE

## 2.4.0.1 (2023-10-18)
[UCM-33704](https://task.uralsib.ru/browse/UCM-33704)
* Исправление запроса при отправке в онми на перевыпуска карт

## 2.4.0 (2023-10-18)
[UCM-33726](https://task.uralsib.ru/browse/UCM-33726)
* Переведен на JDK 17

## 2.3.32 (2023-10-05)
[UCM-33411](https://task.uralsib.ru/browse/UCM-33411)
* CARD_SERVICES_LINKER - добавлено ограничение времени и кол-во попыток вынесено в конфиг

## 2.3.31.3 (2023-10-12)
[UCM-33593](https://task.uralsib.ru/browse/UCM-33593)
* SET_PIN после перевода в анализ процесс не прерывался

## 2.3.31.2 (2023-09-29)
[UCM-31762](https://task.uralsib.ru/browse/UCM-31762)
* Время между повторным запросом статуса APPROVED_MKK берется из отдельной проперти

## 2.3.31.1 (2023-09-28)
[UCM-32493](https://task.uralsib.ru/browse/UCM-32493)
* UNISTREAM_SEND.CHECK_RESULT, если пришла ошибка с CITY+, то более не устанавливается statusDescription у операции из параметра errMsg

## 2.3.31 (2023-09-25)
[UCM-32492](https://task.uralsib.ru/browse/UCM-32492)
* Рефакторинг WF UNISTREAM_REFUND:
  * CHECK_STATUS. Проверяется статус у REFUND_KEY, вместо ITEM_KEY

## 2.3.30 (2023-09-22)
[UCM-32492](https://task.uralsib.ru/browse/UCM-32492)
* Рефакторинг WF UNISTREAM_REFUND:
  * Добавлены описания
  * Исправлен npe
  
## 2.3.29 (2023-09-22)
[UCM-32492](https://task.uralsib.ru/browse/UCM-32492)
* Добавлен обработчик WF UNISTREAM_REFUND type=122
* Рефакторинг WF UNISTREAM_RECEIVE:
  * Переход процессора и обработки шагов на Command

## 2.3.28 (2023-09-21)
[UCM-31139](https://task.uralsib.ru/browse/UCM-31139)
* Доработка флоу для сохранения событий

## 2.3.27 (2023-09-20)
[UCM-32562](https://task.uralsib.ru/browse/UCM-32562)
* Доработки воркфлоу CARD_ISSUE, рефакторинг использования констант и клиента мс operation
[UCM-32564](https://task.uralsib.ru/browse/UCM-32564)
* Доработки воркфлоу CARD_ISSUE_DIGITAL, рефакторинг использования констант и клиента мс operation

## 2.3.26 (2023-09-20)
[UCM-32763](https://task.uralsib.ru/browse/UCM-32763)
* Добавлена логика workflow: CREDITCARD_REISSUE_DELIVERY, DEBITCARD_REISSUE_DELIVERY

## 2.3.25 (2023-09-19)
[UCM-32444](https://task.uralsib.ru/browse/UCM-32444)
* WF UNISTREAM_RECEIVE
  * В TransferStatus добавлено новое значение PAY_VALIDATE
  * для CHECK_RESULT установлен корректный тип
  
## 2.3.24 (2023-09-19)
[UCM-32444](https://task.uralsib.ru/browse/UCM-32444)
* WF UNISTREAM_SEND:
  * Доработаны тесты с учётом вынесенного общего кода для в хелпер по юнистрим
  * Параметры @Value вынесены в UnistreamProperty
* Добавлен обработчик WF UNISTREAM_RECEIVE type=121

## 2.3.23 (2023-09-11)
[UCM-32219](https://task.uralsib.ru/browse/UCM-32219)
* WF UNISTREAM_SEND:
  * При изменении статуса описание статуса более нигде не заполняется.
  * Логи истории расширены для статусов CHECK_STATUS,CHECK_RESULT

## 2.3.22 (2023-09-11)
[UCM-32219](https://task.uralsib.ru/browse/UCM-32219)
* WF UNISTREAM_SEND:
  * Штатные переходы из статуса в статус более не влекут изменение описание статуса операции

## 2.3.21 (2023-09-08)
[UCM-32219](https://task.uralsib.ru/browse/UCM-32219)
* Дорабвлен обработчик WF UNISTREAM_SEND type=120

## 2.3.20.1 (2023-09-06)
[UCM-31080](https://task.uralsib.ru/browse/UCM-31080)
* Фикс по рефактору CRIF

## 2.3.20 (2023-08-30)
[UCM-32471](https://task.uralsib.ru/browse/UCM-32471)
* Ограничиваем кол-во символов для employerName. OPEN_DIGITAL_CREDITCARD.SEND_DOCUMENT_OMNICHANNEL

## 2.3.19 (2023-08-28)
[UCM-32281](https://task.uralsib.ru/browse/UCM-32281)
* При формировании документа о действии с карточной опцией добавлен параметр типа оповещений (SMS_TYPE)

## 2.3.18 (2023-08-21)
[UCM-31080](https://task.uralsib.ru/browse/UCM-31080)
*  Для воркфлоу CRIF определение пути по typeCode
* [UCM-31762](https://task.uralsib.ru/browse/UCM-31762)
* Займы МКК. Новый статус в воркфлоу CRIF и DOC_FROM_CRIF
* Рефактор CRIF

## 2.3.17.1 (2023-08-18)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
* Добавил обработку случая, когда при нахождении документа в очереди на обработку
происходит отмена оператором

## 2.3.17 (2023-08-03)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
* Переименовал длинные названия классов

## 2.3.16.2 (2023-08-08)
[UCM-31932](https://task.uralsib.ru/browse/UCM-31932)
* FIX: не поступает смс после звонка КЦ
* FIX: операция не по флоу

## 2.3.16.1 (2023-07-25)
[UCM-31633](https://task.uralsib.ru/browse/UCM-31633)
* FIX: При отправке заявки в омни отдаем параметр authType вместо docAuthType

## 2.3.16 (2023-07-24)
[UCM-31047](https://task.uralsib.ru/browse/UCM-31047)
* Переход на enum OperationTypeId и отказ от interface OperationTypeIds

## 2.3.15.2 (2023-07-07)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
* Добавил обработку статусов POSTPONE и CHECK_POSTPONE

## 2.3.15.1 (2023-07-06)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* Изменён текст логирования при обработке событий

## 2.3.15 (2023-07-03)
[UCM-30843](https://task.uralsib.ru/browse/UCM-30843)
* Выключение валидации запрещенных слов в операции СБП

## 2.3.14 (2023-07-03)
[UCM-30843](https://task.uralsib.ru/browse/UCM-30843)
* Выключение валидации запрещенных слов в операции СБП, если включена валидация до создания операции.

## 2.3.13.5 (2023-07-05)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
* Добавил обязательное поле - код бранча

## 2.3.13.4 (2023-07-05)
[UCM-30949](https://task.uralsib.ru/browse/UCM-30949)
* WF "Изм. лимитного плана" id=103:
  * Поиск контакта(номер телефона) теперь ведётся через актуальный метод
  * Отправка смс теперь фиксируется в логах WF

## 2.3.13.3 (2023-07-04)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
* Поменял тип поля. Приходит лонг, но мы превращали в инт - портили данные

## 2.3.13.2 (2023-07-04)
[UCM-31133](https://task.uralsib.ru/browse/UCM-31133)
* Добавлена проверка на зависание операции в статусе WAIT_DECISION

## 2.3.13.1 (2023-07-04)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
* Добавил недостающие классы для обработки статусов 

## 2.3.13 (2023-06-30)
[UCM-31169](https://task.uralsib.ru/browse/UCM-31169)
* Исправление NPE при удалении счетов SBPay

## 2.3.12 (2023-06-28)
[UCM-30263](https://task.uralsib.ru/browse/UCM-30263)
* Отправка заявки в омни по заказу дебетовой карты с курьеркой

## 2.3.11 (2023-06-28)
[UCM-29976](https://task.uralsib.ru/browse/UCM-29976)
* Реализована обработка удаления счетов SBPay

## 2.3.10 (2023-06-26)
[UCM-30949](https://task.uralsib.ru/browse/UCM-30949)
* WF "Изменение лимитного плана" (103):
  * Убрана обработка статуса DECLINED_BY_OPERATOR
  * Добавлена обработка статуса MISSED_CALL
  * Добавлена обработка статуса WAIT_ACTIVATION

## 2.3.9 (2023-06-26)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
*  Правка с ревью

## 2.3.8 (2023-06-26)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
*  Доработка флоу смена номера телефона

## 2.3.7 (2023-06-26)
[UCM-29544](https://task.uralsib.ru/browse/UCM-29544)
*  Доработка флоу сбер сити

## 2.3.6 (2023-06-23)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
*  Изменил текст сообщений по новой доке

## 2.3.5 (2023-06-21)
[UCM-30934](https://task.uralsib.ru/browse/UCM-30934)
* Чуть отрефакторил вызов отправки history event и добавл отправку ивента при откладывании обработки документа на 
следующий опер день

## 2.3.4 (2023-06-19)
[UCM-30864](https://task.uralsib.ru/browse/UCM-30864)
*  Создан метод для получения времени между повторным запросом для кредитных workflow

## 2.3.3.5 (2023-06-28)
[UCM-31062](https://task.uralsib.ru/browse/UCM-31062)
* Добавлена одновременная отправка csv и pdf выписок

## 2.3.3.4 (2023-06-19)
[UCM-30478](https://task.uralsib.ru/browse/UCM-30478)
*  Подправлена обработка отрицательных ответов при отправке выписки

## 2.3.3.3 (2023-06-15)
[UCM-30478](https://task.uralsib.ru/browse/UCM-30478)
*  В енам добавлены статусы, которых не было

## 2.3.3.2 (2023-06-15)
[UCM-30808](https://task.uralsib.ru/browse/UCM-30808)
*  Добавлена обработка отрицательных ответов при отправке выписки

## 2.3.3.1 (2023-06-13)
[UCM-30384](https://task.uralsib.ru/browse/UCM-30384)
*  Добавлена задержка перед запросом статуса документов у крифа для 39 типа операции

## 2.3.3 (2023-06-13)
[UCM-29209](https://task.uralsib.ru/browse/UCM-29209)
*  Добавлена обработка форкфлоу SEND_STATEMENT

## 2.3.2 (2023-06-11)
[UCM-30486](https://task.uralsib.ru/browse/UCM-30486)
* version 5 кредитной анкеты

## 2.3.1 (2023-06-09)
[UCM-30228](https://task.uralsib.ru/browse/UCM-30228)
* Доработать WORKFLOW операции 104 CHANGE_PHONE (изменение номера телефона). Сделал всё, кроме реализации статусов CHECK_POSTPONE, POSTPONE

## 2.3.0 (2023-06-05)
[UCM-28532](https://task.uralsib.ru/browse/UCM-28532)
* Для воркфлоу-комманд внедрен единый интерфейс Command
* Для воркфлоу-статусов внедрен единый интерфейс WorkflowStatus
* Для поиска необходимой команды к выполнению реализован сервис CommandService
* Флоу CARD_SERVICE_LINKER переведено на команды и отрефакторено
* Исправлена опечатка в проперте CardServiceLinkerProperties#fillEmailEnabled
* Реализован сервис работы с событиями HistoryEventService
* OperationService изменен в соответствии с новым интерфейсом статусов операций - WorkflowStatus
* Удален устаревший утилитарный класс OperationAttributeUtils
* В тестах добавлены конфигурации запуска, мокающие внешние системы для написания интеграционных тестов

## 2.2.41.6 (2023-05-25)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* Изменил механизм получения времени начала / окончания обработки документа 

## 2.2.41.5 (2023-05-23)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* Добавил логирование

## 2.2.41.4 (2023-05-24)
* Поправил учёт времени старта и завершения операции получения данных карты

## 2.2.41.3 (2023-05-23)
[UCM-30366](https://task.uralsib.ru/browse/UCM-30366)
* Для CrifStatus и OrderStatus добавил обработку ошибок в методе получения значения енама
* Для статусов воркфлоу 66-ой операции CHECK_STATUS, CRIF_APPROVE, DECLINED_BY_BANK_SYSTEM, WAIT_FOR_DECISION актуализированы статусы для перевода в ANALYSIS

## 2.2.41.2 (2023-05-23)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* Поправил учёт времени старта, окончания обработки

## 2.2.41.1 (2023-05-23)
[UCM-30374](https://task.uralsib.ru/browse/UCM-30374)
* Правка бага

## 2.2.41 (2023-05-22)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* Добавил недостающие отправки в AFS

## 2.2.40 (2023-05-22)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* Поправил дублирование при обработке статуса

## 2.2.39 (2023-05-22)
[UCM-30297](https://task.uralsib.ru/browse/UCM-30297)
* Поправил тесты по операции получения данных карты

## 2.2.38 (2023-05-18)
[UCM-30297](https://task.uralsib.ru/browse/UCM-30297)
* Поправил запрос confirmationId при обработке операции получения данных карты

## 2.2.37 (2023-05-16)
[UCM-28891](https://task.uralsib.ru/browse/UCM-28891)
* Реализована отправка данных в AFS по статусам операции получения данных карты

## 2.2.36 (2023-05-16)
[UCM-29436](https://task.uralsib.ru/browse/UCM-29436)
* Добавлена обработка очереди `operation-processing-remove-expired-operator-block-queue`

## 2.2.35.4 (2023-05-11)
[UCM-29626](https://task.uralsib.ru/browse/UCM-29626)
* Исправлена проблема обработки пустых атрибутов адреса приходящих от dadata

## 2.2.35.3 (2023-05-03)
[UCM-30018](https://task.uralsib.ru/browse/UCM-30018)
* Добавлен статус ANALYSIS в операцию получения данных карты

## 2.2.35.2 (2023-05-03)
[UCM-27524](https://task.uralsib.ru/browse/UCM-27524)
* Поменял тип лога для события, отправляемого в AFS

## 2.2.35.1 (2023-05-02)
[UCM-29626](https://task.uralsib.ru/browse/UCM-29626)
* Доработана отправка в омни заявки на кредитную карту (адрес регистрации)

## 2.2.35 (2023-05-02)
[UCM-27524](https://task.uralsib.ru/browse/UCM-27524)
* Отправка в AFS при прохождении статусов в процессе смены телефона

## 2.2.34.1 (2023-05-02)
[UCM-29941](https://task.uralsib.ru/browse/UCM-29941)
* Если *_LIMIT_AMOUNT = 0, то передавать maxOperations = 0

## 2.2.34 (2023-05-02)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* Добавил обработку статусов, на которых ничего не происходит для WORKFLOW операции 104 CHANGE_PHONE (изменение номера
  телефона)

## 2.2.33 (2023-04-28)
[UCM-29821](https://task.uralsib.ru/browse/UCM-29821)
* cоздан воркфлоу GET_CARD_DETAILS

## 2.2.32 (2023-04-26)
[UCM-27662](https://task.uralsib.ru/browse/UCM-27662)
* WORKFLOW операции 104 CHANGE_PHONE (изменение номера телефона)

## 2.2.31 (2023-04-24)
[UCM-29379](https://task.uralsib.ru/browse/UCM-29379)
* Сохранение аттрибута CRIF_NUMBER

## 2.2.30 (2023-04-19)
[UCM-28909](https://task.uralsib.ru/browse/UCM-28909)
* cоздан воркфлоу CHANGE_CARD_LIMIT

## 2.2.29 (2023-04-06)
[UCM-29037](https://task.uralsib.ru/browse/UCM-29037)
* Оптимизация кредитной карты

## 2.2.28 (2023-03-10)
[UCM-28628](https://task.uralsib.ru/browse/UCM-28628)
* Перевод уровня логирования в WARN если событие имеет развитие процесса.

## 2.2.27 (2023-03-01)
[UCM-28491](https://task.uralsib.ru/browse/UCM-28491)
* Добавить событие в процессинг операции сити+

## 2.2.26.2 (2023-03-03)
[UCM-26861](https://task.uralsib.ru/browse/UCM-26861)
* исправлен маппинг запроса в product-manager для обновления данных по карточным услугам

## 2.2.26.1 (2023-03-02)
[UCM-26861](https://task.uralsib.ru/browse/UCM-26861)
* добавлен статус воркфлоу WAIT_RETAIL_FOR_COMPLETED и его обработка (Ожидаем переподключение услуги в ритейле)

## 2.2.26 (2023-02-27)
[UCM-26499](https://task.uralsib.ru/browse/UCM-26499)
* Для 38,39,63,66,67 изменение работы статуса DECLINED_BY_OPERATOR 
* Добавлен статус CHECK_STATUS

## 2.2.25 (2023-02-22)
[UCM-27225](https://task.uralsib.ru/browse/UCM-27225)
* 6 шаг. ЗК. Создание операции, ее Workflow и метода для старта операции

## 2.2.24 (2023-02-22)
[UCM-26861](https://task.uralsib.ru/browse/UCM-26861)
* Исправлен переход в статус COMPLETED для операций с типом 21(SMS_INFO), 22 (COMPLIMENT), 23 (TIME_PRESENT)

## 2.2.23 (2023-02-20)
[UCM-26861](https://task.uralsib.ru/browse/UCM-26861)
* Обращение в кэш при подключении карточный услуги

## 2.2.22 (2023-02-13)
[UCM-27977](https://task.uralsib.ru/browse/UCM-27977)
* Оплата услуг. Холдирование средств
* fix fix fix

## 2.2.21.7 (2023-02-15)
[UCM-28070](https://task.uralsib.ru/browse/UCM-28070)
* поменял ожидаемый тип атрибута deadlineSigning 38-ой операции на LocalDateTime

## 2.2.21.6 (2023-02-14)
[UCM-28070](https://task.uralsib.ru/browse/UCM-28070)
* поменял ожидаемый тип атрибута deadlineSigning 39-ой операции на LocalDateTime

## 2.2.21.5 (2023-02-10)
[UCM-28029](https://task.uralsib.ru/browse/UCM-28029)
* typeAdditionalPhoneOwner заменен на typeOwnerAdditionalPhone

## 2.2.21.4 (2023-02-09)
[UCM-27866](https://task.uralsib.ru/browse/UCM-27866)
* Добавлен статус воркфлоу DOWNLOAD_PARAMETERS для 39-го типа операции

## 2.2.21.3 (2023-02-08)
[UCM-27307](https://task.uralsib.ru/browse/UCM-27307)
* Исправлено заполнения поля RequestedAmount   

## 2.2.21.2 (2023-02-08)
[UCM-27866](https://task.uralsib.ru/browse/UCM-27866)
* Добавлен статус воркфлоу DOWNLOAD_PARAMETERS для 39-го типа операции
* Убрано использование дефолтного значения в случае отсутствия DEADLINE_SIGNING

## 2.2.21.1 (2023-02-06)
[UCM-27307](https://task.uralsib.ru/browse/UCM-27307)
* Учитываем typeCode CARD

## 2.2.21 (2023-02-03)
[UCM-27307](https://task.uralsib.ru/browse/UCM-27307)
* Доработан запрос в омниканальную платформу

## 2.2.20 (2023-02-03)
[UCM-26343](https://task.uralsib.ru/browse/UCM-26343)
* UCM-26343 [REST] В методе холдирования средств для СБП передавать телефон получателя

## 2.2.19.2 (2023-01-26)
[UCM-27579](https://task.uralsib.ru/browse/UCM-27579)
* Добавить во флоу СИТИ+ (11 тип) проверку на тоггл

## 2.2.19.1 (2023-01-17)
[UCM-25239](https://task.uralsib.ru/browse/UCM-25239)
* исправлена работа с флагом crif.is-downloading-loan-parameters-enabled

## 2.2.19 (2023-01-10)
[UCM-26708](https://task.uralsib.ru/browse/UCM-26708)
* таймаут на ожидание ответа от омни по ВФ привязка счета c2b

## 2.2.18 (2022-12-22)
[UCM-26262](https://task.uralsib.ru/browse/UCM-26262)
* магическая пересборка

## 2.2.17 (2022-12-22)
[UCM-25239](https://task.uralsib.ru/browse/UCM-25239)
* Функционал задачи закрыт флагом is-downloading-loan-parameters-enabled

## 2.2.16 (2022-12-22)
[UCM-26262](https://task.uralsib.ru/browse/UCM-26262)
* CИТИ+. Холдирование/расхолдирование средств + правки в WF
* fix

## 2.2.15 (2022-12-19)
[UCM-25239](https://task.uralsib.ru/browse/UCM-25239)
* Новые статусы у 39 типа из-за получений параметров по кредиту от крифа

## 2.2.14.1 (2022-11-25)
[UCM-26267](https://task.uralsib.ru/browse/UCM-26267)
* Исключили шаг OPERATOR_PROCESSING из ВФ операции 103 типа

## 2.2.14 (2022-11-18)
[UCM-21235](https://task.uralsib.ru/browse/UCM-21235)
* Новые статусы для workflow = CRIF

## 2.2.13 (2022-11-17)
[UCM-21235](https://task.uralsib.ru/browse/UCM-21235)
* Новые статусы для workflow = CRIF

## 2.2.12 (2022-11-07)
[UCM-25284](https://task.uralsib.ru/browse/UCM-25284)
* Новый флоу для операции смены лимитов

## 2.2.11 (2022-11-07)
[UCM-25212](https://task.uralsib.ru/browse/UCM-25212)
* Выпилить соап клиенты РБС

## 2.2.10.4 (2022-11-07)
[UCM-25212](https://task.uralsib.ru/browse/UCM-25212)
* срочный вывод версии 2.2.11

## 2.2.10.3 (2022-11-07)
[UCM-24496](https://task.uralsib.ru/browse/UCM-24496)
* доработки по c2b привязка счета (обработка rcvMcc null)

## 2.2.10.2 (2022-11-03)
[UCM-25725](https://task.uralsib.ru/browse/UCM-25725)
* Установить таймаут запроса АФС 10 сек

## 2.2.10.1 (2022-11-01)
[UCM-25269](https://task.uralsib.ru/browse/UCM-25269)
* Убрано использование сервиса Messages, т.к. от этого функционала отказались

## 2.2.10 (2022-10-24)
[UCM-25182](https://task.uralsib.ru/browse/UCM-25182)
* Добавлен параметр hashApp для отправки в омни по ЦКК 

## 2.2.9.9 (2022-10-25)
[UCM-25521](https://task.uralsib.ru/browse/UCM-25521)
* исправлена отправка пуша при отказе в simpleTransfer

## 2.2.9.8 (2022-10-25)
[UCM-24496](https://task.uralsib.ru/browse/UCM-24496)
* доработки по воркфлоу c2b привязка счета

## 2.2.9.7 (2022-10-24)
[UCM-24496](https://task.uralsib.ru/browse/UCM-24496)
* доработки по воркфлоу c2b привязка счета

## 2.2.9.6 (2022-10-20)
[UCM-25385](https://task.uralsib.ru/browse/UCM-25385)
* для 38 типа операций перенёс функционал обработки статуса DECLINED_BY_BANK_SYSTEM в обработку TIME_OUT_SIGN. 
Для того чтобы не переводить в DECLINED статус, если от крифа уже получили другой статус

## 2.2.9.5 (2022-10-20)
[UCM-25418](https://task.uralsib.ru/browse/UCM-25418)
* исправил опечатки в отправке пуша об отмене операции

## 2.2.9.4 (2022-10-19)
[UCM-25374](https://task.uralsib.ru/browse/UCM-25374)
* Для 38типа воркфлоу статус WAIT_FOR_DOCS заменён на WAIT_DOCS_FOR_HC

## 2.2.9.3 (2022-10-18)
[UCM-25354](https://task.uralsib.ru/browse/UCM-25354)
* Для 66 операции исправлено заполнение полей employerName и employerInn

## 2.2.9.2 (2022-10-13)
[UCM-25214](https://task.uralsib.ru/browse/UCM-25214)
* Реализована обработка воркфлоу статусов AFS_VISUAL_CONTROL, OPERATOR_APPROVED, CRIF_APPROVE,
 COMPLETED, DECLINED_BY_OPERATOR для 38 типа операции

## 2.2.9.1 (2022-10-11)
* Доработал отправку пуша при переходе операции в declined

## 2.2.9 (2022-10-10)
* Пересборка приложения

## 2.2.8 (2022-10-04)
[UCM-24269](https://task.uralsib.ru/browse/UCM-24269)
* Отправка пуша об отказе при переходе в declined (для сити+ добавлен атрибут в условие определения автоплатежа)

## 2.2.7 (2022-10-04)
[UCM-24269](https://task.uralsib.ru/browse/UCM-24269)
* Отправка пуша об отказе операции при переходе в declined (c2c, sbp, c2b, city+, simpleTransfer)

## 2.2.6 (2022-09-30)
[UCM-22526](https://task.uralsib.ru/browse/UCM-22526)
* добавлено описание статуса операции c2b из ответа omni при переходе в declined

## 2.2.5.4 (2022-10-08)
[UCM-25156](https://task.uralsib.ru/browse/UCM-25156)
* Для операции с типом 38 добавил сохранение атрибута CRIF_RESPONSE.DOCS_SING со значением noAction

## 2.2.5.3 (2022-10-03)
[UCM-24722](https://task.uralsib.ru/browse/UCM-24722)
* Доработал обработку ситуации, когда пришёл некорректный код ПП

## 2.2.5.2 (2022-09-29)
[UCM-24722](https://task.uralsib.ru/browse/UCM-24722)
* Добавил обработку ситуации, когда пришёл некорректный код ПП

## 2.2.5.1 (2022-09-23)
[UCM-22313](https://task.uralsib.ru/browse/UCM-22313)
* Для OPEN_CREDIT_CARD добавлена обработка CCPA 

## 2.2.5 (2022-09-19)
[UCM-24496](https://task.uralsib.ru/browse/UCM-24496)
* WF для операции 102 типа (c2b подключение счета)

## 2.2.4 (2022-09-17)
[UCM-24675](https://task.uralsib.ru/browse/UCM-24675)
* Воркфлоу операции подключения счета к сбппей

## 2.2.3 (2022-09-14)
[UCM-24448](https://task.uralsib.ru/browse/UCM-24448)
* Созданы обработчики статусов worflow DOC_FROM_CRIF до DOCS_SING

## 2.2.2 (2022-09-14)
[UCM-24162](https://task.uralsib.ru/browse/UCM-24162)
* вынес типы ПП из сервиса operation-processing в common

## 2.2.1.1 (2022-09-01)
[UCM-24328](https://task.uralsib.ru/browse/UCM-24328)
* WF смены пин-кода - ставим атрибут карты PINCHANGE = inProcessing

## 2.2.1 (2022-08-29)
[UCM-24085](https://task.uralsib.ru/browse/UCM-24085)
* WF для операции 101 типа (короткий)

## 2.2.0 (2022-08-11)
* Добавлен Liguibase

## 2.1.12.2 (2022-08-17)
[UCM-24062](https://task.uralsib.ru/browse/UCM-24062)
* Добавил для CrifStatus и OrderStatus статус UNKNOWN_UNPROCESSED_STATUS, который будет возвращаться методом valueOfIgnoreCase в случае статуса, который не будет обработан в operation-processing

## 2.1.12.1 (2022-08-15)
[UCM-23906](https://task.uralsib.ru/browse/UCM-23906)
* вкл/откл заполнение поля email для ритейлгейт для 21-23 операций

## 2.1.12 (2022-08-08)
[UCM-22180](https://task.uralsib.ru/browse/UCM-22180)
* Переезд на прямой шлюз с RBS

## 2.1.11.1 (2022-08-10)
[UCM-23888](https://task.uralsib.ru/browse/UCM-23888)
* ЦКК: исправлено заполнение адреса по ЦКК

## 2.1.11 (2022-08-03)
[UCM-23622](https://task.uralsib.ru/browse/UCM-23622)
* ЦКК: исправлен запрос по creditCardOrder в соответствии со спекой

## 2.1.10 (2022-08-02)
[UCM-22441](https://task.uralsib.ru/browse/UCM-22441)
* вынес сервис для отправки откликов в presale PresaleAnswerService
* вынес коды кредитных предложений в енам
* добавил отправку отклика в тибко для операций с типами 39, 63, 66, 67

## 2.1.9 (2022-07-28)
[UCM-23314](https://task.uralsib.ru/browse/UCM-23314)
* убрал функционал, относящийся к опросу ОМНИ для получения статуса заявки 
(отменилось требование автоматического опроса ОМНИ в случае ошибки при получении статуса заявки)
* фикс тестов в соответствии с обновлёнными требованиями

## 2.1.8 (2022-07-28)
[UCM-23314](https://task.uralsib.ru/browse/UCM-23314)
* изменен принцип создания scheduler для кредитов - теперь джоба будет выполняться, даже если была пропущена
* в конфиг добавлен счетчик попыток для кредитных джоб  
* изменен текст для арма при создании джоб 

## 2.1.7 (2022-07-27)
[UCM-22435](https://task.uralsib.ru/browse/UCM-22435)
* добавил новый статус процессинга операций - DECLINED_BY_OPERATOR
* добавил обработку статуса DECLINED_BY_OPERATOR для 39, 63 и 67 типов операции (классы OpenCreditCardProcessor и CrifOperationProcessor)
* добавил компонент для обработки статуса DECLINED_BY_OPERATOR для 66 типа операции + юнит тесты (класс DeclinedByOperator)
* добавил проперти для делэя и таймаута, которые используются для повторного опроса OMNI для получения статуса заявки
* создал енамы для многократно используемых статусов OrderStatus и CrifStatus
* рефакторинг OpenDigitalCreditCardOperationProcessor, CrifOperationProcessor

## 2.1.6 (2022-07-19)
[UCM-23265](https://task.uralsib.ru/browse/UCM-23265)
*  Передача параметра "type" в тибко.

## 2.1.5.4 (2022-07-26)
[UCM-23593](https://task.uralsib.ru/browse/UCM-23593)
* Убран тех. статус для 31 и 32 типов
* Исправлен адрес для подключения продуктов по профилю

## 2.1.5.3 (2022-07-21)
[UCM-22480](https://task.uralsib.ru/browse/UCM-22480)
* воркфлоу по операциям 88, 89 типов

## 2.1.5.2 (2022-07-21)
[UCM-23412](https://task.uralsib.ru/browse/UCM-23412)
* Добавочный номер телефона в заявке к омни

## 2.1.5.1 (2022-07-19)
[UCM-23412](https://task.uralsib.ru/browse/UCM-23412)
* Убраны лишние статусы у WORKFLOW_ID = OPEN_CREDIT_CARD
* Исправлен перевод из статуса CRIF_REQUEST в WAIT_DECISION

## 2.1.5 (2022-07-13)
[UCM-23369](https://task.uralsib.ru/browse/UCM-23369)
* ЦКК: изменены условия задачи

## 2.1.4 (2022-07-12)
[UCM-23369](https://task.uralsib.ru/browse/UCM-23369)
* ЦКК: При получении сообщения от омни, отправляем phaseDesc в status_description

## 2.1.3.2 (2022-07-08)
[UCM-23328](https://task.uralsib.ru/browse/UCM-23328)
* Описание статусов по ЦКК вынесен в конфиг
* Рефактор - переименован пакет component в properties

## 2.1.3.1 (2022-06-30)
[UCM-21194](https://task.uralsib.ru/browse/UCM-21194)
[UCM-22469](https://task.uralsib.ru/browse/UCM-22469)
* добавлено описание статусов
* исправлена логика отправки TIME_OUT в омни по ЦКК
 
## 2.1.3 (2022-06-27)
[UCM-22011](https://task.uralsib.ru/browse/UCM-22011)
* fix

## 2.1.2.2 (2022-06-08)
[UCM-22516](https://task.uralsib.ru/browse/UCM-22516)
* Исправление заполнения номера телефона для 66 операции
* Убарно обращение в omni со статусом fail

## 2.1.2.1 (2022-06-08)
[UCM-22066](https://task.uralsib.ru/browse/UCM-22066)
* для 31, 32, 33, 34, 39, 41, 55, 57, 63, 65, 66 типов совсем убран statusDescription при переводе в ANALYSIS
* для 66 при переводе в DECLINED помечаем как финальный

## 2.1.2 (2022-06-03)
[UCM-22007](https://task.uralsib.ru/browse/UCM-22007)
Новый тип операции 35 - открытие счета РКО
* fix

## 2.1.1 (2022-06-02)
[UCM-22066](https://task.uralsib.ru/browse/UCM-22066)
* Убрал запись тех.статус в STATUS_DESCRIPTION при переводе в анализ из-за ошибки для 31, 32, 33, 34, 39, 41, 55, 57, 63, 65, 66 типов

## 2.1.0.13 (2022-06-03)
* [UCM-22469](https://task.uralsib.ru/browse/UCM-22469)
  * ЦКК: отправка TIMEOUT в омни при статусе DECLINED_BY_BANK_SYSTEM
* [UCM-22466](https://task.uralsib.ru/browse/UCM-22466)
  * ЦКК: Убрал id документов из аттрибута операции, для корректного подписания документов
* [UCM-22516](https://task.uralsib.ru/browse/UCM-22516)
  * ЦКК: Добавлена отправка статусов в омни

## 2.1.0.12 (2022-06-01)
[UCM-21470](https://task.uralsib.ru/browse/UCM-22470)
* ЦКК: Убрал тела документов из аттрибута операции 

## 2.1.0.11 (2022-06-01)
[UCM-21470](https://task.uralsib.ru/browse/UCM-22470)
* ЦКК: Добавлен опрос конечного статуса у омни при DECLINED_BY_BANK_SYSTEM
* В арм добавляем сообщение, что отправлен email

## 2.1.0.10 (2022-06-01)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* ЦКК: если лимит целое число, сохраняем без .0 

## 2.1.0.9 (2022-05-25)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* ЦКК Добавлено ограничение на длину поля при отправке в history

## 2.1.0.8 (2022-05-25)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* Исправлено сохранение аттрибутов при скачивании документов

## 2.1.0.7 (2022-05-25)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* Исправлено логирование для ЦКК - убраны optional при получении результата
* Исправлено время для подписания документов

## 2.1.0.6 (2022-05-25)
[UCM-21128](https://task.uralsib.ru/browse/UCM-21128)
* Для 63 типа исправлен перевод в статус COMPLETED 

## 2.1.0.5 (2022-05-25)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* Фикс отправки имени и фамилии в омни по ЦКК

## 2.1.0.4 (2022-05-24)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* для ЦКК исправлены типы, которые отправляем в омниканальную платформу 

## 2.1.0.3 (2022-05-20)
[UCM-22205](https://task.uralsib.ru/browse/UCM-22205)
* исправлена опечатка

## 2.1.0.2 (2022-05-20)
[UCM-22205](https://task.uralsib.ru/browse/UCM-22205)
* для 39 и 63 операции при получении неизвестного статуса из крифа сохраняем его аттрибут

## 2.1.0.1 (2022-05-19)
[UCM-21128](https://task.uralsib.ru/browse/UCM-21128)
* скорректирована логика для статуса WAIT_DECISION 63 типа операции

## 2.1.0 (2022-05-12)
[UCM-21128](https://task.uralsib.ru/browse/UCM-21128)
* добавлен jaeger
* для 63 типа операции создан новый WORKFLOW = OPEN_CREDIT_CARD

## 2.0.163.2 (2022-04-26)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* Рефактор ЦКК

## 2.0.163.1 (2022-04-25)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* Удалены не используемые статусы по ЦКК
* Доработана обработка в статусе DECLINED_BY_BANK_SYSTEM

## 2.0.163 (2022-04-22)
[UCM-21741](https://task.uralsib.ru/browse/UCM-21741)
* подтверждение подключения пк через колбек

## 2.0.162.11 (2022-04-22)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* Исправлено заполнение email для ЦКК

## 2.0.162.10 (2022-04-22)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* решена проблема одинаковых названий бинов

## 2.0.162.9 (2022-04-22)
[UCM-21765](https://task.uralsib.ru/browse/UCM-21765)
* улучшено логирование в АРМ
* исправлены мелкие ошибки по ЦКК

## 2.0.162.8 (2022-04-22)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
* изменена логика отправки на повторно операции с2b

## 2.0.162.7 (2022-04-21)
[UCM-21649](https://task.uralsib.ru/browse/UCM-21649)
* добавлено поле staffNumber при отправке в омни заявки на выпуск ЦКК
* добавлены параметры для расписаний

## 2.0.162.6 (2022-04-20)
[UCM-21649](https://task.uralsib.ru/browse/UCM-21649)
* ЦКК - улучшение логирования в АРМе

## 2.0.162.5 (2022-04-20)
[UCM-21649](https://task.uralsib.ru/browse/UCM-21649)
* увеличены немного интервалы походов за статусом для тестирования с2б

## 2.0.162.4 (2022-04-20)
[UCM-21649](https://task.uralsib.ru/browse/UCM-21649)
* SendDocumentOmnichannel - исправлен формат для поля DocumentIssueDate

## 2.0.162.3 (2022-04-20)
[UCM-21649](https://task.uralsib.ru/browse/UCM-21649)
* Добавлено поле totalWorkingExperience при отправке в омни

## 2.0.162.2 (2022-04-20)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
* sbpOperId добавлен в атрибут

## 2.0.162.1 (2022-04-19)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
* уменьшены интервалы походов за статусом для тестирования с2б/ . убрать позже

## 2.0.162 (2022-04-19)
[UCM-21285](https://task.uralsib.ru/browse/UCM-21285)
* Добавлен переключатель который позволяет перестать учитывать ЗОД для операций ЧДП/ПДП (41тип)

## 2.0.161 (2022-04-18)
[UCM-21607](https://task.uralsib.ru/browse/UCM-21607)
* Доработка по ЦКК - documentIssuerCode и documentIssueDate заполняем из аттрибутов

## 2.0.160 (2022-04-18)
[UCM-21649](https://task.uralsib.ru/browse/UCM-21649)
* Доработка по ЦКК

## 2.0.159 (2022-04-15)
[UCM-21649](https://task.uralsib.ru/browse/UCM-21649)
* Для ЦКК добавлен статус рабочего при передачи в ОМНИ

## 2.0.158 (2022-04-15)
[UCM-19527](https://task.uralsib.ru/browse/UCM-19527)
* Оповещение омни о подписи документов

## 2.0.157 (2022-04-13)
[UCM-19464](https://task.uralsib.ru/browse/UCM-19464)
* Реализация запроса из Омни документов на подпись

## 2.0.156 (2022-04-12)
[UCM-19571](https://task.uralsib.ru/browse/UCM-19571)
* Получение инфы по одобренной заявке

## 2.0.155 (2022-04-12)
[UCM-20700](https://task.uralsib.ru/browse/UCM-20700)
* Отправка отклика в крифделивери при таймауте

## 2.0.154 (2022-04-04)
[UCM-19647](https://task.uralsib.ru/browse/UCM-19647)
* Обработка получение статуса заявки КК из омни

## 2.0.153 (2022-03-31)
[UCM-19572](https://task.uralsib.ru/browse/UCM-19572)
* Обновление запроса в Омни для заказа ЦКК

## 2.0.152 (2022-03-31)
[UCM-19572](https://task.uralsib.ru/browse/UCM-19572)
* Исправлено отправление заявки ЦКК в омни.
* Доработан тестовый метод

## 2.0.151 (2022-03-30)
[UCM-19572](https://task.uralsib.ru/browse/UCM-19572)
* Исправлена обработка AFS для ЦКК
* Доработана обработка TIME_OUT_SIGN для обычной КК

## 2.0.150 (2022-03-29)
[UCM-19572](https://task.uralsib.ru/browse/UCM-19572)
* Получение статуса заявки по ЦКК из омни

## 2.0.149 (2021-03-28)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Новый флоу операций c2b
## 2.0.148.21.5 (2022-04-25)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  внедрение фичи записи идентификатора сбп операций раньше времени

## 2.0.148.21.4 (2022-04-21)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  внедрение фичи записи идентификатора сбп операций раньше времени

## 2.0.148.21.3 (2022-04-18)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  откат хардкода для пвт 

## 2.0.148.21.2 (2022-04-15)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  хардкод для пвт

## 2.0.148.21.1 (2022-04-15)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  хардкод для пвт

## 2.0.148.21 (2022-04-13)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  смена метода задержки

## 2.0.148.20 (2022-04-13)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  смена метода задержки

## 2.0.148.19 (2022-04-13)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  добавляем паузу сразу

## 2.0.148.18 (2022-04-13)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  убиваем бесконечный повтор

## 2.0.148.17 (2022-04-13)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  Получение статуса с2b из омни вручную. логирование

## 2.0.148.16 (2022-04-13)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  Получение статуса с2b из омни вручную. поправлена отправка в очередь

## 2.0.148.15 (2022-04-13)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  Получение статуса с2b из омни вручную. поправлена отправка в очередь

## 2.0.148.14 (2022-04-12)
[UCM-21566](https://task.uralsib.ru/browse/UCM-21566)
*  Получение статуса с2b из омни вручную

## 2.0.148.13 (2022-04-06)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Исправлены параметры передаваемые в омни

## 2.0.148.12 (2022-04-05)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Исправлены параметры передаваемые в омни

## 2.0.148.11 (2022-04-05)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Исправлены параметры передаваемые в омни

## 2.0.148.10 (2022-04-04)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Исправлеа нпе

## 2.0.148.9 (2022-04-04)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Добавлено поле для отпраки данных по c2b

## 2.0.148.8 (2022-03-31)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Использована другая дто в работе метода отправки перевода c2b

## 2.0.148.7 (2022-03-31)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Изменен контракт метода перевода c2b

## 2.0.148.6 (2022-03-31)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Изменен вызов реста получения продукта во флоу c2b

## 2.0.148.5 (2022-03-31)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Изменен вызов реста получения продукта во флоу c2b

## 2.0.148.4 (2022-03-30)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Исправлен параметр в запросе клиента во флоу c2b

## 2.0.148.3 (2022-03-30)
[UCM-20562](https://task.uralsib.ru/browse/UCM-20562)
*  Новый флоу операций c2b

## 2.0.148.2(2022-03-29)
[UCM-21261](https://task.uralsib.ru/browse/UCM-21261)
* Исправлена ошибка формата у documentDate, при отправке заявки на выпуск цифровой карты

## 2.0.148.1(2022-03-08)
[UCM-19681](https://task.uralsib.ru/browse/UCM-19681)
* убрана логика 19681 задачи

## 2.0.148(2022-03-07)
[UCM-19681](https://task.uralsib.ru/browse/UCM-19681)
* фикс нпе

## 2.0.147(2022-03-03)
[UCM-19681](https://task.uralsib.ru/browse/UCM-19681)
* Получение отклика от крифделивери о готовности документов

## 2.0.146 (2022-03-01)
[UCM-20738](https://task.uralsib.ru/browse/UCM-20738)
* Исправлены опечатки и описание статуса DECLINED для вывода в арм

## 2.0.145 (2022-02-21)
[UCM-19432](https://task.uralsib.ru/browse/UCM-19432)
* Создание нового типа операции 66 для заказа цифровой КК

## 2.0.144.2 (2022-01-28)
[UCM-20279](https://task.uralsib.ru/browse/UCM-20279)
* Исправили отклики в tibco. Не отправляем их для typeCode=CC

## 2.0.144.1 (2022-01-26)
[UCM-20221](https://task.uralsib.ru/browse/UCM-20221)
* Добавлена отправка в тибко - отклик с кодом APL

## 2.0.144 (2022-01-21)
[UCM-17481](https://task.uralsib.ru/browse/UCM-17481)
* найден тест, потерявшего просьба позвонить в 02!
* Получение документов по кредиту в pdf вместо html

## 2.0.143.2 (2022-01-18)
[UCM-20111](https://task.uralsib.ru/browse/UCM-20111)
*  спрятан тест

## 2.0.143.1 (2022-01-18)
[UCM-20111](https://task.uralsib.ru/browse/UCM-20111)
*  Убрать точку из RCV pam для сбп операций

## 2.0.143 (2021-12-16)
[UCM-15092](https://task.uralsib.ru/browse/UCM-15092)
* Добавлены шаги AFS для крифа и выпуска карт

## 2.0.142.1 (2021-11-18)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Хотфикс на допутимые типы операций сбп

## 2.0.142 (2021-11-14)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Добавление параметра для холдирования, так как ритейл не обрабатывает дефолтные значения сбп

## 2.0.141 (2021-11-10)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Изменение логики проверки смены банка или счета для митуми

## 2.0.140 (2021-11-10)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Обертка получения статуса в трай

## 2.0.139 (2021-11-10)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Получение статуса по соглашению от ритейл

## 2.0.138 (2021-11-09)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* дополнительный параметр для поиска документа в ритейл

## 2.0.137 (2021-11-06)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* исправление нпе

## 2.0.136 (2021-11-06)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Изменение условия проверки наличия изменений

## 2.0.135 (2021-11-06)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Уменьшено время ожидания ответа в ритейле

## 2.0.134 (2021-11-06)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Добавлено логирование, изменение счета на идентификтаор продукта

## 2.0.133 (2021-11-05)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Выборка поиска операции сбп включат 82й тип

## 2.0.132 (2021-11-05)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Тестово уменьшен таймаут ожидания сбп

## 2.0.131 (2021-11-05)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Тестово уменьшен таймаут ожидания сбп

## 2.0.130 (2021-11-05)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Тестово уменьшен таймаут ожидания сбп

## 2.0.129 (2021-11-05)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Исправлено назначение статуса операции

## 2.0.128 (2021-11-05)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Исправлена нпе

## 2.0.127 (2021-11-02)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Добавление номера документа

## 2.0.126 (2021-11-02)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Изменение типа поля

## 2.0.125 (2021-11-02)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Процессинг операции изменения банков и счета безакцепта

## 2.0.124 (2021-11-01)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Изменение процессинга сбп под изменение холдирования

## 2.0.123 (2021-10-27)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Изменение статуса операции после поиска перевода в ритейле

## 2.0.122 (2021-10-27)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Изменение статуса операции после отправки отложенного сообщения

## 2.0.121 (2021-10-15)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Из процессинга митуми убрали обращение к тибко, вынесли его в сбп

## 2.0.120 (2021-10-15)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Доработки me2me

## 2.0.119 (2021-10-01)
[UCM-17678](https://task.uralsib.ru/browse/UCM-17678)
* Интеграция Системы противодействия мошенничеству (AFS) с СБП по Стандарту ОПКЦ...
* удалил заглушку verify

## 2.0.118 (2021-10-01)
[UCM-17874](https://task.uralsib.ru/browse/UCM-17874)
* Доработки me2me

## 2.0.117 (2021-09-17)
[UCM-16424](https://task.uralsib.ru/browse/UCM-16424)
* Миграция SOA на TS urlencode

## 2.0.116 (2021-09-16)
[UCM-15092](https://task.uralsib.ru/browse/UCM-15092)
* Внедрение статуса OPERATOR_APPROVED

## 2.0.115 (2021-09-15)
[UCM-17532](https://task.uralsib.ru/browse/UCM-17532)
* Новый воркфлоу- запрос денег с другого банка при переводе себе по сбп

## 2.0.114 (2021-09-13)
[UCM-17678](https://task.uralsib.ru/browse/UCM-17678)
* Интеграция Системы противодействия мошенничеству (AFS) с СБП по Стандарту ОПКЦ

## 2.0.113 (2021-08-27)
[UCM-16928](https://task.uralsib.ru/browse/UCM-16928)
* Интеграция Системы противодействия мошенничеству (AFS) с СБП по Стандарту ОПКЦ

## 2.0.112 (2021-08-10)
[UCM-16482](https://task.uralsib.ru/browse/UCM-16482)
* Обработка колбека pay control и создание нового шага во flow операций.

## 2.0.111.3 (2021-08-23)
[UCM-16966](https://task.uralsib.ru/browse/16966)
* добавил случайный постфикс для создания расписания 

## 2.0.111.2 (2021-08-12)
[UCM-17125](https://task.uralsib.ru/browse/UCM-17125)
* Отрицательное время в ttl operation-processing

## 2.0.111.1 (2021-08-12)
[UCM-16424](https://task.uralsib.ru/browse/UCM-16424)
* Миграция SOA на TS Передавать в QUERY параметрах source=DBO

## 2.0.111 (2021-08-06)
[UCM-16424](https://task.uralsib.ru/browse/UCM-16424)
* Миграция SOA на TS Передавать в QUERY параметрах SOURCE_APP=DBO

## 2.0.110 (2021-08-06)
[UCM-17062](https://task.uralsib.ru/browse/UCM-17062)
* Добавлена отправка уведомления в омниканальную платформу

## 2.0.109 (2021-07-29)
[UCM-16613](https://task.uralsib.ru/browse/UCM-16613)
* Исправлены имена параметров

## 2.0.108 (2021-07-28)
[UCM-16212](https://task.uralsib.ru/browse/UCM-16212)
* Удаление неиспользуемых soap клиентов

## 2.0.107 (2021-07-28)
[UCM-16424](https://task.uralsib.ru/browse/UCM-16424)
* Создан процесс CARD_ISSUE_DIGITAL на основе CARD_ISSUE.
* Реализована отправка данных в оминканальну платформу на api - /cards/debit/new

## 2.0.106 (2021-07-13)
[UCM-16424](https://task.uralsib.ru/browse/UCM-16424)
* Мграция SOA на TS. Передавать в QUERY параметрах MsgId

## 2.0.105 (2021-07-08)
[UCM-16296](https://task.uralsib.ru/browse/UCM-16296)
* Удалены deprecated методы
* Проперти перенесены в ConfigurationProperties

## 2.0.104 (2021-06-29)
[UCM-15856](https://task.uralsib.ru/browse/UCM-15856)
* Удалены лишние statusDescription в процессе WU
так как они отображаются в истории "PROCESS > CHECK_RESULT"

## 2.0.103 (2021-06-25)
[UCM-16031](https://task.uralsib.ru/browse/UCM-16031)
* Отображение ошибки от CrifDelivery.

## 2.0.102 (2021-06-24)
[UCM-15025](https://task.uralsib.ru/browse/UCM-15025)
* Заполнение GROUNDPAYMENT с датой в уфимском часовом поясе

## 2.0.101 (2021-06-21)
[UCM-16031](https://task.uralsib.ru/browse/UCM-16031)
* Отображение ошибки от CrifDelivery.

## 2.0.100 (2021-06-21)
[UCM-12310](https://task.uralsib.ru/browse/UCM-12310)
* RF Переведено общение с rtl SOAP на мс retailgate.

## 2.0.99 (2021-06-18)
[UCM-12310](https://task.uralsib.ru/browse/UCM-12310)
* Переведено общение с rtl SOAP на мс retailgate.

## 2.0.98 (2021-06-07)
[UCM-15025](https://task.uralsib.ru/browse/UCM-15025)
* DOCUMENTDATE в SimpleTransferOperationProcessor отправляется по уфимскому времени.

## 2.0.97.1 (2021-06-29)
[UCM-16207](https://task.uralsib.ru/browse/UCM-16207)
* Хотфикс, дата ситиплюс операций отправляется в ритейл в уфимском часовом поясе 

## 2.0.97 (2021-06-03)
[UCM-14920](https://task.uralsib.ru/browse/UCM-14920)
* Сохранение суммы для ПДП

## 2.0.96 (2021-05-26)
[UCM-14760](https://task.uralsib.ru/browse/UCM-14760)
Добавлен ответ ритейла в логирование истории для статуса WAIT_RTL_PERFORM

## 2.0.95 (2021-05-06)
[UCM-6734](https://task.uralsib.ru/browse/UCM-6734)
AFS добавлены события в журнал

## 2.0.94 (2021-04-26)
[UCM-14658](https://task.uralsib.ru/browse/UCM-14658)
Доработан sbp процесc, после успешного шага SBP_CONFIRM 
операция не попадала в RTL_UNHOLD

## 2.0.93 (2021-04-21)
[UCM-14122](https://task.uralsib.ru/browse/UCM-14122)
Поправлено создание HistoryEvent в одном методе и обогощено

## 2.0.92.3 (2021-05-24)
[UCM-15378](https://task.uralsib.ru/browse/UCM-15378)
* bag_fix

## 2.0.92.2 (2021-05-21)
[UCM-15378](https://task.uralsib.ru/browse/UCM-15378)
* изменение сохронения атребута "CRIF_RESPONSE.DOCS_SING"

## 2.0.92.1 (2021-04-26)
[UCM-13027](https://task.uralsib.ru/browse/UCM-13027)
fix изменен форматтер локальной даты, на симплформаттере локал дата падала

## 2.0.92 (2021-04-21)
[UCM-11861](https://task.uralsib.ru/browse/UCM-11861)
fix Некорректный статус в имейле после после подключения услуги смс

## 2.0.91 (2021-04-19)
[UCM-14450](https://task.uralsib.ru/browse/UCM-14450)
* Внесены исправления по алгоритму изменения отправки перевода Western Union

## 2.0.90 (2021-04-19)
[UCM-14347](https://task.uralsib.ru/browse/UCM-14347)
* Внесены оптимизационные правки по алгоритму отправки перевода Western Union

## 2.0.89 (2021-04-16)
[UCM-14347](https://task.uralsib.ru/browse/UCM-14347)
* Добавлены новые условия алгоритма в WesternUnion workflow

## 2.0.88 (2021-04-15)
[UCM-14346](https://task.uralsib.ru/browse/UCM-14346)
* Исправлено в AFS Splunk 
  не поступают статусы "COMPLETED" по документам СБП.
  
## 2.0.87 (2021-04-15)
[UCM-12758](https://task.uralsib.ru/browse/UCM-12758)
* В workflow SBP вызов метода getSbpPaymentStatus  обернут в try catch 
  в случает возникновения ошибки со стороны tibco
  отправлять трейс ошибки в history

## 2.0.86 (2021-04-08)
* Добавлены перехваты исключений от Сити+ в WesternUnion workflow

## 2.0.85 (2021-04-08)
[UCM-12757](https://task.uralsib.ru/browse/UCM-12757)
* выводить exception в журнал operation-processing при обращениях к СИТИ+  

## 2.0.84 (2021-04-06)
[UCM-14007](https://task.uralsib.ru/browse/UCM-14007)
* Исправлено использование deprecated поля в Western Union wf 

## 2.0.83 (2021-04-06)
[UCM-13802](https://task.uralsib.ru/browse/UCM-13802)
* rework

## 2.0.82 (2021-04-07)
[UCM-13907](https://task.uralsib.ru/browse/UCM-13907)
* Исправлен возникающий Exception в workflow отправки переводы WesternUnion (WesternUnionSendProcessor.class)

## 2.0.81 (2021-04-06)
[UCM-13802](https://task.uralsib.ru/browse/UCM-13802)
* Новый статус для WORKFLOW_STATUS

## 2.0.80 (2021-04-05)
[UCM-12285](https://task.uralsib.ru/browse/UCM-12285)
* Добавлены изменения workflow WesternUnion (WesternUnionProcessor.class)

## 2.0.79 (2021-03-24)
[UCM-12285](https://task.uralsib.ru/browse/UCM-12285)
* Исправлен workflow для изменения перевода WesternUnion

## 2.0.78 (2021-03-24)
[UCM-13058](https://task.uralsib.ru/browse/UCM-13058)
* Доработка ЧДП при ЗОД

## 2.0.77 (2021-03-16)
[UCM-12285](https://task.uralsib.ru/browse/UCM-12285)
* Добавлены изменения workflow для изменения перевода WesternUnion (WesternUnionProcessor.class)

## 2.0.76 (2021-03-16)
* UCM-11519: WorkFlow WesternUnion

## 2.0.75 (2021-03-16)
[UCM-13027](https://task.uralsib.ru/browse/UCM-13027)
* Дата operDate  в ритейл передается в уфимском часовом поясе

## 2.0.74.7 (2021-04-22)
[UCM-14583](https://task.uralsib.ru/browse/UCM-14583)
* в случае возникновения ошибки при запросе статуса из рбс,
процесс откладывается и повторяется через некоторое время
ps: operation-processing.p2p добавить проперти в config

## 2.0.74.6 (2021-04-16)
[UCM-14384](https://task.uralsib.ru/browse/UCM-14384)
* заполняем у SIMPLE_TRANSFER номер документа для ритейла из операции UiOperationId даже если был не нал

## 2.0.74.5 (2021-04-16)
[[RESTAPI] Документы уходят в нештатку](https://task.uralsib.ru/browse/UCM-14348)
* прерывание обработки документа на этапе получения статуса из Ритейл, если документ был отправлен в отказ оператором

## 2.0.74.4 (2021-04-16)
[UCM-14384](https://task.uralsib.ru/browse/UCM-14384)
* заполняем у SIMPLE_TRANSFER номер документа для ритейла из операции UiOperationId

## 2.0.74.3 (2021-04-16)
[UCM-14157](https://task.uralsib.ru/browse/UCM-14157)
* Workflow card2card разделен на осуществелние перевода и запрос статуса 

## 2.0.74.2 (2021-04-14)
[Наряд №3389343 СБП Ошибка холдирования средств](https://sdportal/workorder/3389343)
* при таймауте холдирования добавлено расхолдирование средств

## 2.0.74.1 (2021-04-02)
[UCM-11253](https://task.uralsib.ru/browse/UCM-11253)
* Добавлено подробное логирование ошибок

## 2.0.74 (2021-03-11)
[UCM-11253](https://task.uralsib.ru/browse/UCM-11253)
* При отказе операции заполнять причину отказа в поле statusDescription объекта операции

## 2.0.73 (2021-03-10)
[UCM-12752](https://task.uralsib.ru/browse/UCM-12752)
* при подписании timeout анкеты на кредит дергается /internal/crif-document-packages/{operationId}

## 2.0.72 (2021-03-03)
[UCM-11893](https://task.uralsib.ru/browse/UCM-11893)
Отдельные конфиги количества потоков для очереди  "operation-processing-queue"

## 2.0.71 (2021-02-24)
[UCM-10119](https://task.uralsib.ru/browse/UCM-1019)
Обработчик статуса CONFIRMPAY  и корректировка самостоятельного получения статуса

## 2.0.70 (2021-02-22)
[UCM-11861](https://task.uralsib.ru/browse/UCM-11861)
Некорректный статус в имейле после после подключения услуги смс

## 2.0.69 (2021-02-21)
[UCM-9736](https://task.uralsib.ru/browse/UCM-9736)
* добавил 0 по умолчанию если сумма на пдп не указана

## 2.0.68.3 (2021-03-04)
[UCM-12563](https://task.uralsib.ru/browse/UCM-12563)
* исправил запрос в credit-manager

## 2.0.68.2 (2021-02-26)
[UCM-11483](https://task.uralsib.ru/browse/UCM-11483) BUGFIX FROM STABLE
Если при переводе счет закрыт то стату операции = declined

## 2.0.68.1 (2021-02-24)
[UCM-12012](https://task.uralsib.ru/browse/UCM-12012)
* CreditRepayment добавил 0 по умолчанию если сумма погашения не указана

## 2.0.68 (2021-02-17)
###### @author SandulyakSV
[UCM-11692](https://task.uralsib.ru/browse/UCM-11692)
* Добавление main_package_id для дозаказываемых карт

## 2.0.67 (2021-02-09)
###### @author SandulyakSV
[UCM-11075](https://task.uralsib.ru/browse/UCM-11075)
* Добавление ASN для открываемых карт-счетов

## 2.0.66 (2021-02-05)
###### @author SandulyakSV
[UCM-10936](https://task.uralsib.ru/browse/UCM-10936)
* Правка Client Id для отправки CPU в IBSO Retail

## 2.0.65 (2020-12-22)
[UCM-10697](https://task.uralsib.ru/browse/UCM-10697)
* Поставлена прогрессивная задержка при обработке документа в статусе 3

## 2.0.64 (2021-02-04)
###### @author LukmanovII
[UCM-10378](https://task.uralsib.ru/browse/UCM-10378)
### Change 1
* fix bug url soa adapter

## 2.0.63 (2021-02-04)
###### @author LukmanovII
[UCM-10378](https://task.uralsib.ru/browse/UCM-10378)
### Change 1
* расширены логи

## 2.0.63 (2021-02-03)
###### @author LukmanovII
[UCM-10726](https://task.uralsib.ru/browse/UCM-10726)
### Change 1
* Добавлены новые параметры для открытия ПУ


## 2.0.62 (2021-02-03)
###### @author LukmanovII
[UCM-10378](https://task.uralsib.ru/browse/UCM-10378)
### Change 1
*  добавлен этап проверки afs для разблокировки карты

## 2.0.61 (2020-12-28)
[UCM-9148](https://task.uralsib.ru/browse/UCM-9148)
* Не регистрируются события OPERATION_PROCESSING$OPERATION$SBP

## 2.0.60 (2020-12-22)
[UCM-9736](https://task.uralsib.ru/browse/UCM-9736)
* Проверить мок крифа

## 2.0.59.1 (2021-02-01)
[UCM-10638](https://task.uralsib.ru/browse/UCM-10638)

## 2.0.59 (2020-12-21)
[UCM-9736](https://task.uralsib.ru/browse/UCM-9736)
* Проверить мок крифа

## 2.0.58 (2021-01-19)
[Наряд №3276234 Реализация: 937767 Рефакторинг часовые пояса)](https://task.uralsib.ru/browse/UCM-9370)
* добавление BROWSER для логирования для afs

## 2.0.57 (2021-01-19
[Наряд №3276234 Реализация: 937767 Рефакторинг часовые пояса)](https://task.uralsib.ru/browse/UCM-9507)
* добавлена аннотация @UralsibTimeZoneFix

## 2.0.56 (2021-01-18)
[Доработки СБП (мс retailgate, operation-processing дбо3 и дбо4)](https://task.uralsib.ru/browse/UCM-9588)
* Добавлен sbpOperId в holdAmount

## 2.0.55 (2020-12-30)
[UCM-9300](https://task.uralsib.ru/browse/UCM-9300)
[UCM-9375](https://task.uralsib.ru/browse/UCM-9375)
* добавление атрибутов для отправки afs

## 2.0.54 (2020-12-29)
[UCM-9373](https://task.uralsib.ru/browse/UCM-9373)
* Правка разбора ответа при закрытии депозита

## 2.0.53 (2020-12-29)
[UCM-9325](https://task.uralsib.ru/browse/UCM-9325)
* добавление атрибутов для отправки afs

## 2.0.51.1 (2021-01-15)
[UCM-9587](https://task.uralsib.ru/browse/UCM-9587)
* Изменет статус операции при отказе РБС с ANALYSIS на DECLINED

## 2.0.51 (2020-12-22)
[UCM-9102](https://task.uralsib.ru/browse/UCM-9102)
* добавил логирование sessionId и ip для логироавния afs в ADVANCED_REPAYMENT и CREDIT_APP

## 2.0.51 (2020-12-22)
[UCM-9074](https://task.uralsib.ru/browse/UCM-9074)
[UCM-9079](https://task.uralsib.ru/browse/UCM-9079)
* добавление sessionId и ip для логирования для afs

## 2.0.50 (2020-12-22)
[UCM-9130](https://task.uralsib.ru/browse/UCM-9130)
* [RESTAPI] Откладывание проверки статуса ритейла после 10-го раза

## 2.0.49 (2020-12-21)
[UCM-7448](https://task.uralsib.ru/projects/UCM/issues/UCM-7448)
Открытие ПУ workflow

## 2.0.48.2 (2021-01-25)
[Доработки СБП ( мс retailgate, operation-processing дбо3 и дбо4)](https://task.uralsib.ru/browse/UCM-9588)
* hotfix для прода holdAmount +sbpOperId

## 2.0.48.1(2020-12-21)
* изменение типа атрибута sessionId

## 2.0.48(2020-12-21)
[UCM-8597](https://task.uralsib.ru/browse/UCM-8983)
[UCM-7558](https://task.uralsib.ru/browse/UCM-8971)
* Добавлен метод для обезки длины атрибутов, которые передаются в afs (длина не
должна превышать 200 символов)
* добавлены атрибуты sbpId, receiverTelephone

## 2.0.47(2020-16-10)
[UCM-8853](https://task.uralsib.ru/browse/UCM-8853)
* Исправление NPE в Close Deposit Workflow

## 2.0.46.3(2020-12-18)
[UCM-8306](https://task.uralsib.ru/browse/UCM-8306)
* Действия после авторизации в части Loan. Доработка /messages/alerts
* REWORK

## 2.0.45.3(2020-12-17)
[UCM-8597](https://task.uralsib.ru/browse/UCM-8597)
[UCM-7558](https://task.uralsib.ru/browse/UCM-8558)
* Добавлен атрибут sessionId

## 2.0.45(2020-12-10)
[UCM-8306](https://task.uralsib.ru/browse/UCM-8306)
* Действия после авторизации в части Loan. Доработка /messages/alerts

## 2.0.44.4(2020-12-22)
[[Middle] Ошибка парсинга даты в ответе от Ритейл](https://task.uralsib.ru/browse/UCM-9096)
* добавлена проверка на null при конвертации даты в строку при закрытии депозита

## 2.0.44.3(2020-12-11)
[Транзакции prod [ 7 OWN_FUNDS_CONVERSION ]Конвертация между своими счетами](https://task.uralsib.ru/browse/UCM-8467)
* исправлена конвертация атрибутов в boolean

## 2.0.44.2 (2020-12-10)
[Документ №44952970 (Перевод физическому или юридическому лицу) - в статусе «Разбор нештатной ситуации»](https://task.uralsib.ru/browse/UCM-8250)
* для настройки кол-ва попыток проверки статуса переводов в Ритейл добавлена переменная (Dictionary): CATEGORY = "OPERATION_PROCESSING", CODE = "TRANSFER.MAX_STATUS_COUNT"
* для настройки кол-ва попыток проверки статуса открытия/закрытия депозитов в Ритейл добавлена переменная(Dictionary): CATEGORY = "OPERATION_PROCESSING", CODE = "DEPOSIT.MAX_STATUS_COUNT"

## 2.0.44.1 (2020-12-04)
[UCM-8115](https://task.uralsib.ru/browse/UCM-8115)
[UCM-8232](https://task.uralsib.ru/browse/UCM-8232)

### Fixed (1 fix)
* Правка логирования afs. Исправил запись в EventTypeCode: OPERATION-PROCESSING$OPERATION -> OPERATION_PROCESSING$OPERATION

## 2.0.44 (2020-12-01)
[UCM-6734](https://task.uralsib.ru/projects/UCM/issues/UCM-6734)

### Fixed (1 fix)
* Правка логирования afs

## 2.0.43 (2020-12-01)
[UCM-6734](https://task.uralsib.ru/projects/UCM/issues/UCM-6734)

### Added (1 change)
* Был добавлен параметр `afs.verify-debug`
* **ВАЖНО** добавить в конфигурационный файл пром стенда параметр `operation-processing.afs.verify-debug` со значением `false`

## 2.0.42 (2020-11-27)
[[Оплата услуг] В ПП на оплату услуг СИТИ+ в назначении платежа отсутствует информация за что оплата](https://task.uralsib.ru/browse/UCM-7257)

## 2.0.41 (2020-11-27)
[UCM-7596](https://task.uralsib.ru/browse/UCM-7596)

### Fixed (1 fix)
* Исправлена десериализация объекта `AfsOperationProcessingItem`

## 2.0.40 (2020-11-27)
[UCM-7596](https://task.uralsib.ru/browse/UCM-7596)

### Added (1 change)
* Добавил проверку времени жизни сообщения в очереди Afs. Метод `receivefromAfsQueue`

### Changed (1 change)
* Поправил текстовки логирования afs.

## 2.0.39.1 (2020-12-02)
[[Rest] Открытие счета в процессе конверсии. Отсутствие Соглашения](https://task.uralsib.ru/browse/UCM-8305)
* при конверсии с автооткрытием счета убрана проверка Соглашения 'Автоматическое ПОДКЛЮЧЕНИЕ вновь открываемых счетов'

## 2.0.39 (2020-11-26)
[UCM-7596](https://task.uralsib.ru/browse/UCM-7596)

### Added (1 change)
* Добавлен exchange для afs очередей

### Changed (1 change)
* Изменены очереди для работы с afs

## 2.0.38 (2020-11-12)
bug fix перевыпск дебетовой карты

### Change (1 change)
* добавлена причина перевыпска карты класс CardIssueProcessor метод getDocReopenDebitCard(...)

## 2.0.37(2020-11-12)
Доработка workflow перевыпуск карты / выпуск доп. карты

### Change (1 change)
* доработан workflow CardIssueProcessor, добавлена реализация бинов getDocReopenDebitCard/getDocOpenAdditionDebitCard
 
## 2.0.36 (2020-10-27)
bug fix открытие дебетовой карты
### Change (1 change)
* поправлена логика добавления COBRAND, PAY_SYS, CARD_CATEGORY

## 2.0.35.1 (2020-11-17)
[Черновик перевода ФЛ сложно привязать к клиенту и сессии](https://task.uralsib.ru/browse/UCM-7370)
* для AFS в переводы и открытие/закрытие депозита добавлены id сессии, клиента, профиля, ip-адрес

## 2.0.35.0 (2020-10-27)
[UCM-7158 В релизе 3 некорректная версия operation-rocessing](https://task.uralsib.ru/browse/UCM-7158)
### Fixed
* получение списков PAY_SYS, COBRAND, CARD_CATEGORY

## 2.0.35 (2020-10-27)
[Увеличение количества попыток получения статуса обработки документа в Ритейл](https://task.uralsib.ru/browse/UCM-6171)

## 2.0.34 (2020-10-27)
[UCM-6734](https://task.uralsib.ru/browse/UCM-6734)

### Fixed (1 fix)
* Исправлен пустой trigger при создании job'а 

## 2.0.33 (2020-10-26)
[Наряд №3145664 UCM-5468](https://sdportal/workorder/3145664)

### Added (4 change)
* Добавлено логирование для AFS CreditRepayment
* Добавлено логирование для AFS P2POperationProcessor
* Добавлено логирование для AFS CrifOperationProcessor
* Добавлено логирование для AFS CityplusOperationProcessor


## 2.0.32 (2020-10-26)
[UCM-6636](https://task.uralsib.ru/browse/UCM-6636)
Опереция не доходила до отказа самостоятельно


## 2.0.31 (2020-10-24)

### Fixed (1 fix)
* Исправлен баг из-за которого отправка email ломала обработку afs_visual_control

## 2.0.30 (2020-10-23)
[АРМ Обработки документа](https://task.uralsib.ru/browse/UCM-6578)
[Наряд №3178484 UCM-6578](https://sdportal/workorder/3178484)
* в workflow добавлен новый статус OPERATOR_APPROVED

## 2.0.29 (2020-10-22)
* Фикс отправки email для AFS_VERIFY x2

## 2.0.28 (2020-10-22)
* Фикс отправки email для AFS_VERIFY

## 2.0.27 (2020-10-19)
[Наряд №3171764 Реализация: 935862 логирование событий (+ draft)](https://sdportal/workorder/3171764)
* Логирование АFS для переводов и открытия/закрытия счета, добавлено логирование для START

## 2.0.26 (2020-10-15)
* fix afs log 2

## 2.0.25 (2020-10-15)
* fix afs log

## 2.0.24 (2020-10-15)
* Добавлено логирование url afs

## 2.0.23 (2020-10-13)
* Добавлен новый статус проверки AFS `AfsStatus.FAILED` для ситуаций когда AFS не смог определить статус операции

## 2.0.22 (2020-10-12)
[UCM-6140](https://task.uralsib.ru/browse/UCM-6140) Игнорирование ошибок AFS по операциям СБП

## 2.0.21 (2020-10-09)
[UCM-5655](https://task.uralsib.ru/browse/UCM-5655)

[Наряд №3149950 Реализация доп требований](https://sdportal/workorder/3149950)

[Задача Проекта №927031 [П3] Модуль выставления счетов](https://sdportal/mprojects/927031)

### Added (1 change)
* Добавлена обработка ErrorCode.VALIDATION_ERROR при запросах управления АП !69

## 2.0.20 (2020-10-08)

### Changed (1 change)
* Установлен ZoneId при логировании событий АП !68

## 2.0.19 (2020-10-08)

### Fixed (1 change)
* В функционале АП, при обработке ошибки из City+, текст ошибки брался из несуществующего поля !64

## 2.0.18 (2020-10-06)
[Наряд №3145649 Реализация: 935862 логирование событий AFS](https://sdportal/workorder/3145649)
### Added
Добавлены типы событий логирования в HISTORY_EVENT для AFS: 
* OPERATION-PROCESSING$OPERATION$BETWEEN_OWN_ACCOUNTS	Перевод между своими счетами 
* OPERATION-PROCESSING$OPERATION$RUB_TO_ANY_PERSON	Перевод физическому или юридическому лицу 
* OPERATION-PROCESSING$OPERATION$RUB_TO_BUDGET	Перевод по бюджетным реквизитам 
* OPERATION-PROCESSING$OPERATION$CUR_TO_ANY_PERSON_WITHIN_BANK	Перевод валюты по сети филиалов Банка 
* OPERATION-PROCESSING$OPERATION$CUR_TO_ANY_PERSON_IN_FOREIGN_BANK	Перевод валюты по системе международных переводов 
* OPERATION-PROCESSING$OPERATION$OWN_FUNDS_CONVERSION	Конвертация между своими счетами 
* OPERATION-PROCESSING$OPERATION$OPENING_DEPOSIT Открытие депозита 
* OPERATION-PROCESSING$OPERATION$CLOSING_DEPOSIT Закрытие депозита

## 2.0.17 (2020-10-07)
##### Рефактор workflow выпуск дебетовой карты
#### [Наряд Анкеты - Открытие дебетовой карты](https://sdportal/workorder/3138875)

#### Изменены:
* ##### Класс CardIssueProcessor

## 2.0.17 (2020-10-06)
[Наряд №3149528 Реализация: 933984 [П4] АРМ Обработки документов - CR (oper-proc)](https://sdportal/workorder/3149528)

[Задача Проекта №933984 [П4] АРМ Обработки документов - CR](https://sdportal/mprojects/933984)

### Added (1 change)
* Added HttpClientConfig

### Changed (2 changes)
* Параметр времени ожидания afs проверки перенесен в operationType `afsReadTimeout`
* Рефакторинг workflow метода `receiveFromAfsQueue`

### Fixed (1 fix)
* Исправлена ошибка 404 при отправке e-mail `/send` -> `/internal/send` в MailServerClient.java

### Deprecated (1 change)
* RestTemplateConfig is deprecated. Подгрузка сертифката перенесена в HttpClientConfig

## 2.0.16 (2020-10-05)
[Уладение лишнего импорта](https://task.uralsib.ru/browse/UCM-4892)

## 2.0.15 (2020-10-02)
[Добавление нового аттрибута financeCode](https://task.uralsib.ru/browse/UCM-4892)

## 2.0.14 (28-09-2020)
[Добавление статуса в workflow process](https://task.uralsib.ru/browse/UCM-5558)

## 2.0.13 (23-09-2020)
[Operation-processing вынос jks во внешнюю файловую ситсему](https://task.uralsib.ru/browse/UCM-5324)

### 2.0.11 (2020-09-09)

[Наряд №3106194 Реализация (928491 [П1] Интеграция с AFS Splunk (Он-лайн контроль)](https://sdportal/workorder/3106194)

[Задача Проекта №928491 [П1] Интеграция с AFS Splunk (Он-лайн контроль)](https://sdportal/mprojects/928491)

### Added (3 changes)
* Метод проверки операции в afs `/internal/operation/{operationId}/afs-check`
* В BasicProcessor добавлены методы afs
* Во все workflow добавлены методы afs

### Deprecated (1 change)
* Метод `GET /internal/afs/operation/{operationId}/check`

## 2.0.9 (2020-08-31)

### Changed 
* CreditRepayment

## 2.0.5 (2020-08-14)
[Наряд №3082165 Реализация: 927996 WF](https://sdportal/workorder/3082165)

[Задача Проекта №927996 [П4] Кредиты - действие, конопка погасить, досрочное погашение](https://sdportal/mprojects/927996)

### Added 
* CreditRepayment

### Changed
* RetailClient

## 2.0.3 (2020-07-15)
[Наряд №3035032 Реализация: 927503 АП](https://sdportal/workorder/3035032)

[Задача Проекта №927503 [П2] Шаблоны и автоплатежи](https://sdportal/mprojects/927503)

### Added 
* CreateAutopayOperationProcessor
* UpdateAutopayOperationProcessor
* DeleteAutopayOperationProcessor

### Changed
* AutopayOperationProcessor
* MvsClient
