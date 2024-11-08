[<- На главную](https://github.com/evgeniy-kotin/minecraft-v4?tab=readme-ov-file#оглавление)

# Регионы

## Выделение территории

Приват территории защищает ваши постройки и вещи. Старайтесь использовать его для всех своих важных построек. </br>
В чужом привате нельзя ставить и ломать блоки, убивать животных, открывать сундуки.

Сначала нужно получить инструмент для выделения - деревянный топор. Для этого нужно выполнить команду</br>
`//wand`

Чтобы выделить территорию, нужно указать две точки (два противоположных угла параллелипипеда).</br>
Первый - левый клик с топором в руке</br>
Второй - правый клик с топором в руке</br>
После того, как будет выбраны два блока, выделенная зона будет показана [рамкой](https://github.com/evgeniy-kotin/minecraft-v4/blob/main/images/regions_hover.png).

Чтобы расширить данную зону, нужно посмотреть в сторону расширения и выполнить команду</br>
`//expand <BLOCK_COUNT>`, где <BLOCK_COUNT> - количество блоков

Чтобы уменьшить зону выделения, нужно посмотреть в сторону уменьшения и выполнить команду</br>
`//contract <BLOCK_COUNT>`, где <BLOCK_COUNT> - количество блоков

Чтобы узнать количество блоков в выделенной территории, нужно выполнить команду</br>
`//size`</br>
На данный момент для всех игроков действует ограничение в 60 000 блоков для одного региона. 
Если нужно заприватить больше - нужно разделить территорию на несколько регионов

Чтобы убрать выделение, нужно выполнить команду</br>
`//sel`

## Приват территории

После того, как нужная территория была выделена, ее необходимо заприватить.</br>
Для этого нужно выполнить команду</br>
`/region claim <REGION_NAME>`</br>
Теперь выделенная область принадлежит вам и другие игроки не могут взаимодействовать с этим регионом.

Управление жителеями региона:</br>
`/region addmember <REGION_NAME> <PLAYER>` - добавить жителя <PLAYER> в регион <REGION_NAME></br>
`/region removemember <REGION_NAME> <PLAYER>` - удалить жителя <PLAYER> из региона <REGION_NAME></br>
Житель региона может полностью взаимодействовать со всеми блоками в регионе, но не может добавлять других жителей

Управление владельцами региона:</br>
`/region addowner <REGION_NAME> <PLAYER>` - добавить владельца <PLAYER> в регион <REGION_NAME></br>
`/region removeowner <REGION_NAME> <PLAYER>` - удалить владельца <PLAYER> из региона <REGION_NAME></br>
**У владельца региона есть все на права на добавление и удаления жителей и других владельцев. Не добавляйте случайных людей как владельцев**

Посмотреть информацию о регионе, в котором стоите:</br>
`/region info`

Чтобы удалить регион, нужно выполнить команду:</br>
`/region remove <REGION_NAME>`