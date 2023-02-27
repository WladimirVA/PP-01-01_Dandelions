<p align="center">
<img  src="./static/img/Иконка _Лого_ (1_1).svg" width="40%">
</p>
 
# [“Тест для определения уровня владения английским языком”](http://vorobeyenglish.ru/)
## 1. Цель проекта
Цель проекта - разработать web приложение для пользователей (далее Приложение). Пользователь сможет определить уровень владения английским языком через тестирование. 	
## 2. Описание системы 
Система 	состоит из следующих основных блоков:
 	 	
1. Главная страница	
2. Форма 	ввода имени (без фамилии) 	 	
3. Функционал тестирования 	
4. Функционал результатов	
5. Функционал обратной связи

Система 	предусматривает один тип Пользователей. 	Он имеет доступ к главной странице, разделу обратной связи, форме ввода имени, тестированию и результату. 
## 2.1 Главная страница
На главной странице должно отображаться 	название: 		
«Узнай свой уровень английского языка» 	 	
 	 	
Название 	кликабельное на всех страницах проекта. При нажатии на Название осуществляется переход на Главную страницу.
Отображается информация для пользователя: 	
 	 	
«Вы 	можете пройти тестирование для определения уровня английского языка. Тест содержит 60 вопросов с возможностью выбора 1 правильного ответа из 4-х. Время 	на выполнения теста не ограничено. В конце Вы получите результат прохождения теста».
	
С главной страницы (из подвала) есть возможность перейти в раздел «Обратная связь»
	
Отображается кнопка «Начать тест». После нажатия на кнопку, появляется всплывающее окно «Форма ввода имени».
## 2.2 Форма ввода имени
По центру экрана появляется «Форма ввода имени» (далее Форма). Форма содержит 1 обязательное поле для ввода Имени 	пользователя. Поле допускает ввод символов кириллицей и латиницей. Минимальное количество символов 2, 	максимальное 255. Введенное имя используется 	для обращения к пользователю при выводе 	результатов. 	
 		
При 	открытой форме нельзя перейти в функционал любого другого окна.
 	
Форму можно закрыть нажатием на кнопку «×».


Отображается кнопка «Продолжить». Она становится активной только после ввода символов. При нажатии на активную кнопку 	пользователь переходит на новую страницу, начинается тестирование. 
## 2.3 Функционал тестирования 
Количество вопросов 60. Вариантов ответов 4 из которых 1 правильный (для всех вопросов).
 	
Вопросы отображаются рандомно с 1-го по 	60-й. Отображается номер вопроса. Правильный ответ не	отображается после каждого вопроса. 	
 	 	
Отображается кнопка «Далее». При нажатии на кнопку 	осуществляется переход к следующему вопросу. После 60-го вопроса при нажатии 	на кнопку «Далее» осуществляется переход в раздел Результатов.
## 2.4 Функционал результатов
На экране отображается результат прохождения 	теста с обращением к Пользователю по 	имени, которое он ввел ранее в Форме.
## 2.5 Функционал обратной связи
В разделе отображается информация о команде разработки и контактные данные (форма отправки письма в техподдержку)
## 3 Разработка проекта
Дизайн:  Figma

Frontend: HTML, CSS, JavaScript

Backend: GO v1.20, PostgreSQL v15
