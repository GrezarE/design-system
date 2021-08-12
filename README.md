  # Лендинг NASA. Описание

Перед вами лендинг для туристов. Он содержит описание предложения по космо-туризму: возможные маршруты, информацию о компании и способы оплаты. Лендинг сделан с помощью дизайн-системы NASA.

### Задание

Используя компоненты дизайн-системы NASA добавить модальное окно. Модальное окно открывается по клику на кнопку «Оставить заявку» и содержит форму подачи заявки для туристов.
Компонент модального окна содержит:
- Заголовок: «Расскажите о себе»,
- Подзаголовок: «и отправьтесь в космос вместе с NASA!»,
- Текстовое поле ввода с подписью: «Ваше имя»,
- Заголовок «Выберите планеты, которые хотели бы посетить»,
- 7 чекбоксов с названиями всех планет солнечной системы (кроме Земли),
- Заголовок «Выберите удобный способ оплаты»,
- 4 радио-кнопки: наличные, Bitcoin, Dogecoin и Chillim
- Кнопка «Отправить заявку»
- Иконку крестика, по клику на которое модальное окно закрывается


### Структура проекта
├── assets/

│       ├──  nasawds-3.0.177/   ── содержит  файлы последней версии дизайн-системы

└──  index.html ── файл с разметкой лендинга

### Для работы с дизайн-системой NASA вам понадобятся
- https://designsystem.digital.gov/ ── страница дизайн-системы.
- https://designsystem.digital.gov/components/overview/ ── список компонентов с их описанием и примерами кода.
- https://designsystem.digital.gov/design-tokens/ ── вспомагательные возможности для построения проекта.
- https://designsystem.digital.gov/utilities/ ── для использования дополнительных свойств CSS.
- https://designsystem.digital.gov/documentation/developers/#css-architecture - про архитектуру CSS.

### Примечание

В данной дизайн-системе используется другое соглашение по именованию: БЭМ модификаторы прописываются не через «_», а через «--», например: `usa-button--secondary` и это нормально.

### Ссылка 

https://grezare.github.io/design-system/

### Репозиторий проекта

[Репозиторий проекта на GitHub](https://github.com/bruffridge/nasawds)
