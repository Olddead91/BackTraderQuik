# BackTraderQuik
Провайдер для автоторговли в BackTrader из QUIK. Использует библиотеку [QuikPy](https://github.com/cia76/QuikPy).

### Для чего нужен
Чтобы торговые системы, написанные для BackTrader, можно было поставить на автоматическую торговлю в QUIK.

### Установка провайдера
1. Скопируйте файлы проекта в папку с торговой системой BackTrader

### Начало работы
В папке DataExamples находится хорошо документированный код примеров по работе с биржевыми данными из QUIK. С них лучше начать разбираться с библиотекой.

1. **Symbol.py** - Получение данных одного тикера по одному временнОму интервалу.
2. **Symbols.py** - Получение данных нескольких тикеров по одному временнОму интервалу. [Видео с разбором кода >>>](https://finlab.vip/symbolspy/)
3. **Timeframes.py** - Получение данных одного тикера по разным временнЫм интервалам методом прямой загрузки.
4. **Resample.py** - Получение данных одного тикера по разным временным интервалам путем конвертации меньшего временнОго интевала в больший (Resample). [Видео с разбором кода >>>](https://finlab.vip/resamplepy/)
5. **Replay.py** - Точное тестирование большего временного интервала с использованием меньшего.
6. **Rollover.py** - Склейка фьючерсов. Не работает у брокеров, которые не хранят историю фьючерсных контрактов.

В папке BrokerExamples находится хорошо документированный код примеров по работе со счетами, заявками и позициями из QUIK.

1. **LiveTradingEvents.py** - Перехват событий QUIK
2. **LimitCancel.py** - Выставление и отмена заявок

### Авторство, право использования, развитие
Автор данной библиотеки Чечет Игорь Александрович.

Библиотека написана в рамках проекта [Финансовая Лаборатория](https://finlab.vip/) и предоставляется бесплатно. При распространении ссылка на автора и проект обязательны.

Исправление ошибок, доработка и развитие библиотеки осуществляется автором и сообществом проекта [Финансовая Лаборатория](https://finlab.vip/).
### Что дальше
- Бесплатный курс "Автоторговля" по идеям, концепциям и процессам алгоритмической/автоматической торговли [смотрите здесь >>>](https://finlab.vip/wpm-category/autotrading2021/)


- Бесплатный курс "BackTrader: Быстрый старт" [ждет вас здесь >>>](https://finlab.vip/wpm-category/btquikstart/)


- [Подписывайтесь на Telegram канал "Финансовой Лаборатории",](https://t.me/finlabvip) чтобы быть в курсе всех новинок алгоритмической и автоматической торговли.