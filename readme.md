Test Face recognition


Тестовое задание

 
Используя предоставленный обучающий датасет, обучить нейронную сеть и подготовить итоговую модель для определения оценки схожести (L2 дистанцию или косинусное расстояние) двух изображений лиц. 

 

Нейронная сеть должна принимать на входе одноканальные изображения размера 32х32. 

 
На предоставленном тестовом датасете, используя обученную модель, получить оценки схожести пар изображений лиц. На основе оценок схожести и лейблов получить  Accuracy, EER и FAR/FRR график.

 
Лейблы имеют следующий вид:

positive - на паре изображений лица одного и того же человека

negative - на паре изображений  лица разных людей

 
Также представить чекпоинты моделей, код пайпланов обучения и теста. Также составить презентацию о процессе и результатах обучения.


Обучающий датасет: CASIA WebFace https://arxiv.org/pdf/1411.7923.pdf , 10572 классов (уникальных лиц), 490623 изображений

Тестовый датасет: LFW http://vis-www.cs.umass.edu/lfw/, 3000 positive и 3000 negative пар. 

Оба датасета заранее выравнены(aligned) по 5 точкам(центры глаз, кончик носа и уголки рта). 

Скачать можно по следующей ссылке:

https://data.oz-services.ru/download/oz/test.tar.gz

Если все понятно или есть вопросы - пишите сюда

Ждем решение в понедельник 22.11

