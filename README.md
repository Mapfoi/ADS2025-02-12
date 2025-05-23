# ADS2025-02-12

## Algorithms & Data Structures

### Начало работы:

**Посмотрите видео: <a href="https://youtu.be/mIs-X63CH78" target="_blank">Tutorial:QuickStart</a>**
<br>_(оно старое, но переписывать смысла нет, все понятно должно быть)_.

1. Инициализация. Нажмите Fork на странице https://github.com/Khmelov/ADS2025-02-12/
2. У вас в аккаунте fork появится тут https://github.com/ваш_логин/ADS2025-02-12
3. Выберите в IDEA git -> clone (или New-Project from Version control) и затем:
   * укажите ссылку на Ваш fork https://github.com/ваш_логин/ADS2025-02-12;
   * выберите путь к директории (папке) проекта без русских букв и пробелов;
   * укажите имя директории проекта (например ADS2025-02-12_verXX - такой директории на диске быть не должно).
   * после создания проекта нужно вручную добавить источник для обновлений VCS -> Git -> Remote имя **upstream** с URL: https://github.com/Khmelov/ADS2025-02-12/
4. если проект не компилируется, возможно потребуется подключить библиотеку init.jar (это модифицированный JUnit 4)
   - удалите все библиотеки в свойствах проекта
   - подключите init.jar (щелкните на ней правой кнопкой и выберите команду **Add as library**)

### Перед **каждым** сеансом работы:

1. Обязательно проверьте что все закоммичено (**это важно**)
2. Получите последние изменения основного репозитория Git -> Pull (выберите **upstream** как источник)
3. **Скопируйте** папку с заданиями и тестами (by.it.a_khmelev.lessonXX) в свою папку ((by.it.groupXXXXXX.фамилия.lessonXX))
   - фамилия, это пакет в java, поэтому допускаются только латинские буквы, и обязательно все в нижнем регистре
4. Отправьте эти изменения в свой репозиторий Git -> Commit + Push
5. Возможные ошибки (по этим причинам Pull Request не будет приниматься)
   - НЕ решайте задания в a_khmelev
   - НЕ переносите файлы из a_khmelev, а копируйте их
   - НЕ создавайте папки с буквами в верхнем регистре
   - НЕ изменяйте чужие файлы ни на байт (это приводит к ошибкам слияния)

### Работаем с кодом:

1. Добавьте файлы ВСЕ java-файлы вашего пакета под контроль версий (Ctrl+Shift+A или Git -> Add)
2. Работайте с кодом. Добейтесь чтобы проект собирался и запускался **без ошибок**.
3. Делайте коммиты Ctrl+K. _возврат на пункт 2 нужное число раз
4. Отправьте накопленные изменения в свой репозиторий Git -> Push
5. Если работу нужно сдать, проверьте что проект собирается и запускается, затем можно сделать Git -> Pull Request (в master)
<br>_при коммитах видно какие изменяются файлы. Должны быть изменения **только в вашей папке**_

### ВНИМАНИЕ!

Если проект не запускается из-за ошибок в чужих директориях/папках/пакетах **НЕ ИСПРАВЛЯЙТЕ ИХ!**.
<br>Кто-то их тоже исправит и будет конфликт слияния на github.
<br>**А как тогда сделать правильно?** Просто отключите проблемную директорию (папку):
* выделите её в дереве проекта
* нажмите на ней правой кнопкой мыши
* Выполните команду Mark Directory as -> Excluded
* эта команда затронет только Ваш компьютер

### Если все поломалось! 
Значит пока не знаете git, или java, или Idea ;). Но исправить все можно даже не зная этого. 
Аварийный вариант восстановления репозитария.

1. **Скопируйте** свою папку из src/by/it/ в отдельное место на диске.
   * найти свою папку на диске можно выделив ее в дереве папок в IDEA. Далее, правая кнопка -> Open in Explorer.
2. Удалите fork из своего аккаунта github (откройте форк на сайте, выберите Setting-Delete this repository)
3. Выполните всю последовательность из шапки (см. <b>Начало работы</b>).
4. Верните свою папку на место в свежем проекте.
5. Делайте коммит Ctrl+K.
6. Отправьте накопленные изменения в свой репозиторий Git -> Push

Версия **java 21-я** (это актуальня LTS-сборка).
Другие версии **НЕ ИСПОЛЬЗУЙТЕ**, проект не соберется у других и при проверке.


_С уважением, Александр Хмелев._
