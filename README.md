## ТЗ
  _Мобильное (Андроид, Айфон) приложение для клиентов сети автомоек. + WEB для директора, бухгалтера, кассира, мойщика._
  
## Требования
+ Пользователи:
   1. Директор
   2. Бухгалтер
   3. Клиент
   4. Оператор (касса)
   5. Мойщик
- Для Клиентов:
  - Регистрация (Авторизация):
      - Номер
      - Логин
      - Пароль
      - Модель тс
  - Выбор точки на карте.
  - Выбор бокса, времени, услуги.
  - Оплата (Способ оплаты).
  - Возможность отмены услуги и возврата платежа за 30 минут до назначенной услуги.
  - Обратная связь по качеству услуги.\
  **_Дополнительно:_**
  - Оповещения.
  - Загруженность мойки.
- Для Директора:
  - Авторизация.
  - Возможность выбора точки.
  - Рейтинг посещаемости, окупаемости точек + Рейтинг/анти-рейтинг клиентов (кол-во отменённых услуг, негативные отзывы).
  - Статистика по работе мойщиков.
  - Просмотр и редактирование списка VIP-клиентов.
  - Просмотр доступных тарифов и акций.
  - Просмотр загруженности боксов + прогноз.
- Для бухгалтера:
  - Авторизация.
  - Возможность выбора точки на карте.
  - Рейтинг окупаемости точек.
  - Просмотр и редактирование списка VIP-клиентов.
  - Просмотр и редактирование доступных тарифов и акций.
- Для оператора:
  - Авторизация.
  - Список всех предоплат с возможностью выбора актуальных (на сегодняшний день или тех, где услуга ещё не выполнена).
  - Поиск по номеру предоплаты (на текущий день) и/или по номеру/логину клиента.
  - _Всё то же, что было без приложения (Возможность оплаты и назначения специально выделенного "оффлайн" бокса и услуги)._
- Для мойщика:
  - Табло с номером предоплаты, статуса оплаты и услугой.

## Расчёты
### Точки:
 - Корсаков (5 боксов)
 - Долинск (7 боксов)
 - ЮС (10 боксов)

```
Рабочий день: 12 часов.
Среднее время обслуживания тс: 12.5 минут.
Среднее количество машин на один бокс в течение дня: 12 * 60 / 12.5 ~ 58 машин/бокс.
```
### Итоги:
```
Максимальное количество машин: 580 (10 боксов * 58) машин/день.
Минимальное количество машин: 0 или 290 (5 боксов * 58) машин/день.
```
### Ссылки
|Название               |Файл              |Изображение            |
|-----------------------|------------------|-----------------------|
|**UseCases**| [UseCases](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/UseCaseTT.md) | <img src="https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/Use_Cases.svg" width="300" alt="UseCases"> |

- [OpenAPI документация](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/api-docs.yaml)
- [ERD](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/ERD.svg)
  <img src="https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/ERD.svg" width="300" alt="Пример">
  ![ERD](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/ERD.svg "ERD")
- [Sequence Diagram для авторизации](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/SD_AuthRegistr.puml)
  ![SD_auth](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/SD_auth.svg "SD_auth")
- [Sequence Diagram для записи](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/SD_appointment.puml)
  ![SD_appoint](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/SD_appointment.svg "SD_app")
- [User story](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/UserStories.md)
- [User story Mapping](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/User%20Story%20Mapping.unidraw)
  ![User story Mapping](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/User%20Story%20Mapping.svg "User Story Mapping")
- [Status Model](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/StatusModel.uml)
- [C4](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/C4_model.unidraw)
  ![C4](https://github.com/Ossakeeper/PODVODNAYA_MOYKA/blob/main/C4_model.png "C4")
