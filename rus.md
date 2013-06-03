# Кнопки в сторону: обзор интерфейсов с жестовым управлением

Наверняка дизайнеры пользовательских интерфейсов и UX-дизайнеры помнят запуск 
первого iPhone от Apple так будто бы это было вчера. Кроме всего прочего, он 
стал первым персональным устройством с полностью **сенсорным взаимодействием**. 
Его выпуск стал переломным моментом в истории интерфейсов.

Сегодня дети чуть ли не с пелёнок окружены сенсорными устройствами и 
воспринимают их как нечто абсолютно естественное. Родители поражаются насколько 
быстро их дети разбираются как работает планшет или смартфон. Это подтверждает 
что касания и жесты обладают огромным потенциалом и могут сделать взаимодействие 
с мобильными устройствами намного проще и интереснее. 

## Испытание кнопками и панелями меню

«Рекомендации по пользовательским интерфейсам» и комиссия Apple по контролю 
приложений значительно повлияли на качество мобильных приложений. Они помогли 
многим дизайнерам и разработчикам понять принцип работы ключевых элементов и 
взаимодействий интерфейса. Например, многие из нас, и я в их числе, следовали 
одной из общеизвестных рекомендаций Apple использовать компоненты [UITabBar][1] 
и [UINavigationBar][2].

Кстати, если вы можете искренне утверждать что в вашем первом приложении для 
iPhone не было никаких панелей меню в верхней или нижней части экрана, пришлите 
мне скриншот. Я угощу вас пивом и почту за честь сообщить всем своим подписчикам 
в Твитере что вы опередили своё время.

Главный изъян моих панелей меню, расположенных в верхней или в нижней части 
экрана, в том что они занимают почти 20% экрана. Работая над проектом для 
небольших областей просмотра, мы должны **посвятить каждый пиксель контенту**. В 
конце концов, именно контент имеет наибольшее значение для пользователя.

В этой инновационной индустрии дизайнерам мобильных приложений нужно некоторое 
время чтобы научиться проектировать более креативные и нестандартные интерфейсы. 
Если также принимать во внимание странную манеру команды Apple отвергать 
приложения которые выходят за рамки шаблонов, не удивительно что проекты с 
экспериментальным вариантом дизайна такие как [Clear][3] и [Rise][4] прошли 
долгий путь до выхода в свет. Но они все-таки были запущены. И несмотря на всю 
свою необычность и удобство пока только для продвинутых пользователей, они 
свидетельствуют о громадном потенциале интерфейсов с жестовым управлением.

![Rise и Clear][Скриншоты приложений с жестовым управлением Rise и Clear]

*Действие «потянуть вниз чтобы обновить» кажется очень естественным*

## Возможности интерфейсов с жестовым управлением

Уже более двух лет я занимаюсь изучением влияния жестового управления на 
качество и удобство взаимодействия пользователя с мобильными приложениями. 
Наиболее важным критерием для меня является **максимальная интуитивность 
действий**. Именно благодаря интуитивности такие действия как «потянуть вниз 
чтобы обновить», предложенное Лорен Брихтер (Loren Brichter), в два счета стали 
нормой. Действие, придуманное Брихтер для программы Tweetie под iPhone, 
оказалось настолько удобным, что оно было позаимствовано несчётным количеством 
приложений, которые организованы в виде списков. 

### Избавляемся от нагромождения элементов

Лучшим способом начать проектировать интерфейсы с жестовым управлением будет 
использовать пространство на экране только для представления главного контента. 
**Не думайте что главная навигация должна быть постоянно на виду**. Вместо этого 
придумайте для неё какое-то другое расположение. С точки зрения виртуальной 2-D 
или 3-D среды, навигацию можно расположить в разных местах относительно области 
просмотра: рядом с ней, под или над ней, позади или спереди неё или же 
спрятанной в её верхней части. Прекрасным решением будет вызов этого элемента 
интерфейса с помощью жеста перетаскивания или свайпа в сторону. Это уже вам 
решать при разработке приложения.

К примеру, мне нравится реализация меню со свайпом в сторону на Facebook и Gmail 
для iOS. Эту актуальную концепцию очень просто использовать. Пользователи 
проводят пальцем вправо по области просмотра чтобы вывести элементы навигации. 
Это не только освобождает пространство  в пользу контента, но и обеспечивает 
доступность любой части приложения в два или три касания. У многих приложений 
дела обстоят намного хуже!

