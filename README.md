# sfer
Запуск:
1. Через командную строку
  -  mkdir build        (создаем папку build)
  -  cd build           (переходим в нее)
  -  cmake ..           (собираем зависимости)
  -  make               (собираем проект)
  -  ./tinyraytracer    (запускаем приложение)

2. Через IDE (Clion например)
  - open project
  - подгрузить cmake в проект
  - запускаем
  
Результат: на выходе в папке build изображение out.ppm с отрисованной сценой.
