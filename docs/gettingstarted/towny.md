## Города

**ДЛЯ ТОГО, ЧТОБЫ ПОНЯТЬ, КАК ПОЛЬЗОВАТЬСЯ ЭТИМ ПЛАГИНОМ - ВАМ ПРИДЕТСЯ СМОТРЕТЬ ТУТОРИАЛЫ И ГУГЛИТЬ!**

- [Ссылка на поиск в GOOGLE](https://www.google.com/search?q=towny+%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B)
- [Ссылка на поиск в ЯНДЕКС](https://yandex.ru/search/?text=towny+%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B&lr=39&search_source=yacom_desktop_common&rdrnd=465819&redircnt=1721922349.1)
- Или введите `/towny menu`

### Основа

Чтобы посмотреть на карту с городами перейдите на https://map.astrainteractive.ru/

- `/towny universe` - она покажет, сколько городов, резидентов и т.д
- `/town list` - Список городов
- `/nation list` - Список наций
- `/towny prices` - Просмотр цен на города и т.д
- `/town` - Просмотр информации о вашем городе
- `/town plots` - Информация о чанках вашего города
- `/towny time` - Узнать сколько времени до начала нового дня

### Создание города

⚠️️Создание города или нации стоит большого количества денег

⚠️️Создание городов и приват идет по чанкам. Нажмите F3+G для отображения чанков

⚠️️Можно занимать только соседние чанки

- `/town new НАЗВАНИЕ_ГОРОДА_НА_АНГЛИЙСКОМ` - Создайте город. Он будет создан, а чанк, в котором вы стоите, заприватится
- `/town НАЗВАНИЕ_ГОРОДА` - Информация о городе
- `/resident ИМЯ_ИГРОКА` - информация о резиденте
- `/t spawn` - Вернуться в город
- `/town set spawn` - Чтобы изменить спавн встаньте в новое место и введите
- `/resident toggle constantplotborder` - Вместо F3+G
- `/town claim` - Занять новый чанк
- `/town map` - Покажет карту чанков в чате
- `/town buy bonus 1` - Купить дополнительный бонусный чанк
- `/town invite ИГРОК` - Пригласить игрока в город
- `/town toggle open` - Сделать город открытым/закрытым для вступления

### Бабло

Чтобы город существовал - нужны деньги. Они берутся из казны города.

Введя команду /town вы увидите текущую сумму казны и ежедневную плату за город

Чем больше резидентов в городе - тем луче. Вы можете собирать с них налоги. В том же меню /town будет указан налог. Но
что самое замечательное - ВЫ как мэр можете брать деньги из казны!

⚠️У вас должен быть мозг. Надо посчитать, как лучше всего ваши резиденты должны платить налог. Например, если вы
установите налог в 10$ - то за 5 резидентов в день вы будете получать 100$. И если налог на город стоит больше чем 100$
очевидно что этого не хватит. Надо будет либо добавлять из своего кармана либо увеличивать налог на резидентов.

⚠️Резидент, который не выплатит налог, будет автоматически исключен из города!

⚠️Город, который не будет выплачивать налог будет автоматически превращен в руины

- `/town deposit СУММА` - Внесите деньги в казну
- `/town withdraw СУММА` - Взять сумму из казны
- `/town set tax СУММА` - Установить налог для резидентов
- `/town toggle taxpercent` - Установить налог в процентах. Люди будут платить % со своего баланса

Вы также можете устанавливать налоги на чанки

- `/t set plottax СУММА` - Установить налог на чанк в день

### Продажа плотов

Вы можете продавать чанки города резидентам. Когда резидент зайдет в такой чанк - он увидет уведомление о том, что чанк
на продажу.

- `/plot fs ЦЕНА` - Назначить цену за чанк
- `/plot nfs` - Убрать чанк с продажи

### Разрешения

- `/t set perm off` - Убрать все разрешения для города
- `/plot toggle ФЛАГ` - Отключить/Включить спавн мобов, взрывов и т.д
- `/plot set perm off` - Убрать все разрешения с текущего чанка в котором вы стоите
- `/t set perm resident build on` - Добавить резиденту разрешение строить, но не ломать на всех чанках города.
- `/t set perm КТО ПЕРМИШОН ФЛАГ` - Добавить новое разрешение. Пример ниже. Авто подстановка имеется, так что
  разберетесь
- `/plot set perm КТО ПЕРМИШОН ФЛАГ` - Добавить новое разрешение на один чанк. Авто подстановка имеется, так что
  разберетесь
- `/plot perm hud` - Включить/выключить скорборд с менюшкой

### Типы чанков

Можно добавлять разные типы чанков. Например, в фермерском чанке люди не смогу ломать что-либо. Только агрокультуру. В
диком чанке можно будет рубить деревья и т.д

- `/plot set ТИП_ЧАНКА` - Сделать чанк другого типа. Типы показаны в автозаполнении команды
- `/plot set farm` - Пример. Сделать чанк фермерским. Тип чанков показан в /towny map
