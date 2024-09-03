Разработайте приложение «Словарь», позволяющее записывать в него не знакомые термины и их определения.

1. Функциональные требования: 

Поле для ввода, позволяющее изменить текст элемента.
Кнопка «Новый элемент» добавляет в список новый элемент.
Если поле внутри элемента пустое, то при снятии фокуса с поля элемент удаляется из списка.
Приложением можно пользоваться с клавиатуры (без использования мыши или трекпада):
Переключение между элементами происходит с помощью Tab (вперёд) и Shift + Tab (назад).
Переключение выполненности элемента происходит с помощью клавиши Enter, когда на элементе установлен фокус.
При создании нового элемента в его поле автоматически ставится фокус, чтобы сразу можно было начать печатать.
Технические требования
Вся логика должна быть вынесена в кастомные хуки, компоненты могут содержать только:

JSX-разметку.
Обработчики событий.
Вызовы кастомных хуков.
