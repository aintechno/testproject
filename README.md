
При выполнении тестового задания я использовал возможности простого JavaScript, а также библиотеки Lodash

Как работает программа:
1. Необходимо выбрать файл с данными (data.json), для этого, на страницу был добавлен input
   (Такой подход обусловлен тем, что как я понял из ТЗ, 
   проверка тестового задания будет проводиться на локальной машине, 
   без использования локального сервера, а прочитать содержимое файла, 
   который хранится локально, не на сервере, не представляется возможным)
2. После получения всех данных из файла data.json, на странице появляются checkbox, каждый из которых 
содержит уникальное свойство объектов, которые были получены из файла ранее
3. После выбора checkbox и нажатия на кнопку "Найти", на страницу выводятся все объекты, 
в которых присутствуют выбранные свойства. Также, на страницу выводятся максимальные и минимальные 
значения повторяющихся свойств у разных объектов в следующем формате: PROPERTY_NAME_max или PROPERTY_NAME_min

Стилизация документа не была осуществлена, т.к. в ТЗ такое требование отсутствует

Возможно, задание выполнено не совсем правильно, т.к. я не до конца понял, что необходимо реализовать