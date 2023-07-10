# Инструкция Telegram PRO

Актуальную инструкцию к спамеру можно найти [здесь](https://holmen.gitbook.io/telegram-pro/).

## Возможности
- Спам под последними постами, последним комментарием.
- Отслеживание постов и спам 1-м комментарием.
- Редактирование комментария через заданное время.
- Использование и замена картинок в комментариях.
- Вступание в каналы.
- Изменение имя, фамилии, описания и аватарки в профиле.
- Удаление остальных сессий(устройств) и установка 2FA.
- Уникализация комментария (замена символов) в случайном порядке.
- Уникализация текста (замена символов) на английские, греческие и красивый русский шрифт.
- Работа с несколькими аккаунтами (работа аккаунтов по-очередно).
- Запоминание проспамленных каналов из прошлого аккаунта и продолжение того же списка каналов на новом аккаунте (Работает даже после перезапуска программы).
- Проверка ссылки на валидность (публичные/приватные)
- Использование прокси при работе.
- Установка лимитов комментариев на один аккаунт.
- Оповещение о важных действиях бота в ТГ.
- Включать и выключать показ превью при спаме.
- Автоматически сокращать размер картинки.
- Менять ссылку в тексте каждый аккаунт.

## Инструкция по установке
Перед использованием бота необходимо скачать [Python](https://www.python.org/ftp/python/3.11.1/python-3.11.1-amd64.exe). Во время установки не забудьте установить галочку напротив "Add python.exe to PATH".

![Установка Python](https://i.imgur.com/9Vdl03a.png)

После того как мы установили Python, заходим в Telegram PRO. После запуска и у вас откроется консоль и установятся все необходимые библиотеки. После установки у вас откроется программа и покажет уникальный ключ вашего устройства. Нажимаем кнопку "Скопировать ключ" и отправляем разработчику в ЛС.

## Навигация по софту

Запуск софта производится через файл "Telegram PRO". 

Если ваш ключ был активирован, у вас откроется интерфейс программы. 

**В софте есть 3 основных раздела:**

![Раздел основной](https://i.imgur.com/wNeIMBB.png)

Главный раздел, который отображает всю необходимую информацию о работе софта и состоянии аккаунтов.

---

![Раздел настроек](https://i.imgur.com/QP0zBFL.png)

Настройки софта

---

![Раздел замены символов](https://telegra.ph/file/132a4ddc02448cfe6e57b.png)

Замена символов в тексте. В данный момент доступно 4 варианта: на англ. буквы, на греческие буквы и два других шрифта.

---

Далее идет кнопка, нажав по которой, вы можете получить уникальный ключ вашего устройства.

## Настройка софта

В этом пункте вам может показаться что настроек слишком много и бот очень сложный, но это так кажется, т.к здесь расписаны настройки для всех режимов бота. Когда вы выберете в боте конкретный режим, у вас останутся только те настройки, которые вам нужны для работы этого режима.

Для начала разберем режимы работы, всего в софте их 4:

1. **Спам на последние посты во всех каналах** - В этом режиме работы не нужно вступать в каналы, достаточно лишь вписать каналы в настройке "Список каналов". Этот режим просто спамит комментариями под последними постами. Также в настройке "Количество считываемых постов для спама" можно установить кол-во постов, под которыми бот будет спамить в каждом канале. Например, если установить 3, то бот отправит комментарий в каждом канале под тремя последними постами.

2. **Стандартный спам** - для его использования, вам нужно быть участником каналов. Этот режим отправляет комментарий сразу, как только появляется новый пост в канале. Комментарий можно вписать в настройке "Текст для спама".

3. **Спам с заменой через N сек**. - Выполняет ту же самую функцию, что и стандартный спам, только теперь при выходе поста бот отправляет "Белый текст" (Настроить можно в "Белый текст для спама") и через заданное кол-во секунд (Настраивается в настройке "Задержка редактирования комментария") заменяет комментарий на текст для спама. 

4. **Спам с заменой через N сообщений** - Данный режим работы очень похож на "Спам с заменой через N сек", только тут комментарии редактируются при достижении отправленных N белых комментов. Т.е как только бот отправит, например 20 комментариев, он сразу же начнет заменять все комментарии на текст для спама.

Теперь предлагаю пройтись по переключателям, которые находятся в самом вверху настроек. Их всего 13:

1. **Запоминать проспамленные каналы** - Благодаря этой функции вы можете заставить бота запоминать каналы, в которых он уже проспамил. Например: У вас в базе 200 каналов, первый аккаунт проспамил 70 каналов и если эта функция будет выключена, то бот переключится на второй аккаунт и начнет проходить заново по списку каналов. Если же эта функция включена, то бот будет со второго аккаунта продолжит тот список каналов, который проходил первый аккаунт. При перезапуске программы бот все также сохраняет историю проспамленных каналов.

2. **Проверять ссылку на валидность** - Перед запуском каждого аккаунта бот будет искать в вашем тексте ссылку и будет проверять вашу ссылку на доступность. Если ссылка была удалена, то бот останавливает работу. Если же ссылка доступная, то бот продолжает работу. **Поддерживаются только ссылки Телеграмма.**

3. **Использовать изображения** - В софте также можно использовать картинки при спаме. Если в канале запрещено их использовать, то бот будет отправлять комментарий без картинки. При включении этого переключателя, появятся две настройки "Путь до обычного изображения" и "Путь до изображения для спама". В эти настройки вам нужно вписать название и формат изображения, наприрмер, "*image.png*", без ковычек. Все изображения хранятся в папке image.

4. **Сокращать размер изображения** - При использовании изображений можно установить этот параметр и ваши изображения будут сжиматься до 500 пикселей, при этом сохраняя соотношение сторон. Это позволит быстрее отправлять комментарии из-за маленького веса картинки.

5. **Заменять изображения каждый аккаунт** - С помощью этой функции вы сможете использовать разные картинки каждый аккаунт (1 картинка - 1 аккаунт). Картинки для по-очередной замены вы сможете найти по пути image/image_replace, в эту папку закидываем картинки в любом формате и нумеруем их в нужном порядке. Картинки будут браться по числам в порядке возврастания, т.е от 1 и например до 20. Сначала будет идти стандартная картинка для спама в папке image, а далее на второй и следующие аккаунты браться из папки image_replace.

6. **Удалять сессии с установкой 2FA** - Если вашей сессии уже есть 24ч+, то с аккаунта можно выкинуть пользователя и установить 2FA (двухфакторный пароль), чтобы он не смог войти в аккаунт. При включении этой настройки появится поле для ввода пароля для 2FA. Туда вписываем какой-нибудь пароль. Если эта настройка включена, то перед запуском бота хозяин будет выкинут из аккаунта и установлен двухфакторный пароль.

7. **Вступать в каналы** - Эту настройку необходимо включать для 2,3 и 4 режима работы. Он вступает в каналы, которые указаны в настройке "Список каналов для вступления".

8. **Менять аватарку, имя и описание** - При включении этой настройки бот будет менять профиль аккаунта. Указать имена, описание и аватарки можно в папке profiles. Там вы найдете файлы "name.txt", "about.txt", в них можно вписать имя и описание. Далее в папке photos закидываем аватарки, можно любое название и любой формат (png, jpg). Бот будет брать рандомные имена, описание и аватарку из указанных вами данных.

9. **Уникализировать каждый раз текст** - При включении этой функции, перед отправкой ваш текст для спама будет прогонятся через специальный модуль, который заменяет русские буквы на похожую букву из английского или греческого алфавита.

10. **Использовать прокси** - При включении этой функции, бот будет использовать прокси. При включении появится поле для ввода данных прокси.

11. **Использовать Telegram уведомления** - При включении этой функции, бот будет отсылать вам важные уведомления в вашего телеграм бота. Нужен будет токен бота и ваш ID в телеграме.

12. **Использовать превью в комментариях** - Использование функции "превью" из Telegram. Если не знаете что это такое, то попробуйте отправить ссылку кому-нибудь в ЛС в телеграме и под ссылкой вы увидите превью.

13. **Заменять ссылку в тексте каждый аккаунт** - При использовании этой функции в боте будет автоматически заменяться ссылка в вашем тексте после каждого пройденного аккаунта. Чтобы добавить ссылки, нужно включить этот параметр и найти параметр "*Список ссылок для замены в тексте*" и нажать редактировать. Туда нужно вставить столько же, либо больше ссылок, чем у вас аккаунтов. **Работает только с ссылками Телеграмма.**

Далее пройдемся по остальным настройкам в боте. Их тут тоже достаточно:

- **Задержка отправки комментариев** - Указывайте значение в секундах, через которое вы хотите отправлять коммент. Например, появился пост и через заданное кол-во секунд отправится комментарий. Если хотите убрать задержку на комментарий, то впишите 0.

- **Задержка редактирования комментария** - Уже разбирали, используется для второго режима.

- **Количество считываемых постов для спама** - Тоже разбирали, используется для третьего режима.

- **Лимит комментариев для редактирования** - Тоже разбирали, используется для четвертого режима.

- **Перерыв между сессиями** - В софте можно закинуть сразу несколько сессий и выставить между ними перерыв, этот параметр отвечает именно за это. Например, вы используете 3-й режим, бот раскидал комменты по всем каналам и закончил работу с сессией. Прежде чем перейти ко второй сессии, он будет ждать заданное кол-во секунд.

- **Лимит отправленных сообщений с 1-го аккаунта** - В этой настройке мы можем установить лимит комментариев для каждого аккаунта. Если поставим 0, то лимитов не будет. Если поставим 50, то каждый аккаунт будет отправлять максимум 50 комментариев (считаются только успешно отправленных комментарии).

- **Данные прокси (HTTP)** - Здесь вы указываете данные от прокси в формате "*ip:port@login:password*". Поддерживаются только прокси формата HTTP(S).

- **Токен Telegram бота** - Заходим в @BotFather в Telegram и создаем бота с любым названием и любой ссылкой. Далее вставляем сюда токен бота.

- **Ваш Telegram ID** - Переходим в @getmyid_bot в Telegram и получаем ID своего аккаунта Telegram и вставляем его в эту строчку. На этот аккаунт вам будут приходить уведомления.

- **Текст для спама** - При нажатии кнопки редактировать откроется текстовый документ, в который мы закидываем наш крео. Можно использовать [Markdown](https://confluence.twin24.ai/pages/viewpage.action?pageId=126484785) (стилизация текста). Если не знаете что это, то можете кликнуть на надпись и почитать подробнее. Также вы можете использовать несколько крео для спама. Просто в конце крео с новой строки впишите "/split" и далее с новой строки вставьте свой другой крео. Бот будет выбирать каждый раз рандомное крео.

- **Белый текст для спама** - Также открывается текстовый документ, в котором вы можете вписать с новой строки какой-нибудь "белый текст" для спама.

- **Список каналов для спама** - Откроется текстовый документ, сюда мы вставляем ссылки на каналы построчно, в которых хотим спамить. Этот список используется только для первого режима работы.

- **Список каналов для вступления** - Откроется текстовый документ, сюда мы вставляем ссылки на каналы построчно. У Telegrama лимит запросов на вступление около 40 каналов в день!

- **Список ссылок для замены в тексте** -  Сюда вставляем ссылки для параметра "Заменять ссылку в тексте каждый аккаунт". Ссылок должно быть столько же, либо больше, чем кол-во ваших аккаунтов в боте.

Как только мы установили все необходимые нам настройки, нам нужно нажать кнопку **"Сохранить"**, чтобы наши параметры сохранились. Если вы вдруг захотите быстро перекинуть ваши параметры в другого бота, то просто перекидывайте файл "config.ini", в нем хранятся все ваши настройки.

## Установка аккаунтов и запуск софта

После того, как мы все настроили, нам нужно закинуть наши аккаунты(сессии) в бота. **Поддерживаются только сессии формата Telethon!**

Закидываем сессии в папку sessions, после перезапускаем софт и можно начинать работу. Для того, чтобы запустить бота нужно нажать на зеленую кнопку слева.

![Работа софта](https://telegra.ph/file/67156a28db1a3ee8f75b4.png)

В боте нереализована функция паузы, поэтому если вы вдруг во время работы нажмете на красную кнопку "Стоп" (появится после старта программы), то программа остановится и закроется.

Если вдруг останутся какие-либо вопросы или появятся проблемы во время использования софта, то сообщайте мне в [ЛС](https://t.me/HolmenGS), будем разбираться :)