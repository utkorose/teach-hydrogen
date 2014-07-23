---
title: Выбраны аудио-хостинг и хостинг для изображений
author: Администратор Сайта
layout: post
permalink: /phauhosting/
categories:
  - Новости сайта
---
Итак, поскольку сайт создаётся на бесплатном хостинге(ссылку на него ищите в правом нижнем углу сайта), ограничено место под контент. 50 мб выделяется хостером, при этом из них 30 уже забито. Поэтому встал вопрос &#8212; где хранить аудио файлы фонограмм ударных и скриншоты, которые будут использоваться для наглядности? Пока мой выбор пал на сервисы яндекса &#8212; яндекс-фотки:  
[<img title="" src="http://img-fotki.yandex.ru/get/4411/129199783.0/0_6714f_ef835be9_XS.jpg" alt="" width="76" height="78" border="0" />][1]  
[Посмотреть на Яндекс.Фотках][1]  
и яндекс-видео:



Идею с яндекс видео подбросили [здесь][2]:

На <a href="http://video.yandex.ru/" target="_blank">Я.видео</a> можно загружать аудио файлы. Но плеер остаётся как для видео. Из-за этого проблематично вывесить в одном посте несколько аудио файлов, слишком много места занимает всё это.  
Его надо просто уменьшить.

1. <a href="http://video.yandex.ru/upload" target="_blank">Загружаем на Я.видео</a> музыкальный файл.

2. Берём &#171;код для блога&#187;:

<pre>&lt;object width="450" height="<strong>370</strong>"&gt; 
&lt;param name="video" value="http://flv.video.yandex.ru/lite/anticipator/nv5w3ujj0g.4"&gt;
&lt;/param&gt; &lt;param name="allowFullScreen" value="true"&gt;
 &lt;/param&gt; &lt;param name="scale" value="noscale"&gt; &lt;/param&gt;
 &lt;embed src="http://flv.video.yandex.ru/lite/anticipator/nv5w3ujj0g.4"
 type="application/x-shockwave-flash" width="450"
 height="<strong>370</strong>" allowFullScreen="true" scale="<strong>noscale</strong>" &gt;
 &lt;/embed&gt; &lt;/object&gt;</pre>

3. Исправляем значения параметра height на 30 (вместо height=&#187;370&#8243; ставим height=&#187;30&#8243;).

4. После scale=&#187;noscale&#187; (почти в самом конце кода) прописываем salign=&#187;BL&#187;.

5. Полученный код ставим в тело поста в режиме &#171;просто текст&#187;.

<pre>&lt;object width="450" height="<strong>30</strong>"&gt; &lt;param name="video"  
value="http://flv.video.yandex.ru/lite/anticipator/nv5w3ujj0g.4"&gt;
 &lt;/param&gt; &lt;param name="allowFullScreen" value="true"&gt;
 &lt;/param&gt; &lt;param name="scale" value="noscale"&gt; &lt;/param&gt;
 &lt;embed src="http://flv.video.yandex.ru/lite/anticipator/nv5w3ujj0g.4"
 type="application/x-shockwave-flash" width="450" height="<strong>30</strong>"
 allowFullScreen="true" scale="<strong>noscale</strong>"<strong> salign="BL"</strong>&gt; &lt;/embed&gt; &lt;/object&gt;</pre>

И получаем узкую линейку проигрывателя.

&nbsp;

 [1]: http://fotki.yandex.ru/users/teachhydrogen/view/422223/
 [2]: http://www.ph4.ru/host_audio.ph4