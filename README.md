# Switcher
Switcher - небольшая утилита без зависимостей. Позволяет манипулировать классами, когда проиводится клик по DOM-элементу.

Управляется только data-атрибутами, которые присваиваются элементам, с классами которых будут производиться манипуляции

## Параметры: 
* data-togglr-target = "SELECTOR" - селектор элемента, с классами которого будут производиться манипуляции (целевой элемент)
* data-togglr-toggle  = "CLASS" - класс, который будет переключаться у целевого элемента
* data-togglr-add = "CLASS" - добавляет класс целевому элементу
* data-togglr-remove = "CLASS" - удаляет класс у целевого элемента
* data-togglr-exclusive = "CLASS" - переключает класс у целевого элемента и удаляет этот класс с элементов, которые являются соседними для целевого  
* data-togglr-exclusiveAdd = "CLASS" - добавляет класс целевому элементу и элементам, которые являются соседними для целевого

Если другие параметры, кроме data-toggl-target не заданы, то по умолчанию используется значение data-togglr-toggle ="IsActive" (*IsActive - класс по умолчанию*)

Switcher работает с динамически добавленными узлами

**Когда Switcher успешно инициализирован, он добавляет класс "togglr" в узлел html**
