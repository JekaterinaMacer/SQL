# SQL

Здравствуйте, рады приветствовать Вас на курсе!

Наш курс является тренажером, поэтому состоит только из практических заданий. Перед тем как приступить, обязательно прочитайте информацию с этого шага.

Рекомендуемый алгоритм успешного прохождения каждого шага курса

Прочитайте текстовый материал, он достаточно короткий и всегда имеет всю необходимую информацию для выполнения практического задания.
Eсли по тексту теории встречаются примеры - скопируйте и вставьте их в окно кода, запустите запрос, не отправляя на проверку (нажать черную кнопку Запустить код). Проанализируйте результат, если он (результат) является неожиданным или не понятным - еще раз вернитесь к теории и еще раз ее прочитайте.
Теперь можно приступать к выполнению практического задания. Прежде всего внимательно прочитайте формулировку, разберитесь, что именно нужно сделать (без этого совершенно нет смысла писать код SQL);
Если задание понятно - можно приступать к реализации запроса, тут два варианта - либо Вы полностью напишете запрос на SQL, либо поищите среди примеров похожий, скопируйте его и начинайте его корректировать (скорее всего, когда пройдете десяток шагов, вариант с копированием отпадет, как ненужный).
Отправьте запрос на проверку.  Результата может быть два - либо запрос написан верно, и он проходит - можно переходить к следующему шагу. Либо запрос система не пропускает, в нем допущена ошибка, но "кто не ошибается, тот ничего и не делает...", ошибки это обязательный и полезный элемент в процессе обучения;
Начинайте отлаживать (исправлять) запрос, причем если Вам удастся это сделать самостоятельно - значит Вы  действительно разобрались с материалом шага, можно переходить к следующему. Если же ошибки исправить не удается,  не спешите паниковать, читать и писать комментарии, лезть в Интернет - просто вернитесь к 1 или 2-му пункту этого алгоритма.
Если же все-таки теория и примеры не помогают, воспользуйтесь памяткой о типичных ошибках и способах их исправления (приведена ниже),  примерно половина ошибок связана с описанными в ней пунктами и, привыкнув каждый раз проверять свой запрос, Вы сбережете себе много часов и нервов (проверено на опыте).
Когда Вы напишете правильный запрос, его можно опубликовать в решениях, посмотреть решения других студентов и обсудить свое.
В комментариях можно давать подсказки или делиться тем, что вызвало у Вас наибольшие трудности, только без спойлеров!
Очень полезно прочитать вопрос другого обучающегося и, если Вы точно знаете ответ, самостоятельно ответить на его вопрос - это еще один способ закрепления материала, причем очень действенный (тоже проверено на опыте).
После выполнения заданий каждого модуля, Вы будете получать ссылку на текстовый конспект этого модуля, по которому удобно ориентироваться по пройденному материалу.
 

Памятка о типичных ошибках и способах их исправления

Эта памятка написана, чтобы помочь Вам самостоятельно находить ошибки в своих запросах. Если ваш запрос не принимается системой, то возвращайтесь на эту страничку и пройдитесь по всем пунктам:

1. Приведите синтаксис запроса к общепринятому:

если у вас есть время, стоит изучить руководство по стилю SQL https://www.sqlstyle.guide/ru/
можете отформатировать ваш запрос с помощью, например, https://codebeautify.org/sqlformatter
в любом случае, информации и примеров в курсе достаточно для того, чтобы писать запросы корректно.
2. Проверьте, что ключевые слова, названия столбцов и значения в ячейках, которые необходимо найти, написаны правильно. Особенно обратите внимание, чтобы в русских названиях столбцов не было английских букв.

3. Проверьте, что:

количество открывающихся скобок равно количеству закрывающихся;
запятые разделяют перечисление столбцов, но не ключевые слова;
запросы разделяются точкой с запятой.
4. Проверьте, что последовательность команд указана верно (она отличается от последовательности выполнения команд в запросе):

SELECT 'столбцы или * для выбора всех столбцов; обязательно'

FROM 'таблица; обязательно'

WHERE 'условие/фильтрация, например, city = 'Moscow'; необязательно'

GROUP BY 'столбец, по которому хотим сгруппировать данные; необязательно'

HAVING 'условие/фильтрация на уровне сгруппированных данных; необязательно'

ORDER BY 'столбец, по которому хотим отсортировать вывод; необязательно'
5.  Если запрос включает подзапросы, выполните сначала подзапросы и удостоверьтесь, что получаете ожидаемый результат.

6. Прочитайте комментарии под заданием: большинство трудностей уже обсуждалось не один раз.
