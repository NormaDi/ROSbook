# 4.12 Тестирование вашей модели с помощью ArbotiX Simulator

В томе 1 мы использовали пакет _arbotix\_python_ для создания фальшивого базового контроллера, который позволил нам управлять имитацией TurtleBot и просматривать результаты в RViz. Пакет completearbotix включает в себя контроллер-серверы Dynamixelservos, многошарнирные руки и захваты с различной геометрией. Эти контроллеры также могут быть запущены в поддельном режиме, что позволяет нам тестировать руку \(руки\) робота или головку для наклона и поворота при наблюдении за движениями в RViz.

Пакет _rbx2\_bringup_ включает в себя ряд запускаемых файлов для запуска Box Robot или Pi Robot с использованием контроллеров _arbotix_. Мы подробно рассмотрим файлы запуска и конфигурационные файлы в следующей главе. А пока давайте просто попробуем с нашими моделями роботов.

Если вы еще не установили пакет arbotix, сделайте это сейчас с помощью следующей команды:

```text
$ sudo apt-get install ros-indigo-arbotix
```





