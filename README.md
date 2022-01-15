# Flight rules for New Dev

#### What are "flight rules"?

Руководство для астронавтов (теперь программистов, которые попали к нам в проект) о том как быстрее всего разобраться в проекте.

> Правила полёта - совокупность авиационных правил и инструкций, предусматривающих выполнение полётов в условиях, при которых местонахождение, пространственное положение и параметры полёта воздушного судна определяются по показаниям пилотажно-навигационных приборов.

#### Conventions for this project
Для начала, вам не следует отправлять ненужные пробелы. Git предоставляет простой способ проверки — перед коммитом выполните команду ``git diff --check``, которая выведет список ненужных пробелов. Выполняя эту команду перед коммитом вы сможете избежать отправки ненужных пробелов, которые могут раздражать других разработчиков. Далее, постарайтесь делать коммит логически разделённого набора изменений. Если возможно, попытайтесь делать ваши изменения легко понятными — не нужно писать код все выходные, работая над пятью разными задачами, а в понедельник отправлять результат как один большой коммит. Даже если вы не делали коммиты на выходных, то в понедельник используйте область подготовленных файлов для того, чтобы разделить проделанную работу по принципу минимум один коммит на задачу, давая полезные комментарии к каждому из них. Такой подход так же облегчает извлечение или отмену отдельных изменений, если это вдруг потребуется в будущем.

Последнее, что нужно иметь ввиду — это сообщение коммита. Привычка создавать качественные сообщения к коммитам позволяет упростить использование и взаимодействие посредством Git. Как правило, ваши сообщения должны начинаться кратким однострочным описанием не более 50 символов, затем должна идти пустая строка, после которой следует более детальное описание. Проект Git требует, чтобы детальное описание включало причину внесения изменений и сравнение с текущей реализацией — это хороший пример для подражания. Пишите сообщение коммита в императиве: «Fix bug» а не «Fixed bug» или «Fixes bug». 

Давайте рассмотрим простой пример рабочего процесса, который может быть полезен в вашем проекте. Ваша работа построена так: Вы работаете над сайтом, Вы создаете ветку для нового файла, который вы пишете, Вы работаете в этой ветке. В этот момент вы получаете сообщение, что обнаружена критическая ошибка, требующая скорейшего исправления. Ваши действия: переключиться на основную ветку, создать ветку для добавления исправления, после тестирования слить ветку содержащую исправление с основной веткой, переключиться назад в ту ветку, где вы пишете код и продолжить работать. Подробнее об этом можно почитать [тут](https://git-scm.com/book/ru/v2/%D0%92%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-Git-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-%D0%B2%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B8-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D1%8F).

### Kanban 
В проекте используется методология Kanban. Это метод управления разработкой, реализующий принцип «точно в срок» и способствующий равномерному распределению нагрузки между работниками. При данном подходе весь процесс разработки прозрачен для всех членов команды. Задачи по мере поступления заносятся в отдельный список, откуда каждый разработчик может извлечь требуемую задачу. Подробнее [тут](https://www.atlassian.com/ru/agile/kanban).

### Front-end
[Flight rules Front-End.md](Front-End.md)

### Back-end
[Flight rules Back-End.md](Back-End.md)


