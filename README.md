1)Классификации дефектов
Дефекты классифицируются с точки зрения команды QA как Приоритет, а с точки зрения разработки – как Серьезность (сложность кода для его устранения). Это две основные классификации, которые играют важную роль в сроках и объеме работ, которые требуются для устранения дефектов.
Приоритет определяется как порядок, в котором дефекты должны быть устранены. Статус приоритета обычно устанавливается командой QA при поднятии дефекта по отношению к команде разработчиков с указанием сроков устранения дефекта. Статус «Приоритет» устанавливается в соответствии с требованиями конечных пользователей.

Например, если логотип компании неправильно размещен на веб-странице компании, приоритет имеет высокий, но низкий уровень серьезности.
Приоритет можно классифицировать следующими способами:

Низкий – этот дефект может быть исправлен после исправления критических.

Средний – дефект должен быть устранен в последующих сборках.

Высокий – дефект должен быть устранен немедленно, поскольку дефект в значительной степени влияет на приложение, и соответствующие модули нельзя использовать до тех пор, пока он не будет исправлен.

Срочно . Дефект должен быть устранен немедленно, поскольку он серьезно влияет на применение или продукт, и продукт нельзя использовать до тех пор, пока он не будет устранен.

Низкий – этот дефект может быть исправлен после исправления критических.

Средний – дефект должен быть устранен в последующих сборках.

Высокий – дефект должен быть устранен немедленно, поскольку дефект в значительной степени влияет на приложение, и соответствующие модули нельзя использовать до тех пор, пока он не будет исправлен.

Срочно . Дефект должен быть устранен немедленно, поскольку он серьезно влияет на применение или продукт, и продукт нельзя использовать до тех пор, пока он не будет устранен.
Серьезность определяется как неявность дефекта в приложении и сложность кода для его исправления с точки зрения разработки. Это связано с аспектом развития продукта. Серьезность может быть решена на основе того, насколько серьезным является дефект системы. Статус серьезности может дать представление об отклонении в функциональности из-за дефекта.

Пример. Для веб-сайта, выполняющего рейсы, дефект при создании номера билета на основании бронирования имеет высокую степень серьезности, а также высокий приоритет.
Степень серьезности можно классифицировать следующими способами:

Критическое / Серьезность 1 – Дефект влияет на наиболее важные функциональные возможности приложения, и команда QA не может продолжить проверку приложения без его исправления. Например, приложение / продукт часто аварийно завершают работу.

Major / Severity 2 – Дефект воздействует на функциональный модуль; команда QA не может протестировать этот конкретный модуль, но продолжает проверку других модулей. Например, бронирование авиабилетов не работает.

Средняя / Серьезность 3 – Дефект имеет проблему с одним экраном или связан с одной функцией, но система все еще функционирует. Дефект здесь не блокирует какую-либо функциональность. Например, Ticket # является представлением, которое не следует за правильными буквенно-цифровыми символами, такими как первые пять символов и последние пять как числовые.
Низкая / Серьезность 4 – не влияет на функциональность. Это может быть косметический дефект, несоответствие пользовательского интерфейса для поля или предложение улучшить взаимодействие с конечным пользователем со стороны пользовательского интерфейса. Например, цвет фона кнопки «Отправить» не совпадает с цветом кнопки «Сохранить».


2)Вычисление среднего арифметического значения оценки в меньшую сторону 
double MinAVG(string [] marks)
Функция AVG возвращает среднее арифметическое по всем найденным записям. Среднее арифметическое группы чисел - это их сумма, деленная на их количество.

К примеру, у нас есть таблица с пользователями, в которой хранятся их возраста. С помощью AVG мы можем найти их средний возраст.
Синтаксис SELECT AVG(поле) FROM имя_таблицы WHERE условие!


![Снимок экрана (369)](https://user-images.githubusercontent.com/90610084/177032079-7d8a7631-21c3-4cc0-9373-30c79526bcb0.png)




[Снимок экрана (369)](https://user-images.githubusercontent.com/90610084/177032034-8712c86f-aab7-4755-95c5-745738d4e82e.png)

