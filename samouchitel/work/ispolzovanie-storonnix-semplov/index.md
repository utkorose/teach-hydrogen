---
title: Использование сторонних семплов
author: Администратор Сайта
layout: page
easy_noindex_nofollow_index:
  - 0
easy_noindex_nofollow_follow:
  - 0
---
В драм-машине Hydrogen есть возможность использования семплов, не входящих ни в одну из доступных на официальных страницах проекта библиотек. Это может пригодиться тем, кому не нравятся звуки ударных в этих библиотеках, либо тем, кому захочется использовать помимо стандартных ударных какие-нибудь необычные звуки &#8212; к примеру, звук включения лазерного меча из &#171;Звёздных Войн&#187; Джорджа Лукаса.

Для того, чтобы использовать свой семпл в Hydrogen, нужно взять какой-либо из уже существующих в проекте семплов(можно в том числе использовать и пустой, если таковые имеются), указать в нём другой звуковой файл(который лучше закинуть в папку с библиотеками ударных), после чего изменить наименование семпла в списке из редактора паттерна.

Включите стойку инструментов(кнопка в правом верхнем углу), наведите курсор на левую верхнюю вкладку этой панели(&#171;инструмент&#187;) и  щёлкните левой клавишей мыши. У этого пункта есть два подпункта &#8212; instrument(или &#171;общие&#187;) и layers(или &#171;слои&#187;). Выберите второй пункт &#8212; layers(&#171;слои&#187;), после чего удалите все имеющиеся там слои. Для удаления слоя его нужно выделить с помощью курсора и нажать им на кнопку в правом нижнем углу &#8212; &#171;delete layer&#187;(&#171;удалить слой&#187;). После удаления всех старых слоёв со звуками нажмите на соседнюю с этой кнопкой &#171;load layer&#187;(загрузить слой). После этого выберите в открывшемся окне ваш файл.

<span style="text-decoration: underline;"><strong>Важно:</strong></span> в пути к файлу и самом имени файла не должно быть кириллических символов, то есть:

*   *D:\семплы\бадабум.wav &#8212; **ПЛОХО***
*   *D:\samples\badabum.wave &#8212; **ХОРОШО.***

После того, как семпл выбран, осталось из вкладки управления слоями перейти в соседнюю вкладку(&#171;instrument&#187; или &#171;общие&#187;), в открывшемся меню общих настроек навести курсор на название инструмента и щёлкнуть левой клавишей мыши. После этого изменить имя инструмента.  
[<img src="http://img-fotki.yandex.ru/get/6607/129199783.1/0_8fbb2_ac653edc_L.jpg" width="480" height="426" title="" alt="" border="0" />][1]  
[Посмотреть на Яндекс.Фотках][1]

<span style="text-decoration: underline;"><strong>Важно:</strong></span> звук у инструмента *может быть выключен* по-умолчанию. Как правило, в таком случае на соответствующей ему полоске в матрице редактирования паттерна первый из двух квадратиков(оранжевый) будет более тёмным, чем когда звук включен. Если это так &#8212; включите звук этого инструмента в микшере, сделав параметр &#171;Mute&#187; неактивным с помощью клика левой кнопки мыши. Либо, что проще, кликните по квадратику-индикатору. Если звук семпла будет включен, то соответствующий оранжевый квадрат станет более светлым.  
[<img title="" src="http://img-fotki.yandex.ru/get/6409/129199783.1/0_8fbb1_5061e804_L.jpg" alt="" width="354" height="248" border="0" />][2]

<p style="text-align: center;">
  << <a href="/samouchitel/work/upralenie-udarnym/">Предыдущая</a> -*- <a href="/samouchitel/work/">Работа с программой</a> -*- <a href="/samouchitel/work/nastrojka-udarnyx-1-miksher/">Следующая</a>>>
</p>

 [1]: http://fotki.yandex.ru/users/teachhydrogen/view/588722/
 [2]: http://fotki.yandex.ru/users/teachhydrogen/view/588721/
