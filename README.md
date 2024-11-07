## Краткое описание
Мой проект предназначен для того, чтобы управлять проектами в компании, где проект компании - это группа задач и подзадач. В моем проекте можно: 

* Назначать людям задания
*  Планировать проект с помощью инструментов таких как
   - Диаграмма Ганта
   - Канбан доска.
Проект протестирован на Windows 10 и 11, работоспособность на остальных платформах не гарантируется. Если вы столкнетесь с проблемой, расскажите о ней в [Issues](https://github.com/maxxximgb/ProjectManager/issues).

## Сборка
1. Убедитесь, что у вас установлен интерпретатор Python версии 3.9 и выше.
2. Клонируйте проект на ваш компьютер
3. Откройте командную строку в папке проекта
4. Проверьте, установлен ли у вас pyinstaller, если нет то выполните команду
```
pip install pyinstaller
```
5. Перейдите в папку приложения, которое вам нужно собрать.<br/>
 
5.1 Для сервера
```
cd Server
```
5.2 Для клиента
```
cd Client
```
6. Выполните команду
```
build
```
7. Готовое приложение будет находится в папке dist соответствующего собранного вами приложения.

## Ccылки
[Техническое задание](https://drive.google.com/file/d/1228ewiIHi2A2qkSbr0gXxEK064GIZFSH/view)    |    [Пояснительная записка](example.com)    |    [Презентация](example.com)