![Меню со свайпом в сторону][Меню со свайпом в сторону на Facebook и Gmail]

*Меню со свайпом в сторону на Facebook и Gmail*

Кроме навигации ваше приложение наверняка поддерживает контекстные 
взаимодействия. Добавление одних и тех же двух или трёх кнопок под каждым блоком 
контента несомненно загромождает интерфейс. Хотя кнопки и кажутся полезным 
механизмом запуска событий, жесты могут **сделать взаимодействие с контентом 
намного более интуитивным и интересным**. Для ключевых взаимодействий не 
колеблясь интегрируйте простые жесты, такие как касание, двойное касание, 
касание и удерживание пальца. Instagram поддерживает простое двойное касание для 
выполнения одного из ключевых действий: создание и удаление ссылки для элемента 
контента. Не удивлюсь если и другие приложения в скором времени начнут 
использовать такой приём. 

### Подходящий интерфейс

Иногда в процессе разработки инновационного мобильного продукта довольно сложно 
предугадать поведение пользователя. Работая над приложением для бельгийской 
радиостанции, моя команда приложила все усилия чтобы добиться баланса между 
визуализацией музыки и предоставлением новостей в режиме реального времени. 
Огромный выбор контекстных сценариев и диапазон предпочтений пользователей 
значительно усложнили создание идеального интерфейса. Мы решили интегрировать 
простой жест перетаскивания, который даёт пользователям возможность настроить 
вид интерфейса по своему усмотрению. 

![Radio+][Примеры соотношения элементов в интерфейсе Radio+]

*Пользователи могут перетаскивать элементы музыкального и новостного контента 
чтобы подкорректировать их соотношение*

Этот жест придаёт приложению некий момент созидания. Используя жест 
перетягивания, пользователь не перемещается из одного раздела (музыкального или 
новостного) в другой. Вместо этого он получает возможность сосредоточить своё 
внимание на контенте, который его в данный момент интересует больше, и 
продолжать следить за обновлением остального контента.

### Сосредоточьтесь на скорости, размерах и анимации

Что происходит когда пользователь касается элемента? Как визуально 
подтверждается выполнение действия? Как быстро осуществляется анимация 
появления конкретного элемента в области просмотра? Исчезает ли он из поля зрения
автоматически после нескольких секунд неактивности?

Появление сенсорных устройств сильно **изменило наш подход к проектированию 
взаимодействий.** Вместо страниц и экранов, мы сосредотачиваем своё внимание на 
скорости, размерах и анимации. Вы должно быть заметили что настроить 
взаимодействия пользователя и продемонстрировать их сотрудникам и клиентам 
используя статические скриншоты макета непросто. Они не дают полное 
представление о том, что произойдет при касании, продолжительном касании, 
перетаскивании или свайпе элементов. 

Некоторые инструменты создания прототипов, в том числе [Pop][6] и [Invision][7], 
помогут оживить макет. Они очень удобны для тестирования работы приложения и 
**выявления действий, которые могут завести пользователя в тупик**. Работа 
приложения не сводится лишь к навигации между элементами, потому ошибки в работе 
интерфейса и потенциальные причины для дезориентации нужно выявить как можно 
скорее. Не очень приятно когда на них указывают ваши коллеги по команде на 
стадии демонстрации, не так ли?

![InvisionApp][Invision позволяет импортировать и соединять ваши макеты]

*Invision позволяет импортировать и соединять ваши макеты*

Проявите стремление к инновациям: перед тем как приступать к работе, встретьтесь 
с вашим заказчиком и объясните ему что традиционные макеты не дают полное 
представление о будущей работе приложения. Расскажите о преимуществах 
интерактивных макетов и убедите его включить их разработку в процесс разработки 
приложения. Это вероятно увеличит продолжительность разработки и бюджет, но если 
заказчик рассчитывает на максимальное усердие с вашей стороны, это не должно 
стать проблемой.

Иногда я даже предлагаю клиентам подготовить видео-презентацию концепции 
интерфейса. Ведь после ознакомления с интерактивными макетами и изучения всех 
нюансов, им часто нужна более красивая презентация, которую можно показать 
влиятельным людям в компании. 

