# Курсовой проект по курсу "Проектирование информационных систем"

## Тема: Проектирование информационной системы поддержки разработки и обновления приложений для мобильных устройств 

#### Разработка функциональных моделей (IDEF0)

Внешними входными информационные потоки системы:
- Исходный код.
- Описание конфигурации.
Внешние выходные информационные потоки системы:
- Установочный пакет приложения.
Внешними управляющими потоками процесса являются:
- Бизнес-требования.
Основными механизмы процесса:
- DevOps инженер.
- Команда разработчиков.
- Система контроля версий Git.
- SDK для разработки.
- Внешние сервисы.


* Контекстная диаграмма А0 "Автоматизировать процесс DevOps мобильного приложения":

![none](https://viska97.github.io/design2018/Kursovaya/01_A0.png)

* Декомпозиция диаграммы А0:

![none](https://viska97.github.io/design2018/Kursovaya/02_A0.png)

* Декомпозиция блока А2: "Собрать приложение":

![none](https://viska97.github.io/design2018/Kursovaya/04_A2.png)

***

#### Разработка моделей потоков данных (DFD)

* Допустимые виды хранилищ и их размещения:
  - База данных на сервере БД.
  - Репозиторий кода на сервере.
  - Репозиторий артефактов на сервере.
  
* Декомпозиция блока А1 "Настроить конфигурацию":
![none](https://viska97.github.io/design2018/Kursovaya/03_A1.png)

* Декомпозиция блока А21 "Загрузить код в репозиторий":
![none](https://viska97.github.io/design2018/Kursovaya/05_A21.png)

* Декомпозиция блока А22 "Запустить процесс сборки":
![none](https://viska97.github.io/design2018/Kursovaya/06_A22.png)

* Декомпозиция блока А23 "Выполнить локальные тесты":
![none](https://viska97.github.io/design2018/Kursovaya/07_A23.png)

* Декомпозиция блока А24 "Собрать тестовый артефакт":
![none](https://viska97.github.io/design2018/Kursovaya/08_A24.png)

* Декомпозиция блока А25 "Загрузить тестовый артефакт в репозиторий":
![none](https://viska97.github.io/design2018/Kursovaya/09_A25.png)

* Декомпозиция блока А3 "Протестировать приложение на устройствах":
![none](https://viska97.github.io/design2018/Kursovaya/10_A3.png)

* Декомпозиция блока А4 "Распространить приложение":
![none](https://viska97.github.io/design2018/Kursovaya/11_A4.png)

* Расчёт UFP:
![none](https://raw.githubusercontent.com/VasilyMaterikin/design2018-kursovaya/master/ufp.png)

* Оценка объема работ методом FPA IFPUG:
![none](https://raw.githubusercontent.com/VasilyMaterikin/design2018-kursovaya/master/ifpug.png)


* Расчёт трудозатрат методом COCOMO II
![none](https://raw.githubusercontent.com/VasilyMaterikin/design2018-kursovaya/master/cocomo2.png)

* Расчет ожидаемого эффекта проекта

![none](https://raw.githubusercontent.com/VasilyMaterikin/design2018-kursovaya/master/economics1.png)
![none](https://raw.githubusercontent.com/VasilyMaterikin/design2018-kursovaya/master/economics2.png)

***

#### Разработка диаграмм классов (ERD)

* [Диаграмма ERD для потоков](https://github.com/VasilyMaterikin/viska97.github.io/design2018/blob/master/Kursovaya/flows.txt)<br>
![none](http://www.plantuml.com/plantuml/proxy?idx=0&src=https://raw.githubusercontent.com/VasilyMaterikin/viska97.github.io/design2018/master/Kursovaya/flows.txt)<br>

* [Диаграмма ERD для ролей](https://github.com/VasilyMaterikin/viska97.github.io/design2018/blob/master/Kursovaya/roles.txt)<br>
![none](http://www.plantuml.com/plantuml/proxy?idx=0&src=https://raw.githubusercontent.com/VasilyMaterikin/viska97.github.io/design2018/master/Kursovaya/roles.txt)<br>

* [Диаграмма ERD для модулей](https://github.com/VasilyMaterikin/viska97.github.io/design2018/blob/master/Kursovaya/modules.txt)<br>
![none](http://www.plantuml.com/plantuml/proxy?idx=0&src=https://raw.githubusercontent.com/VasilyMaterikin/viska97.github.io/design2018/master/Kursovaya/modules.txt)<br>

***

#### Файлы курсового проекта

* [Модель в формате .rsf](https://github.com/VasilyMaterikin/viska97.github.io/design2018/blob/master/Kursovaya/kursovaya.rsf) 

* [Курсовой проект в формате .docx](https://github.com/VasilyMaterikin/viska97.github.io/design2018/blob/master/Kursovaya/%D0%9A%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F%20-%20%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%BA%D0%B8%D0%BD%20%D0%92.%D0%92.docx)

* [Курсовой проект в формате .pdf](https://github.com/VasilyMaterikin/viska97.github.io/design2018/blob/master/Kursovaya/%D0%9A%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F%20-%20%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%BA%D0%B8%D0%BD%20%D0%92.%D0%92.pdf)
