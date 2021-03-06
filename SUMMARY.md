# Table of contents

* [4. СОЗДАНИЕ МОДЕЛИ URDF ДЛЯ ВАШЕГО РОБОТА.](README.md)
* [ros by example vol 2 indigo.pdf](ros-by-example-vol-2-indigo.pdf.md)
* [4.1 Начнем с базы и колёс](4.1-nachnem-s-bazy-i-kolyos/README.md)
  * [4.1.1 Узлы robot\_state\_publisher и joint\_state\_publisher.](4.1-nachnem-s-bazy-i-kolyos/4.1.1-uzly-robot_state_publisher-i-joint_state_publisher..md)
  * [4.1.2 Базовый файл URDF / Xacro.](4.1-nachnem-s-bazy-i-kolyos/4.1.2-bazovyi-fail-urdf-xacro..md)
  * [4.1.3 Альтернативное использование /base\_footprint frame.](4.1-nachnem-s-bazy-i-kolyos/4.1.3-alternativnoe-ispolzovanie-base_footprint-frame..md)
  * [4.1.4 Добавление базы к модели робота.](4.1-nachnem-s-bazy-i-kolyos/4.1.4-dobavlenie-bazy-k-modeli-robota..md)
  * [4.1.5 Просмотр дерева трансформации робота.](4.1-nachnem-s-bazy-i-kolyos/4.1.5-prosmotr-dereva-transformacii-robota..md)
  * [4.1.6 Использование сетки для базы.](4.1-nachnem-s-bazy-i-kolyos/4.1.6-ispolzovanie-setki-dlya-bazy..md)
* [4.2 Упрощение ваших meshes](4.2-uproshenie-vashikh-meshes.md)
* [4.3 Добавление туловища](4.3-dobavlenie-tulovisha/README.md)
  * [4.3.1 Моделирование туловища](4.3-dobavlenie-tulovisha/4.3.1-modelirovanie-tulovisha.md)
  * [4.3.2 Прикрепление туловища к основанию.](4.3-dobavlenie-tulovisha/4.3.2-prikreplenie-tulovisha-k-osnovaniyu..md)
  * [4.3.3 Использование сетки для туловища.](4.3-dobavlenie-tulovisha/4.3.3-ispolzovanie-setki-dlya-tulovisha..md)
  * [4.3.4 Добавление сетчатого туловища к сетчатому основанию](4.3-dobavlenie-tulovisha/4.3.4-dobavlenie-setchatogo-tulovisha-k-setchatomu-osnovaniyu.md)
* [4.4 Измерение, расчет и корректировка](4.4-izmerenie-raschet-i-korrektirovka.md)
* [4.5 Добавление камеры](4.5-dobavlenie-kamery/README.md)
  * [4.5.1 Размещение камеры](4.5-dobavlenie-kamery/4.5.1-razmeshenie-kamery.md)
  * [4.5.2 Моделирование камеры](4.5-dobavlenie-kamery/4.5.2-modelirovanie-kamery.md)
  * [4.5.3 Добавление камеры к туловищу и основанию](4.5-dobavlenie-kamery/4.5.3-dobavlenie-kamery-k-tulovishu-i-osnovaniyu.md)
  * [4.5.4 Просмотр дерева преобразований с туловищем и камерой](4.5-dobavlenie-kamery/4.5.4-prosmotr-dereva-preobrazovanii-s-tulovishem-i-kameroi.md)
  * [4.5.5 Использование сетки для камеры](4.5-dobavlenie-kamery/4.5.5-ispolzovanie-setki-dlya-kamery.md)
  * [4.5.6 Использование Asus Xtion Pro вместо Kinect](4.5-dobavlenie-kamery/4.5.6-ispolzovanie-asus-xtion-pro-vmesto-kinect.md)
* [4.6 Добавление лазерного сканера \(или других датчиков\)](4.6-dobavlenie-lazernogo-skanera-ili-drugikh-datchikov/README.md)
  * [4.6.1 Моделирование лазерного сканера](4.6-dobavlenie-lazernogo-skanera-ili-drugikh-datchikov/4.6.1-modelirovanie-lazernogo-skanera.md)
  * [4.6.2 Подключение лазерного сканера \(или другого датчика\) к сетчатому основанию](4.6-dobavlenie-lazernogo-skanera-ili-drugikh-datchikov/4.6.2-podklyuchenie-lazernogo-skanera-ili-drugogo-datchika-k-setchatomu-osnovaniyu.md)
  * [4.6.3 Настройка файла запуска лазерного узла](4.6-dobavlenie-lazernogo-skanera-ili-drugikh-datchikov/4.6.3-nastroika-faila-zapuska-lazernogo-uzla.md)
