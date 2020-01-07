# Описание
Система позволяет структурировать накопленные знания - текстовые документы и видеоролики. Созданная структура используется для удобной навигации по всему массиву накопленных человеками знаний, даёт возможность целостного исследования и целостного восприятия и вообще.

## Ключевые сущности
Для удобства меня, в скобках даны названия которые используются в кодовой базе проекта

### Узел (Node)
Некая единица знания, которая может быть выделена из бушующего океана восприятия

Например:
- `person(name)` -  Человек имеющий имя 
- `lifetime (from, to)` - Время жизни с началом и концом (как жаль)
- `polity(description)` - Общественный строй с каким-то его описанием
- `law(description)` - Норма права/Закон с каким то его описанием
- `history_event(description)` - Историческое событие

### Связь (Connection)
Служит для обозначения того что между узлами есть связь

Например:
- `perons_lifetime(кто: person, сколько: lifetime)`
- `politiy_laws(строй: polity, законы: law[])` - законов тут может быть много

### Переход (Transition)
Служит для обозначения того что узел каким то образом преобразовался в другой

Например:
- `polity_polity: (было: polity, стало: polity, потому_что: history_event)`

Приведённые выше описания это структуры для заполнения конкретными значениями

# Пути развития
Возможны совершенное разнообразные общественно-культурные и даже лично-развлекательные полезные применения такой технологии

## Единое исследовательское сообщество
### Исследовательская карта/дневник
Самостоятельное создание типов узлов, соединений и переходов в ходе исследовательской деятельности, в дальнейшем созданная структура, может быть перенесена в “публичное” пространство и использована в исследованиях другими людьми

### Структурирование накопленного опыта
При внесение структуры в существующие исследовательские работы и статьи существенно повысится понятность широкому кругу читателей. А именно возможность исследования и углубления в предметную область следуя за смысловыми связями между элементами и возможность дать самостоятельную оценку значимости той или иной обнаруженной исследователем закономерности

## Образовательная системы которая будет приятна, понятна и интересна для ученика

### Домашнее образование
Для домашнего образование в широком смысле, как возможности для человека получить интерисующие его знания в простой для восприятия форме, в форме связанных друг с другом фактов, результатов исследований, умственных изысканий

### Обучение как исследование
Предоставление возможности углубиться в значимую лично для ученика область, в процессе погружения в интересный лично для человека предмет, он (человек) будет приобретать необходимые для дальнейшего изучения навыки, ведь все области знания разным образом связаны друг с другом. Осваивая их ученик получит цельное знание, цельное представление о мире и о себе в мире

## Разработка новых и улучшение существующих алгоритмов индексации и поиска в интернете
На подобной структуре можно создать систему индексации интернет страниц, качество поиска в такой системе будет значительно лучше по сравнению с алгоритмами, построенными на нейронных сетях и машинном обучении, применяемыми сейчас, тем более что то, каким образом нейросеть выстраивает внутренний алгоритм работы, не всегда доступно пониманию человека

## Искусственный интеллект в правовой сфере
Сейчас имеется множество нейронных сетей, обученные на выполнение конкретной узкой задачи, которая изначально задаётся разработчиком, обучение сети происходит путём  определения правильно/неправильно на огромных выборках данных, предполагается что после обучения сеть каким-то образом (недоступным человеческому пониманию) сформирует внутри себя алгоритм принятия решений в данной узкой ситуации и впредь будет принимать только верные решения.
Для того чтобы применять искуссвтенный интеллект в сферах близких деятельности человека, например автоматизация принятия правовых решений, должна иметься база знаний человеческих ценностей, на которых эти решение принимаются, их (ценностей) развития и изменения во времени, создание такой базы требует разработки структуры/каркаса, как бы того способа которым думает и принимает решения человек. Возможности приследить как ценность была сформирована, под действием каких обстоятельств. 
Я вижу возможность использования структуры, которая будет создана с помошью инструмента в том числе и для этих целей

# Планы
## Масштаб и детализация
Когда есть сформированная структура то полезно иметь возможность ознакомиться с ней с разного так сказать масштаба, видя только главные узлы и связи, более более детальное представление, полное представление. Для этого полезно иметь возможноть натсроить масштаб, глубину так сказать.

## Инструмент для Дискуссий и Обсуждения с вохможностью менять существующую структуру
По имеющимся узлам и связям полезно иметь возможность вести дискусии, при том не просто текстовую переписку а возможность в ходе дискуссии уточнять структуру узлов и связей.

## Привязка к карте
Узлы историко-географического характера полезно иметь привязать к карте.. Ну типо для наглядности. Грецию там, Римскую Империю и всякие такие прочие узлы

## Возможность размечать видеолекции
Так же как к определённому месту текста есть возможность привязать узел или связь, будет возможность и видеоролики размечать подобным образом, возможно интегрироваться с имеющимися видео хостингами, ютубом и тик-током (щутка)


