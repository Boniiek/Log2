При запуске приложения происхдят следующие функции: onCreate() → onStart() → onResume()

При повороте экрана Activity пересоздается, если не настроено сохранение состояния.

При сворачивании приложения происходят функции onPause() и onStop(), но не onDestroy().

Вызов finish() в onCreate() немедленно уничтожает Activity, пропуская остальные методы.
