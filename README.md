##Онлайн редактор кода


###Из чего состоит редактор
- Серверная часть с поддержкой WebSocket’ов и также выступающая в роли веб-сервера, который будет отдавать страницы.
- Браузерная клиентская часть, которая предоставляет интерфейс редактора


###Что должен уметь редактор
Синхронизировать изменения в коде между двумя пользователями


###С использованием чего должен быть написан
- jquery.widget factory. Компонент редактора должен быть полностью обернут в jquery.widget.
- Встраиваемый редактор кода Ace
