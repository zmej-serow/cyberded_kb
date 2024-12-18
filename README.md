## Что это?

В этом репозитории хранится база знаний, которую использует бот одного *уютного велочатика* ["Бициклы, пиво и мачки"](https://t.me/veloserbia),
ведь, как известно, закрепы никто не читает, если их больше одного. Поэтому закрепы переехали сюда.

Крайне приветствуется участие — создание новых и редактирование старых заметок. Всё, что для этого нужно — всего лишь
завести себе аккаунт на GitHub, если его ещё нет, и создать merge request с изменениями, которые невыносимо хочется внести. :)
После проверки реквеста изменения будут вмёржены в репозиторий и примерно через 10 минут бот станет чуточку мудрее. Помните,
что заметка должна быть лаконичной (до 4096 знаков — ограничение телеграма), содержать достоверные сведения и быть полезной сообществу — словом, вы бы хотели видеть
такую информацию в закрепах чата.

*Если совсем лень или слова «merge request» звучат как страшное ругательство, присылайте инфу [мне](https://t.me/zmejserow), я сам добавлю.*

## Отлично! Я в доле!

Файл должен называться так же, как команда бота, которую нужно ассоциировать с его содержимым.
Например, `club.md` добавит боту команду `/club`, по которой он будет выдавать текст из `club.md`.
Разумеется, названия файлов должны быть уникальными; наверное, стоит избегать заглавных букв, т.к. их труднее набирать.

Первая строка файла содержит краткое описание команды, оно будет показываться по команде `/help`.
Например, в `club.md` первая строка — "Актуальная ссылка на официальный клуб чата в страве".
Краткое описание команды обязательно должно отделяться от собственно текста пустой строкой.

Оформление текста — простой [Markdown](https://www.markdownguide.org/cheat-sheet).
К сожалению, [благодаря олимпиадникам](https://core.telegram.org/bots/api#markdownv2-style) из telegram, весь набор
Markdown сейчас не поддерживается (а мне лень пилить полноценный парсер, подстраиваясь под урезанное подмножество
Markdown, которое они осилили завезти в телегу). Работает жирный текст, наклонный, ненумерованные списки, ссылки,
зачёркнутый текст, ещё что-то по мелочи. В общем, делайте merge request, а там разберёмся, может быть, добавлю
поддержку чего-нибудь. :) Plain text тоже сожрёт, конечно.
