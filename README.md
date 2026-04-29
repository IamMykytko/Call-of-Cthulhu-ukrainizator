# Call of Cthulhu (Поклик Ктулгу) - українізатор
Український текстовий фанатський переклад гри "Call of Cthulhu" (2018) від команди "ПерекLand".

![alt text](https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator/blop/main/src/call-of-cthulhu.jpeg?raw=true)

*Зміст README:*
1. [Гайд як встановити переклад](#гайд-як-встановити-переклад)
2. [Наші соціальні мережі та інші лінки](#наші-соціальні-мережі-та-інші-лінки)
3. [Історія створення та післяслово](#історія-створення-та-післяслово)
4. [Скріншоти](#скріншоти)
5. [Підтримати команду за переклад :)](#підтримати-команду-за-переклад)

---
# Гайд як встановити переклад
- **Для Windows 11:**
	- Завантажуйте `pakchunk27-WindowsNoEditor.pak` з репозиторію (якщо ви на GitHub) або з іншого джерела;
	- *Або:* Зайдіть у бібліотеку вашого Steam, знайдіть Call of Cthulhu, натисніть на шестерню справа гри > `Управління` > `Локальні файли` і у вас відкриється потрібна тека гри. Якщо ж ви не знаходите таку опцію в налаштуваннях всередині Steam, то виконайте наступний крок нижче..
	- *Або:* Знайдіть папку, де встановлений ваш Steam-клієнт. Перейдіть за наступним шляхом до гри `*локація-steam*\steamapps\common\Call of Cthulhu`. Тепер ви у потрібній теці гри;
	- Перейдіть за наступним шляхом: `Content\Paks` (у когось може бути `Cya\Content\Paks`). Встановіть у цій теці наш `pakchunk27-WindowsNoEditor.pak`;
	- Готово! Запускайте та насолоджуйтесь грою на українській мові! 🥳
- **Для Linux:**
	- Загалом, те саме, що і для Windows 11 в частині інструкцій, просто трошки з іншими відозміненнями: замість `\` у Linux та інших Unix-подібних ОС використовується `/` для папок, тому НЕ `*локація-steam*\steamapps\common\Call of Cthulhu`, а `*локація-steam*/steamapps/common/Call of Cthulhu`. Зазвичай локація розташування Steam знаходиться у вашій домашній теці: `/home/*ваш-юзер*/.local/share/Steam`. Більше відмінностей в інсталяції українізатора нема.
	- Порада щодо вибору **спеціального інструменту сумісності Proton**, то для Call of Cthulhu використовуйте Proton версії 6.3-8 і гра буде працювати відмінно! *(лише може на панелі задач іконка може відображатись трошки некоректно, але це не суттєво)* 🐧
- **Для MacOS:** *(інструкція поки відсутня, але скоріш за все, ідентично до інших ОС)*

*Де скачать pak з перекладами?*
- LBK Launcher: https://lbklauncher.com/games/call_of_cthulhu_2018
- КУЛІ: *(наразі відсутня сторінка)*
- GitHub: https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator або https://github.com/DiD0LEKSA/CoCUA-public-
- Google Drive: https://drive.google.com/drive/folders/1Zm4mnHBUnIcgi1y00T2xXG_ONuSLU7Oo?usp=sharing

---
# Наші соціальні мережі та інші лінки
- *Discord-сервера:*
	- IamMykytko: https://discord.com/invite/RGZvu8AGZD
	- Козацьке Господарство: https://discord.gg/Dzspar8Hnh
- *YouTube-канали:*
	- IamMykytko: https://www.youtube.com/@iammykytko
	- DID OLEKSA: https://www.youtube.com/@did_oleksa_15
	- 4LC0MAN: https://www.youtube.com/@4LC0M4N
	- Gold Flin: https://www.youtube.com/@gold_flin
- *Instagram-профілі:*
	- IamMykytko: https://www.instagram.com/iammykytko/
- *Steam-посібник:* https://steamcommunity.com/sharedfiles/filedetails/?id=3462038170
- *GitHub-профілі:* 
	- IamMykytko: https://github.com/IamMykytko
	- DID OLEKSA: https://github.com/DiD0LEKSA
	- 4LC0M4N: https://github.com/KYMIBHA
	- gold_flin: https://github.com/Goldflin16
- *LinkedIn-сторінки:*
	- IamMykytko: https://www.linkedin.com/in/iammykytko/
- *Сторінки нашого українізатора:*
	- LBK Launcher: https://lbklauncher.com/games/call_of_cthulhu_2018
	- КУЛІ: *(наразі відсутня сторінка)*
	- GitHub: https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator або https://github.com/DiD0LEKSA/CoCUA-public-

---
# Історія створення та післяслово
Ми дуже довго займались цим перекладом в силу того, що це наш перший подібний проєкт, були масові відключення світла та купу різних технічних питань. Цю гру запропонував перекласти Сашко, та разом з Олексою вони шукали спосіб вирішення технічного питання "як знайти файли для локалізації і як їх перекласти для коректної роботи української в грі?"

Потім вже до цієї роботи доєднався Микита та він вклав свій внесок у вирішення технічого питання, навчивши решту хлопаків використовувати VS Code з тоді ще тільки-но доданим ШІ-агентом Copilot (задля швидкого перекладу чи перевірки якості перекладу), а також навчив решту користуватись Git та GitHub.

Всі ми четверо друзів (Олекса, Микита, Саша та Іван) займались цим перекладом, і на фіналі завершення цього проєкту Олексі та Сашкові запропонували допомогти з перекладом Batman Arkham Knight, тому вони були відсутні деякий час, а потім почалась вся ця історія з відключеннями світла, масовими бомбардуваннями наших міст, тому наш переклад відсрочився на пів року десь, але ми все ж завершили його, попри те, що половина команди тепер відсутня через службу у війську.

Ми думали як Ви можете підтримати нас, думали відкрити нашу власну банку, проте дійшли до згоди, що найкращим нам варіантом буде, якщо Ви задонатите на який-небудь фонд (не важливо який, головне - щоб допоміг війську).

---
# Скріншоти
Ми прикріпимо декілька скріншотів, щоб ви побачили як виглядає українізатор:
![alt text](https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator/blop/main/src/items1.jpg?raw=true)
![alt text](https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator/blop/main/src/main-menu1.jpg?raw=true)
![alt text](https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator/blop/main/src/main-menu2,jpg?raw=true)
<!--![alt text](https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator/blop/main/src/*?raw=true)
![alt text](https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator/blop/main/src/*?raw=true)
![alt text](https://github.com/IamMykytko/Call-of-Cthulhu-ukrainizator/blop/main/src/*?raw=true)-->

---
# Підтримати команду за переклад
Підтримати нас можна донатом на військо, чому ми всі одностайно будемо раді! Малі чи великі донати - неважливо, головне продовжувати допомагати війську! Ми залишили посилання на ті фонди, яким довіряємо:
- Rusoriz: https://send.monobank.ua/jar/2JbpBYkhMv
- Фонд Сергія Притули: https://send.monobank.ua/jar/2AwsVyDJ6Q
- Симороз: https://t.me/OlehSymoroz
- Фонд "Повернись живим": https://savelife.in.ua/donate/#donate-army-card-once

---
> **Дякую за використання нашого перекладу!** Пориньте у безумство та божевілля всесвіту Лавкрафта 🐙
