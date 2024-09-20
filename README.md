# yandex_praktikum_sprint_7

Тебе предстоит протестировать API учебного сервиса Яндекс.Самокат. Его документация: qa-scooter.praktikum-services.ru/docs/.

Протестируй ручки
Проверь, что они корректно работают и выдают нужные ошибки.
Создание курьера
Проверь:
курьера можно создать;
нельзя создать двух одинаковых курьеров;
чтобы создать курьера, нужно передать в ручку все обязательные поля;
запрос возвращает правильный код ответа;
успешный запрос возвращает ok: true;
если одного из полей нет, запрос возвращает ошибку;
если создать пользователя с логином, который уже есть, возвращается ошибка.
Логин курьера
Проверь:
курьер может авторизоваться;
для авторизации нужно передать все обязательные поля;
система вернёт ошибку, если неправильно указать логин или пароль;
если какого-то поля нет, запрос возвращает ошибку;
если авторизоваться под несуществующим пользователем, запрос возвращает ошибку;
успешный запрос возвращает id.
Создание заказа
Проверь, что когда создаёшь заказ:
можно указать один из цветов — BLACK или GREY;
можно указать оба цвета;
можно совсем не указывать цвет;
тело ответа содержит track.
Чтобы протестировать создание заказа, нужно использовать параметризацию.
Список заказов
Проверь, что в тело ответа возвращается список заказов.
Отчёт Allure
Сгенерируй его и запушь в репозиторий.#   S p r i n t _ 7  
 #   S p r i n t 7  
 