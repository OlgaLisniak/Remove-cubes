	ИГРА "REMOVE CUBES"


	Выполнила Лисняк Ольга


	index.html - основной скрипт игры и разметки страницы;
	css/style.css - все стили для элементов;
	Readme.txt - пояснение к игре.
	
	Результат теста по HTML находится в папке html test.
	Результаты тестов по JS находятся в папках JS test(60%) и JS test(90%).


	Правила игры:

Для того чтобы начать игру необходимо нажать кнопку "New Game".

Время отведенное для игры 1 минута. При начатии игры время отсчитывается в обратную сторону.
Посмотреть оставшееся время можно возле надписи Time left.

В поле игры (таблице) ячейки начнут заполняться разными цветами. 
Изначально заполняется случайное число ячеек от 1 до 3. 
При нажатии на цветную ячейку она пропадает, игроку добавляется 1 балл и отображается это 
в поле Points. После того как пропадает одна ячейка на поле появляются следующие 
заполненные ячейки (их количество так же от 1 до 3)*. 

Когда время заканчивается, то появляется всплывающее окно, где в поле Score указано
количество набранных очков за игру, а в поле Name игроку необходимо заполнить своё имя
и нажать кнопку Save. После чего этот результат будет занесён в таблицу результатов 
(Result Table). При перезагрузке страницы таблица результатов очищается.

Для того чтобы приостановить игру на паузу нужно нажать на кнопку Pause,
а для того чтобы возобновить - Resume.


* Иногда уже заполненная ячейка может изменить цвет т.к. поле игры небольшое, а если 
 каждый раз генерировать заполнение клеток (числом от 1 до 3) только на пустых местах, 
 то могу предположить, что не останется свободного места с истечением времени.


	Используемый язык - Javascript. А также библиотека JQuery.
	Элементы игрового поля - HTML-элементы. 
	Для упрощения работы с элементами интерфейса был применен CSS-фреймворк Bootstrap.
	
	
	Совместимость с браузерами:

Игра совместима с Google Chrome, Opera, Mozilla Firefox и Microsoft Edge.
