# academic performance
Исследование успеваемости студентов за учебный год и поиск полезных закономерностей.

Контекст задачи\n
Студенты успешно завершили два семестра обучения и теперь руководство хочет получить детальную информацию о том: а) изменилась ли успеваемость по сравнению с предыдущим семестром; б) больше ли студентов не явилось на контрольные и прочие финальные испытания (вкл. устный экзамен); в) изменился ли средний балл за устный экзамен? за семестр? г) есть ли особенности у групп разных уровней (от Elementary до Advanced), которые следует учитывать при методическом планировании нагрузки д) группы какого уровня показали лучшую успеваемость по итогам года/каждого конкретного семестра? и т.д

Задача – сравнить успеваемость разных групп студентов и ответить на вопроы выше

Описание данных: два .csv файла* с оценками и идентичной структурой колонок, отражающие успеваемость по разным аспектам в течение одного семестра каждый. *персональные данные студентов заменены на uuid'ы в целях анонимизации и соблюдения всех требований обработки такого типа персональных данных.

Столбцы:
stud_id - уникальный идентификатор студента(uuid)
level - уровень группы по шкале CEFR (от Elementary до Advanced)
group - номер группы (условный)

practice_m1/m2/m3/m4 - баллы за работу на практических занятиях в 1,2,3 и 4 модуле соответственно(MAX - 15)
grammar_m1/m2/m3/m4 - баллы за работу занятиях по грамматике в 1,2,3 и 4 модуле соответственно. (MAX - 10)

case_study/2nd_term - баллы за решение прикладного кейса(ситуации, которая описывает финансовое положение конкрентной компании, вызовы, которые перед ней лежат и цели, которые нужно достичь. Студенты дожны выработать решение и предоставить отчет (MAX - 10)

final_test - баллы за финальный тест (последнее письменное испытание перед экзаменом (MAX - 10)
oral_exam - баллы за ответ на устном экзамене (MAX - 20, 0 баллов при отказе от ответа)
pre_exam_total - кол-во баллов за весь семестр за вычетом устного ответа на экзамене (MAX - 80)
total - общее кол-во баллов за весь семестр с результатом за устный экзамен (MAX - 100)

Заключения и рекомендации\n
По итогам исследования были сформулированы выводы и даны ценные рекомендации.
