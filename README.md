Автор студент групи АК 3-2ск Андрієнко Даниїл 
Kursova
=======
Курсова робота на тему: "Розробка системи розумний будинок" 

  Розробники проекту студенти групи АК3-2ск

-Андрієгнко Даниїл Вікторович

-Хом'яков Станіслав Вікторович

-Квотченко Дмитро Олександрович

Фото розробленої моделі емуляції розумного дому:
![IMG_20220423_173816](https://user-images.githubusercontent.com/68506045/164910794-6a57ccce-0eff-4682-8826-38ed5a88d3d1.jpg)
![IMG_20220423_173909](https://user-images.githubusercontent.com/68506045/164910801-55852166-4360-4756-b9bd-6fe1d860848d.jpg)
В даному репозиторії буде розказано про під'єднання мікроконтролерів типу ардуіно до програмного забезпечення node-red.
Для початку неохідно встановити розширення для node-red інструкцію про те як це зробити можна знайти на сайті https://wikihandbk.com/wiki/Node-RED:%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5/%D0%92%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D0%B5_%D1%81_Arduino.
На цьому ж сайті розказано про те як змінити прошивку ардуіно. Якщо у Вас відсутній драйввер для завнтажте його можна завантажити за наступним посиланням http://wiki.amperka.ru/articles:driver-ch340. 
Після інсталювання драйверу підключіть Вашу плату до комп'ютеру та відкрийте диспетчер устройств у пункті Порты (СОМ и LT) понна відобразитись ваша плата як показано на рисунку. 
![image](https://user-images.githubusercontent.com/68506045/154534261-07a6d666-0904-4e37-a19f-7c753851f110.png)
Після чого необхідно зайти в arduino IDE та змінити прошивку завантажити arduino IDE можна за посиланням https://www.arduino.cc/en/software також можна скористаттись онлайн застосунком https://login.arduino.cc/login?state=hKFo2SBtMzNxa01tVVhUekNoN09oeTdyQ0FCUlFEaW9acThmX6FupWxvZ2luo3RpZNkgUFpfWTdDNFlUMDFTcWtuNEdScnM0bUtDV0dITThYT1SjY2lk2SBycjZMU09TejU3aDdmdnNIZFJYWFBrWkczRVJvWFRmWg&client=rr6LSOSz57h7fvsHdRXXPkZG3ERoXTfZ&protocol=oauth2&authorizeTimeoutInSeconds=5&redirect_uri=https%3A%2F%2Fcreate.arduino.cc%2Feditor&logout_uri=https%3A%2F%2Fcreate.arduino.cc&audience=https%3A%2F%2Fapi.arduino.cc&scope=openid+profile+email&response_type=code&response_mode=query&nonce=RFBndmVsYVNDRG5kVkpMWElMTUtEYl9CcGRJVFdaT0FnWlJnUzRaUERUcw%3D%3D&code_challenge=bnfdl75H1F125HZ4iELqBKTSZxdTOQu3kNB_Lq-dHtg&code_challenge_method=S256&auth0Client=eyJuYW1lIjoiYXV0aDAtc3BhLWpzIiwidmVyc2lvbiI6IjEuMTIuMSJ9#/sso/login після того як все налаштовано можна почати розробляти застосунок про те мені не вдалося реалізувати керування аналоговими виходами. У налаштуваннях нод потрібно вказати порт відповідної плати та тип входу або виходу після команди Deploy connected повинен бути зеленим як показано на рисунку. 
![image](https://user-images.githubusercontent.com/68506045/154535669-5ce07f8f-c2b4-4c1f-ba52-721dd813aadb.png)
 При роботі з ардуіно виникає проблеба з аналоговими виходами в мене не вийшло реалізувати керування ними тобто на сам вихід програмно я сигнал подаю а фізично він завжди дорівнює нулю, як вирішити дану проблему я не знаю та маю надію, що мені допоможуть її вирішити.
