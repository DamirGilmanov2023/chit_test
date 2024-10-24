<h3>Описание</h3>
<p>Скрипт на python для создания базы ответов на вопросы онлайн тестов в сайта rsmu.ru.</p>
<p>Бот авторизуется в системе:</p>
<p><img src="./img/Снимок экрана от 2024-10-24 16-32-15.png"/></p>
<p>Отвечает на вопрос и завершает тест. Проверяет результат вопроса -> правильный или нет.</p>
<p>Правильный записывает в файл output.xlsx лист true, не правильный в лист not.</p>
<p><img src="./img/Снимок экрана от 2024-10-24 15-54-08.png"/></p>
<p><img src="./img/Снимок экрана от 2024-10-24 15-54-19.png"/></p>
<p>После того, как база вопросов собрана, можно привести ее в читабельный вид с помощью скриптов gen_html и gen_pdf</p>
<p><img src="./img/Снимок экрана от 2024-10-24 15-53-39.png"/></p>
<p>Сохраненные картинки сохраняются в папку img.</p>
<p>Скрипт также проверяет отвечен ли был вопрос ранее и если отвечен, то отвечает на него. 
  Не правильные ответы тоже учитываются при ответе.</p>