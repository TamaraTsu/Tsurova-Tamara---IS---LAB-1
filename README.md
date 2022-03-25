# VidjayaStiven-IS-Lab
Intelligent System laboratory work
Виджая Стивен 932001 2022

## Предметная область: ЭС по выбору автомобиля
## Команда:
Андрюшина Мария 932001

Виджая Стивен 932001

Танумихарджя Рафаэл Мэтью 932001

Цурова Тамара 932001

## Link to site
https://car-picker-is-lab1.herokuapp.com/
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/80201768/160152216-9704fcab-60c9-4fbd-a38f-c8824139f3bf.png">


## Как использовать наше веб-приложение:
1. Clone Repository. / Клонируйте репозиторий
2. Open terminal / Откройте консоль
3. pip install flask / Установите библиотеку flask 
4. pip install pymongo / Установите библиотеку pymongo
5. Start debugging main.py file. / Запускайте питонский файл "main.py"
6. Press ctrl (on Windows) / cmd (on Mac) and click on the link from the console. Нажмите ctrl (в Windows) / cmd (в Mac) и нажмите ссылку из консоли.
7. You can start use our web application in your browser. / В вашем браузере вы можете начать использовать наше веб-приложение

## Video of the program
Backend Version: **1.0.0**

Video: https://disk.yandex.com/d/B-rylhY4VN4_aw

Frontend Version: **1.0.0**

Video: https://disk.yandex.com/i/KTPNIMTEob92Xg

## Test
Пользователь хочет найти варианты автомобилей, со следующим характеристиками:

1. **Цена**: От 3.000.000 До 5.000.000
2. **Стиль**: SUV или Sedan
3. **Тип топлива**: Бензин
4. **Тип передачи**: Механическая или Автоматическая
5. **Бренд**: Mazda или Mercedes-Benz или BMW или Honda или Kia
6. **Цвет**: Чёрная, Красная
7. **Год производства**: Не старше 2015
8. **Размер**: Средняя
9. **Категория**: Экономичная

## Result
Наша ЭС возвращает все самые подходящие варианты, а так же другие подходящие варианты соответственно Базе Знаний: 

1. Та же самая цена, стиль, тип топлива, тип передачи, год производства, размер и категория
2. Не принимая во внимание Бренды и Цвета

Все результаты пока находятся внутри папки Car_API и папки Test_Result_File.

Файл *test_best_match.txt* - это результаты всех подходящих вариантов машин

Файл *test_close_match.txt* - это результаты всех других подходящих вариантов машин
