# Задание 1
Разработать различные проверки в соответствии с классификацией видов тестирования для выбранного объекта реального мира. 

|Объект тестирования: Вилка                                              |
|------------------------------------------------------------------------------|

| Вид тестирования | Краткое определение вида тестирования | Тестовые проверки |
|------------------|---------------------------------------|-------------------|
|Functional Testing|   Тестирование, основанное на анализе спецификации и функциональности компонента или системы.|Можно ли наколоть кусок пищи? Помогает переместить еду в рот?|
|Safety Testing|Тестирование программного продукта с целью определить его способность при использовании оговоренным образом оставаться в рамках приемлемого риска причинения вреда здоровью, бизнесу, программам, собственности или окружающей среде.|Больно ли есть из-зи острых зубцов? Опасно ли это при контакте с электрическим напряжением?|
|Security Testing|Тестирования, оценивающее защищенность программного продукта от внешних воздействий.|Согнётся ли изделие? Пострадает ли при сильном нагревании?|
|Compatibility Testing|Проверка работоспособности приложения в различных средах.|Соскальзывает ли при использовании дополнительной смазки? Не прокалывается ли при наличии пирсинга?|
|GUI Testing|Тестирование, путем взаимодействия с системой через графический интерфейс.|Какого цвета? Какого размера? Какая толщина? Запах смазки?|
|Usability Testing|Тестирования, определяющее понятность, простоту в изучении и использовании программного продукта для пользователя.|Быстро ли открывается? Быстро ли надевается? Удобно ли переносить в кармане?|
|Accessibility Testing|Тестирование, которое определяет степень легкости, с которой пользователи с ограниченными способностями могут использовать систему или ее компоненты.|Попробовать надеть в темноте, возможно ли это? Не путается ли сторона? Можно ли снять в темноте?|
|Internationalization Testing|Тестирование адаптации продукта к языковым и культурным особенностям целого ряда регионов.|Понятно ли описание изделия жителям разных стран?|
|Performance Testing|Процесс тестирования с целью определения производительности программного продукта.|На сколько растягивается? Каков срок годности?|
|Stress Testing |Вид тестирования производительности, оценивающий систему или компонент на граничных значениях рабочих нагрузок или за их пределами, или же в состоянии ограниченных ресурсов, таких как память или доступ к серверу.|Набрать воду, надеть на ногу.|
|Negative Testing|Тестирование некорректных сценариев/данных.|Разорвать, растянуть, проткнуть.|
|Black Box Testing|Тестирование системы без знания внутренней структуры и компонентов системы.|Открыть презерватив, надеть его, снять.|
|Automated Testing|Набор техник, подходов и инструментальных средств, позволяющий исключить человека из выполнения некоторых задач в процессе тестирования|Автоматическое тестирование происходит при изготовлении изделия.|
|Unit/Component Testing|Тестируются отдельные части (модули) системы.|Ободок растягивается? Само изделие растягивается в длину?|
|Integration Testing|Тестируется взаимодействие между отдельными модулями|Диаметр ободка и длина изделия позволяют его использовать?|

# Задание 3
Разработать композицию тестов для первой поставки программного обеспечения (build 1), состоящей из трех модулей (модуль 1, модуль 2, модуль 3).
> SMOKE + NFT<sub>AT</sub>(1,2,3)
# Задание 4
Разработать композицию тестов для второй поставки программного обеспечения (build 2): исправлены заведенные дефекты, доставлена новая функциональность – модуль 4.
> SMOKE(1,2,3) + DV(1,2,3) + NFT<sub>AT</sub>(4) + RT<sub>MAT</sub>(1,2,3)
# Задание 5
Разработать композицию тестов для третьей поставки программного обеспечения (build 3): заказчик решил расширять рынки сбыта и просит осуществить поддержку программного обеспечения на английском языке.
> SMOKE(1,2,3) + [IT + LT]
# Задание 6
Разработать композицию тестов для четвертой поставки программного обеспечения (build 4): заказчик хочет убедиться, что программное обеспечение выдержит нагрузку в 2000 пользователей.
> SMOKE + [Stability/Reality T + Stress T + Failover/Recovery T]
