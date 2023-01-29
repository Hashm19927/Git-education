# Git инструкция

## Загрузка программы и установка

- Шаг один 1 (Загрузка)

Нам нужно скачать Git. Следуйте по ссылке ниже:
https://git-scm.com/downloads

Вам необходимо выбрать конфигурацию вашего компьютера и установить нужную версию

- Шаг 2 (Установка)

**Запустите загруженный файл, прочитайте соглашение и нажмите «Далее»"**

![](1.jpg)

**Далее выбираем галочки, которые нам нужно установить. (Для дальнейшей работы лучше выбрать те, что вы видите на GIF)**

![Alt text](2.gif)

**Далее выберите редактор, в котором будете работать. Если у вас установлен код Visual Studio, то выберите его, потому что дальнейшую работу мы будем выполнять в нем.
Если нет, то выбираем Vim, позже можно будет поменять**

![Alt text](3.jpg)

**Далее оставьте все галочки как есть. В последнем окне следует обращать внимание только на предложения. Но вам решать, хотите ли вы получать уведомления или нет. Их можно удалить.**

![Alt text](4.jpg)

## Поздравляем, вы установили Git.

## *Для дальнейшей работы пройдемся немного по основным командам, которые нам понадобятся для работы в Git*


# <span style="color:green"> Basic commands to get started

*git --version:* Indicates the version of git that is installed on your computer. And the path to the file

*git init:* Initializing or creating a repository

*git add .* Adding a file/folder for further work with it in editor. **Adding all files at once, if we put a "dot"**

*git add 'files_name':* Adding a file/folder for further work with it in editor. **Adding the specific file you want**

*git commit -m 'comment':* Creating a commit. Saving the work you've done.

# <span style="color:Blue"> Additional Commands for Checking Data and Reverting to Commits

*git log:* Get changes, saves, and commit codes so that you can return to that branch of work if necessary

*git checkout <first 4 digits of the code branch>:* command to go back to the save/commit you want to go back to![Alt text](5.jpg)

The first 4 digits will be enough to return to commit you want.

git config -- global user.email '': This command will allow you to link to the email you signed up with on Github

git config -- global user.name '': We set our name. To ensure that any changes are recorded by those who make them. You could also refer to them later.

## *Russian instructions about fonts*

## Выделение текста

чтобы выделить текст курсивом, необходимо обромить его звездочками (*), или знаком нижнего подчеркивания (_) Например *вот так* или _вот так_

чтобы выделить текст полужирным, необходимо обромить его двумя звездочками (**), или знаком нижнего подчеркивания (_) Например **вот так** или _вот так_

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа, например:
_Текст моежт быть выделен курсивом и полужирным_, при этом **полужирным**