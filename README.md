# myfavoritesong
Practice on Version Control with Git training from EPAM

Установите git и сгенерируйте пару ssh ключей. Авторизуйте публичный ключ на github.com.
Укажите свой user.name и user.email в git.
Создайте новый репозиторий на github.com и склонируйте его локально на свой компьютер.
Создайте файл названием song.txt и поместите туда половину текста любимой песни.
Сделайте коммит с названием "add first half of my favorite song" и отправьте его на сервер.
Убедитесь что на github есть файл song.txt с текстом песни.
Используя веб-интерфейс гитхаба добавьте вторую половину текста песни и сделайте коммит с названием "finish my song".
В локальном репозитории сделайте pull и убедитесь что коммит, который вы создали на github, подтянулся и у вас полный текст песни.

Данное задание выполняется сразу после предыдущего (I Can Win).
1. Добавьте в проект файл .gitignore и настройте так чтобы скрыть файлы с расширением .db, .log и директории с названиями target или bin.
2. Создайте ветку feature и добавьте в неё два коммита
3. Смержите ветку feature в master
4. Вернитесь в feature и создайте файл arrows.txt cледующего содержания:
The ship glides gently on the waves
As day turns into night
Выполните коммит.
5. Перейдите в master. Создайте там файл arrows.txt и добавьте следующий текст:
One thousand burning arrows
Fill the starlit sky
Выполните коммит.
6. Смержите feature в master решив конфликт: сохраните все 4 строки в файле arrows.txt в порядке их добавления в пунктах 4 и 5.

Данное задание выполняется после предыдущего (Bring It On).
1. Создайте ветку storm и добавьте коммит в файл storm.txt:
Twenty ships with Norsemen braves
Riding the northern wind
2. Добавьте еще 2 строки в storm.txt и сделайте еще один коммит:
They left their shores at early dawn
As a red sun was rising in the east
3. Вернитесь в master и создайте файл pursuit.txt с текстом ниже:
The warming sun returns again
And melts away the snow
The sea is freed from icy chains
Winter is letting go
Выполните коммит.
4. Отметьте коммит тегом session1 и перейдите в ветку storm
5. Сделайте rebase ветки storm так чтобы она содержала последний коммит из мастера.
