---
title: Программирование партий
author: Администратор Сайта
layout: page
easy_noindex_nofollow_index:
  - 0
easy_noindex_nofollow_follow:
  - 0
---
После того, как программа установлена, выбрана и настроена библиотека ударных &#8212; можно переходить непосредственно к &#171;набиванию партий&#187;. Для этого разберёмся с проектом. Под вторым слоем меню Hydrogen-a располагается матрица управления композицией. Она состоит из квадратиков серого цвета. Синим цветом программа выделяет активные квадратики. При нажатии кнопки |||> (проиграть\остановить) или пробела Hydrogen начнёт проигрывать все квадратики слева направо, точнее проигрываться будут только активные, синие квадраты. Каждый квадратик длится определённое количество времени, которое зависит от нескольких параметров &#8212; в том числе от темпа. Например, стандартный квадрат, равный такту, при темпе 120 длится две секунды.  
Создайте новый проект. Загрузите в качестве используемой библиотеки group-gdrums-nsk(которую было <a href="http://t-hydrogen.ru/uchebnik/work/ustanovka-bibliotek-udarnyx/" target="_blank">рекомендовано установить ранее</a>), после чего выберите в левой колонке меню управления композицией Pattern 1. Заполните его, как на рисунке:  
[<img title="programming1" alt="programming1" src="http://img-fotki.yandex.ru/get/9356/129199783.1/0_c8cf2_7e385ca7_L.png" width="500" height="213" border="0" />][1]  
[В другом размере][2]  
(для удобства иструмент &#171;Zildjian Avedis HiHat Closed (RH)&#187;, он же закрытый хэт, был перемещён ближе к остальным инструментам, на самом деле он довольно-таки удалён от начала списка ударных библиотеки)

После того, как закончите, нажмите пробел или кнопку &#171;воспроизвести&#187;. Если всё сделано правильно &#8212; вы услышите(004.mp3):



В Hydrogen, как и во многих прочих драм-машинах, имеется два режима проигрывания партий &#8212; режим &#171;pattern&#187; и режим &#171;song&#187;(композиция). [<img title="" alt="" src="http://img-fotki.yandex.ru/get/4523/129199783.0/0_72ebb_84c7673d_L.jpg" width="426" height="102" border="0" />][3]

При включении первого режима проигрывается только тот паттерн, который в данный момент выбран для редактирования, при включении второго &#8212; вся композиция. Правая крайняя из кнопок на панели воспроизведения(она находится слева от индикаторов режима проигрывания партий) отвечает за цикличность воспроизведения &#8212; когда она активна, при завершении проигрывания паттерна или композиции программа начинает воспроизводить их сначала. Теперь можно слегка разнообразить нашу партию. Наведите курсор на Pattern 1, кликните правой клавишей мыши и выберите &#171;Скопировать&#187;. После подтверждения копирования переключите режим воспроизведения с &#171;pattern&#187;, который стоит по-умолчанию, на &#171;song&#187;, и заполните матрицу композиции следующим образом:  
[<img src="http://img-fotki.yandex.ru/get/9515/129199783.1/0_c8d05_484beffe_L.png" width="305" height="140" title="" alt="" border="0" />][4]  


Теперь при нажатии кнопки &#171;|| >&#187; сначала три раза проиграется первый паттерн, затем один раз второй. Но новый паттерн повторяет первый, поэтому его нужно отредактировать. Выберите его и отредактируйте, как показано на фото ниже:  
[<img src="http://img-fotki.yandex.ru/get/9151/129199783.1/0_c8d07_308a2258_L.png" width="500" height="170" title="" alt="" border="0" />][5]  
  
Если всё правильно сделано &#8212; при проигрывании вы услышите это(005.mp3):  


Этот ритм уже более разнообразен. Однако в драм-машине Hydrogen можно проигрывать и несколько паттернов одновременно, что очень удобно. Наведите курсор на Pattern3 в матрице композиции, щёлкните правой клавишей мыши и в выпавшем контекстном меню выберите &#171;свойства&#187;. Переименуйте один из не использованных паттернов в &#171;Crash&#187; (&#171;крэш&#187;). Когда в композиции используется 10 паттернов и больше возможность редактировать их названия очень удобна, это позволяет не запутаться. В переименованном паттерне поставьте лишь одну точку для инструмента crash3 под цифрой 1 &#8212; в самом начале паттерна. [<img src="http://img-fotki.yandex.ru/get/9510/129199783.1/0_c8d11_36c23b28_L.png" width="500" height="173" title="" alt="" border="0" />][6]  
[Посмотреть на Яндекс.Фотках][6]

Теперь, когда готов третий паттерн, его можно поставить на место. Как правило, стандартно &#171;крэш&#187; используется для обозначения начала какой-то отдельной, логически завершённой части композиции. Он часто звучит в начале куплета, припева, соло, им могут выделяться так же отдельные части. Вот и здесь поставьте паттерн с крэшем в начале нашей композиции из 4х тактов:  
[<img title="" alt="" src="http://img-fotki.yandex.ru/get/6605/129199783.1/0_8ff88_f355a6b8_L.jpg" width="380" height="149" border="0" />][7]

Теперь проиграйте полученную композицию снова. Вы должны услышать следующее(006.mp3):



Теперь приглядитесь к панели над списком паттернов &#8212; она видна, например, на предыдущей иллюстрации. На панели находятся несколько кнопок, которые могут вам пригодиться в работе над паттернами. Это кнопки:

*    &#187;*clear*&#187; &#8212; очищает содержимое паттерна, убирая все точки;
*   &#171;+&#187; &#8212; создаёт новый паттерн, на тот случай, если вам не хватает 10 паттернов, которые используются по умолчанию;
*   две кнопки &#171;вверх&#187; и &#171;вниз&#187; &#8212; перемещают выделенный паттерн в списке вверх и вниз соответственно;
*   &#171;выделять кнопки&#187; &#8212; включает режим, когда можно выделить несколько активных паттернов с помощью мыши и удалить их с помощью клавиатурной клавиши &#171;*delete*&#171;;
*   &#171;рисовать паттерны&#187; &#8212; возвращает первый режим, при котором с помощью курсора мыши щелчком левой клавиши активируется нужный паттерн в матрице либо деактивируется;
*   s*ingle pattern mode* &#8212; непонятно, что она делает.

При наведении курсора на паттерн и нажатии правой клавиши мыши откроется *контекстное меню*, которое предлагает(соответственно):

*   &#171;скопировать&#187; &#8212; предлагает создать новый паттерн, повторяющий по содержанию выбранный;
*   &#171;заполнить/очистить&#187; &#8212; активировать/деактивировать данный паттерн на матрице управления композицией от первой указанной позиции до второй указанной позиции(позволяет быстрее заполнять матрицу синими квадратами, если те идут большим количеством подряд);
*   &#171;свойства&#187; &#8212; изменение имени паттерна (используйте только английские символы и цифры);
*   &#171;загрузить паттерн&#187; &#8212; позволяет загрузить готовый паттерн из файла формата *.h2pattern*;
*   &#171;сохранить паттерн&#187; &#8212; позволяет сохранить паттерн в файл формата *.h2pattern*;
*   &#171;виртуальный паттерн&#187; &#8212; автоматически ставит вместе с данным паттерном любые из выбранных(для одновременного воспроизведения).

Напоследок, чтобы набор возможностей редактировании композиции, рассмотрим контекстное меню семпла.  Для того, чтобы его открыть, наведите курсор на назание семпла в меню редактирования паттерна и щёлкните правой клавишей мыши. Открывшее меню предложит следующие пункты:

*   &#171;удалить все ноты&#187; &#8212; удаляет все точки для выбранного инструмента в выбранном паттерне;
*   &#171;заполнить ноты&#187; &#8212; проставляет для выбранного инструмента точки в редакторе паттерна на пересечениях со всеми вертикальными полосами;
*   &#171;случайная сила нажатия&#187; &#8212; не работает;
*   &#171;удалить инструмент&#187; &#8212; удаляет инструмент из списка ударных проекта.

Так же не стоить забывать про два квадрата справа от названия семпла(первый, оранжевый &#8212; отключить звук данного семпла, второй, зелёный &#8212; отключить звук у всех семплов, у которых которых зелёный квадратик не активен).  
[<img style="border: 0px;" alt="" src="http://img-fotki.yandex.ru/get/6606/129199783.1/0_90049_8cfb62bf_L.jpg" width="272" height="224" border="0" />][8]

<p style="text-align: center;">
  << <a href="/uchebnik/work/v-razrabotkenastrojka-udarnyx-ch3-nalozhenie-effektov/">Предыдущая</a> -*- <a href="http://t-hydrogen.ru/uchebnik/work/">Работа с программой</a> -*- <a href="/uchebnik/work/izmenenie-dlitelnostej/">Следующая</a>>>
</p>

&nbsp;

 [1]: http://fotki.yandex.ru/users/teachhydrogen/view/822514/
 [2]: http://fotki.yandex.ru/
 [3]: http://fotki.yandex.ru/users/teachhydrogen/view/470715/
 [4]: http://fotki.yandex.ru/users/teachhydrogen/view/822533/
 [5]: http://fotki.yandex.ru/users/teachhydrogen/view/822535/
 [6]: http://fotki.yandex.ru/users/teachhydrogen/view/822545/
 [7]: http://fotki.yandex.ru/users/teachhydrogen/view/589704/
 [8]: http://fotki.yandex.ru/users/teachhydrogen/view/589897/