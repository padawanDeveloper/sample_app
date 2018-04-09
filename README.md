Empezando
====

1 Para comenzar con la aplicación, clone el repositorio y luego instale las gemas necesarias:
  * bundle install --without production

2 Luego, migre la base de datos:
  * rails db:migrate

3 Finalmente, ejecute el conjunto de pruebas para verificar que todo esté funcionando correctamente:
  * rails test

4 Si pasa el banco de pruebas, estará listo para ejecutar la aplicación en un servidor local:
  * rails server