* [4.7 Добавление головки панорамирования и наклона](4.7-dobavlenie-golovki-panoramirovaniya-i-naklona/README.md)
  * [4.7.1 Использование Asus Xtion Pro вместо Kinect](4.7-dobavlenie-golovki-panoramirovaniya-i-naklona/4.7.1-ispolzovanie-asus-xtion-pro-vmesto-kinect.md)
  * [4.7.2 Моделирование поворотно-наклонной головки](4.7-dobavlenie-golovki-panoramirovaniya-i-naklona/4.7.2-modelirovanie-povorotno-naklonnoi-golovki.md)
  * [4.7.3 Вычисление осей вращения](4.7-dobavlenie-golovki-panoramirovaniya-i-naklona/4.7.3-vychislenie-osei-vrasheniya.md)
  * [4.7.4 Головка для панорамирования и наклона с помощью сеток на Pi Robot](4.7-dobavlenie-golovki-panoramirovaniya-i-naklona/4.7.4-golovka-dlya-panoramirovaniya-i-naklona-s-pomoshyu-setok-na-pi-robot.md)
  * [4.7.5 Использование сетки Asus Xtion Pro вместо кинекта на пи-роботе.](4.7-dobavlenie-golovki-panoramirovaniya-i-naklona/4.7.5-ispolzovanie-setki-asus-xtion-pro-vmesto-kinekta-na-pi-robote..md)
* [4.8 Добавление одного или двух рук](4.8-dobavlenie-odnogo-ili-dvukh-ruk/README.md)
  * [4.8.1 Размещение руки \(рук\)](4.8-dobavlenie-odnogo-ili-dvukh-ruk/4.8.1-razmeshenie-ruki-ruk.md)
  * [4.8.2 Моделирование руки](4.8-dobavlenie-odnogo-ili-dvukh-ruk/4.8.2-modelirovanie-ruki.md)
  * [4.8.3 Добавление рамы захвата, запрещающей планирование](4.8-dobavlenie-odnogo-ili-dvukh-ruk/4.8.3-dobavlenie-ramy-zakhvata-zapreshayushei-planirovanie.md)
  * [4.8.4 Добавление второй руки](4.8-dobavlenie-odnogo-ili-dvukh-ruk/4.8.4-dobavlenie-vtoroi-ruki.md)
  * [4.8.5 Использование сеток для рычажных сервоприводов и кронштейнов](4.8-dobavlenie-odnogo-ili-dvukh-ruk/4.8.5-ispolzovanie-setok-dlya-rychazhnykh-servoprivodov-i-kronshteinov.md)
* [4.9 Добавление телескопического туловища к бокс-роботу](4.9-dobavlenie-teleskopicheskogo-tulovisha-k-boks-robotu.md)
* [4.10 Добавление телескопического туловища к Pi-роботу](4.10-dobavlenie-teleskopicheskogo-tulovisha-k-pi-robotu.md)
* [4.11 Настольный робот-манипулятор 1-Arm Pi](4.11-nastolnyi-robot-manipulyator-1-arm-pi.md)
* [4.12 Тестирование вашей модели с помощью ArbotiX Simulator](4.12-testirovanie-vashei-modeli-s-pomoshyu-arbotix-simulator/README.md)
  * [4.12.1 Фальшивый коробчатый робот.](4.12-testirovanie-vashei-modeli-s-pomoshyu-arbotix-simulator/4.12.1-falshivyi-korobchatyi-robot..md)
  * [4.12.2 Фальшивый Пи Робот.](4.12-testirovanie-vashei-modeli-s-pomoshyu-arbotix-simulator/4.12.2-falshivyi-pi-robot..md)
* [4.13 Создание вашего собственного пакета описания робота](4.13-sozdanie-vashego-sobstvennogo-paketa-opisaniya-robota/README.md)
  * [4.13.1 Использование rosbuild](4.13-sozdanie-vashego-sobstvennogo-paketa-opisaniya-robota/4.13.1-ispolzovanie-rosbuild.md)
  * [4.13.2 Using catkin](4.13-sozdanie-vashego-sobstvennogo-paketa-opisaniya-robota/4.13.2-using-catkin.md)
  * [4.13.3 Копирование файлов из пакета rbx2\_description](4.13-sozdanie-vashego-sobstvennogo-paketa-opisaniya-robota/4.13.3-kopirovanie-failov-iz-paketa-rbx2_description.md)
  * [4.13.4 Создание файла тестового запуска](4.13-sozdanie-vashego-sobstvennogo-paketa-opisaniya-robota/4.13.4-sozdanie-faila-testovogo-zapuska.md)