## Скорость обучения пользователей

Проектируя жестовые взаимодействия, помните что по мере избавления от 
нагромождения элементов интерфейса, скорость, с которой пользователи смогут 
освоиться в приложении, растет. Без визуальных подсказок пользователи могут не 
догадаться как взаимодействовать с приложением. Не страшно если пользователю 
придется провести самостоятельное изучение возможностей приложения, но он должен 
знать с чего начать. При первом запуске многих приложений пользователь видит 
пошаговое руководство и [я согласен с Максом Рудбергом][8] что **пошаговые 
руководства должны объяснять только базовые взаимодействия**. Не нужно объяснять 
всё сразу. Если руководство слишком запутанное и длинное, пользователи его 
пропустят. 

 Можно немного усложнить свою задачу и предложить интересные подсказки, которые 
 будут появляться постепенно в процессе использования приложения. Такую схему 
 часто называют методом последовательного раскрытия, она является отличным 
 способом выводить на экран только ту информацию, в которой на данной стадии 
 работы нуждается пользователь. Приложение Capture от YouTube, например, выдает 
 подсказку что пользователю нужно повернуть устройство в горизонтальное 
 положение в тот момент когда он впервые включает камеру. 

![Визуальные подсказки][Примеры визуальных подсказок]

*Оптимизируйте процесс обучения пользователя с помощью пошагового руководства 
и/или визуальных подсказок*

Добавление визуальных подсказок - это не единственный вариант. В приложении 
Sparrow при запуске на несколько секунд отображается панель поиска, которая 
затем скользит вверх и исчезает с экрана, намекая что её можно в любой момент 
вызвать, потянув область просмотра вниз. 

## Хватит разговоров, пора к делу

iPhone положил начало революции в интерактивном взаимодействии. Прошло только 
пять лет, а сенсорные устройства уже окружают нас повсюду и дизайнеры 
взаимодействий пересматривают способы взаимодействия людей с цифровым контентом.

Мы должны продолжать исследования, понимать что сенсорные устройства с жестовым 
управлением обладают огромным потенциалом и **сосредоточиться на скорости, 
размерах и анимации**. Как доказывают некоторые инновационные приложения, жесты - 
это отличный способ сделать приложение более сфокусированным на контенте, более 
оригинальным и интересным. И наконец, многие жестовые взаимодействия, которые на 
первый взгляд кажутся слишком непривычными, на деле оказываются очень 
интуитивными. 

Полный обзор возможностей жестов на всех крупных мобильных платформах 
представлен в работе «[Обзор справочных сведений по жестовым касаниям][9]». 
Надеюсь эта статья вдохновила вас на изучение жестовых взаимодействий и усилила 
интерес к миру мобильных интерфейсов. Не бойтесь прилагать больше усилий. 
Интерактивные макеты помогут вам в пути к максимально комфортному опыту работы с 
приложениями. Итак, хватит разговоров, пора браться за дело.

[1]: http://developer.apple.com/library/ios/#documentation/uikit/reference/UITabBar_Class/Reference/Reference.html
[2]: http://developer.apple.com/library/ios/#documentation/uikit/reference/UINavigationBar_Class/Reference/UINavigationBar.html
[3]: http://www.realmacsoftware.com/clear/
[4]: http://www.simplebots.co/
[5]: http://www.macstories.net/news/loren-brichter-talks-about-pull-to-refresh-patent-and-design-process/
[6]: http://popapp.in/
[7]: http://www.invisionapp.com/
[8]: http://blog.maxrudberg.com/post/38958984259/if-you-see-a-ui-walkthrough-they-blew-it
[9]: http://www.lukew.com/ff/entry.asp?1071

[Скриншоты приложений с жестовым управлением Rise и Clear]: img/riseclearapp_compr-rus.png
[Меню со свайпом в сторону на Facebook и Gmail]: img/sideswipe_compr.png
[Примеры соотношения элементов в интерфейсе Radio+]: img/radioplus_compr.png
[Invision позволяет импортировать и соединять ваши макеты]: img/invision_compr.png
[Примеры визуальных подсказок]: img/walkthroughdisclosure_compr-rus.png