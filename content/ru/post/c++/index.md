---
title: Кому и для чего нужен C++
subtitle: Кому и для чего нужен C++

# Summary for listings and search engines
summary: Кому и для чего нужен C++

# Link this post with a project
projects: []

# Date published
date: '2020-03-13T00:00:00Z'

# Date updated
lastmod: '2020-03-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [Git](https://leader-id.storage.yandexcloud.net/upload/3077661/cb3860f7-05a7-4012-9020-574087a10e3f.jpg)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Доклады

categories:
  - post 5
---

# Кратчайшая история создания C++

Первые версии языка C++ (си-плюс-плюс, еще его называют «си-пи-пи» и «плюсы») появились в начале 1980-х годов. Их создатель — датский программист из компании Bell Laboratories Бьерн Страуструп. Он моделировал распределения вызовов по АТС (автоматическим телефонным станциям).

Тогда у Страуструпа было два типа языков: низкоуровневые и языки на основе Фортрана или Алгола, которые были очень медленными.

Низкоуровневые языки дают полный контроль над ресурсами компьютера: процессором, памятью, периферийными устройствами. Но в таких языках мало готовых инструментов, а значит, любые сложные концепции и функции придется кодить самостоятельно. В языках высокого уровня уже есть все необходимые абстракции.

Страуструп объединил возможности объектно-ориентированного С и языка Simula, основанного на Алголе. Главное привнесенное в C новшество — классы, основной элемент в объектно-ориентированном программировании, содержащий в себе данные и код, который ими управляет.

Так появился «‎C с классами»‎ или «‎новый C»‎, который в 1983 году получил свое окончательное название — C++. «++» — это оператор, который означает «добавить единицу». То есть к возможностям языка C добавили еще одну.

# Основные области использования C++

* разработка игр и игровых движков (Unreal Engine, Unity);
* GPU-вычисления (cryptocurrency, deep learning);
* разработка высоконагруженных и высокопроизводительных приложений.

C++ — производительный язык, он помогает дорожным картам в GPS не тупить и строить оптимальные маршруты, любимым играм — не лагать и выдавать максимальное качество с выкрученными до предела настройками графики, банковским сервисам — быть круглосуточными, а переводам — моментальными.

Производительность — важная характеристика любой компьютерной игры. Counter-Strike, StarCraft: Brood War, Diablo I, World of Warcraft — все они появились давно и были написаны на C++, как и операционные системы консолей Xbox и PlayStation, ядра популярных игровых движков Unreal Engine или Unity, на базе которых сделано огромное количество 3D-игр, симуляторов, шутеров и стратегий.

Все потому, что на C++ можно использовать объектно-ориентированное программирование, а когда понадобится — обратиться к низкоуровневым возможностям языка, позволяющим хорошо оптимизировать игру под конкретные платформы и очень эффективно производить расчеты для графики. По этой же причине C++ применяется в графических редакторах (Adobe Photoshop).

Благодаря распараллеливанию (одновременному выполнению большого количества несложных математических операций) язык подходит для биткоинов и нейросетей. Первые можно майнить на C++, вторые — обучать: большинство библиотек для глубокого обучения (TensorFlow, Caffe, Shogun, Pytorch C++ API и т.д.) используют C++-код CUDA и OpenCL.

C++ незаменим для высоконагруженных приложений, его используют для разработки поисковых движков, роботов торговых бирж, систем управления базами данных и маршрутизации сетевого трафика.

С помощью C++ Mozilla Corporation разработала opensource-браузер Firefox, была создана Amadeus — система электронного бронирования авиабилетов, гостиниц, круизных туров и проката автомобилей (через нее проходит 5000 транзакций в секунду, более миллиарда транзакций ежедневно), благодаря C++ работают Яндекс.Поиск и поисковый движок Google.

**C++ нужен не только программистам, но и:**

* техническим художникам: связующему звену между обычными художниками и 3D-моделистами на игровом проекте и разработчиками игрового движка (у которых очень популярен C++) для решения проблем необходимо разбираться в языке и понимать, как все запрограммировано;

* математикам: такие типовые задачи вычислительной математики, как решение систем алгебраических уравнений, дифференцирование и интегрирование функций, оптимизация, интерполяция, экстраполяция и аппроксимация, решаются при помощи реализаций численных методов на C++;

* физикам и химикам: на C++ моделируются среды и физические процессы;

* музыкантам: да, даже им! Это могут быть исследования акустических эффектов, попытки формализации творческого процесса или даже создание музыки: на «‎алгорейвах»‎ люди зажигают под треки, генерируемые алгоритмами, которые вживую на сцене пишет диджей-программист, — вот это настоящий киберпанк.


**А еще C++ — это круто, потому что с его помощью:**

* пишут критическое ПО для истребителей F-16 и F-35;

* разрабатывают пакеты программ и библиотек ROOT для обработки экспериментальных данных физики высоких энергий;

* по поверхности Марса самостоятельно ездят роверы NASA и летает телескоп Хаббл;

* делает практически все Microsoft (Windows OS, пакет Office, Internet Explorer, Visual Studio);

* творят искусство (генеративное) художники: пишут алгоритмы для генерации предметов живописи и скульптур.

# Плюсы и минусы языка

## Плюсы

* Высокая производительность, потому что он не накладывает никакой избыточной нагрузки на программу, не использующую какие-либо возможности.

* Поддержка множества стилей программирования (процедурное программирование, абстракцию данных, объектно-ориентированное программирование и обобщенное программирование). Поэтому разработчик может сам выбрать, в каком стиле ему писать программу.

* Большое сообщество.

## Минусы

Высокий порог входа. Решения об изменениях в C++ принимают на заседаниях комитета, участие в которых формально может принять любой разработчик. Но отправляться на такие собрания в другую страну за свой счет трудно, поэтому большинство участников — представители крупных IT-корпораций, таких как Google, Яндекс. А вот представителей интересов студентов или стартапов немного. Поэтому эксперты могут принять концепции, которые им кажутся очевидными, а для остальной аудитории они будут сложными.

# Спасибо за внимание!

