---
title: 'Writeup_First_CTF'
authors: [Avigdor]
date: 2023-11-23 00:00:00 +0000
categories: [CTF, My_Dev]
tags: [CTF]
---

![](/images_for_writeup_first_ctf/Pasted image 20231122122538.png)
![](/images_for_writeup_first_ctf/Pasted image 20231122122611.png)
![](/images_for_writeup_first_ctf/Pasted image 20231122122642.png)
![](/images_for_writeup_first_ctf/Pasted image 20231122122700.png)
![](/images_for_writeup_first_ctf/Pasted image 20231122122948.png)
![](/images_for_writeup_first_ctf/Pasted image 20231122123008.png)
![](/images_for_writeup_first_ctf/Pasted image 20231122123327.png)

- Проводим OSINT-аналитику и находим некого Edward E. lacobucci, сооснователя CITRIX, что наводит на мысль об CITRIX CTX1 Cipher

> Флаг Аргентины, откуда родом Edward E. lacobucci

Вспоминаем об hint2:

![](/images_for_writeup_first_ctf/Pasted image 20231122123130.png)

Берем пароль, которые расшифровали в начале и распаковываем flag.war:

![](/images_for_writeup_first_ctf/Pasted image 20231122123239.png)

![](/images_for_writeup_first_ctf/Pasted image 20231122123411.png)

> Звезда (напоминающая звезду Давида) в синих цветах, всё в традициях **Израиля**

![](/images_for_writeup_first_ctf/Pasted image 20231122123455.png)

![](/images_for_writeup_first_ctf/Pasted image 20231122123531.png)

- Улыбнулись и пошли дальше

Видим ещё одну зашифрованную строку:

![](/images_for_writeup_first_ctf/Pasted image 20231122123700.png)

Выглядит странно, непонятно как расшифровать, но напоминает url-адрес

> Копаем дальше, не забываем про матрёшку (Намек на стегу) !

![](/images_for_writeup_first_ctf/Pasted image 20231122123849.png)

Жёстко осинтим:

![](/images_for_writeup_first_ctf/Pasted image 20231122124017.png)

![](/images_for_writeup_first_ctf/Pasted image 20231122124032.png)

![](/images_for_writeup_first_ctf/Pasted image 20231122124044.png)

Моссад, а корректнее MOSSAD (ибо было написано на английском "ENTER CAPS")

Берём строку, которую не знали как расшифровать и перебираем основные полиалфавитные шифры, натыкаемся на господина Виженера:

![](/images_for_writeup_first_ctf/Pasted image 20231122124318.png)

![](/images_for_writeup_first_ctf/Pasted image 20231122124337.png)

![](/images_for_writeup_first_ctf/Pasted image 20231122124347.png)

> Смотрим историю коммитов

![](/images_for_writeup_first_ctf/Pasted image 20231122124401.png)

# WIN!