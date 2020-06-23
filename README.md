## Скрипты для разработчиков

### Скрипты
#### ОбновлениеПлатформ.sdbl
В РАЗРАБОТКЕ<br>
Скрипт, который позволяет обновить платформы, установленные на компьютере.<br>
Скрипт проверяет список последний версий платформы на сайте, смотрит список баз компьютера, список установленных платформ. После чего определяет, какие версии платформ нужно установить, а какие - удалить.
- метод Скрипт() - запрашивает имя и пароль пользователя через консоль
- метод ОбновитьПлатформы() - использует имя пользователя и пароль из параметров запуска

### Библиотеки
#### ОпубликованныеПлатформы83.sdbl
В РАЗРАБОТКЕ<br>
Cкрипт для получения списка опубликованных на сайте релизов платформы 8.3<br>
- метод ВсеРелизы() - возвращает список всех релизов<br>
- метод ПоследниеРелизы() - возвращает список последних сборок каждого релиза платформы<br>

#### СписокИнформационныхБаз.sdbl
Cкрипт для получения списка информационных баз компьютера<br>
- метод ДоступныеБазы() - возвращает описание всех баз<br>
- метод ИспользуемыеВерсии() - возвращает все используемые версии платформы, указанные в списке баз<br>

#### УстановленныеПлатформы83.sdbl
Cкрипт для получения списка установленных на компьютере платформ и путей к ним<br>

#### dl-1c.sbsl
Скрипт для скачивания релизов. Автор Дмитрий Клименко. [Репозиторий](https://github.com/klimenko-1c/dl-1c)