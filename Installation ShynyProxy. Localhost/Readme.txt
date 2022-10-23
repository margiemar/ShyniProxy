Для работы ShinyProxy  необходимы:
 - OpenJDK Zulu - ShinyProxy - написан на Java.
 - Docker - для запуска приложений.
 
Docker должен прослушивать порт 2375.

Спецификация ShinyProxy описана в файле application.yml.
Приложения скомпонованы в Dockerfile  и описаны в application.yml в разделе spec.
Контейнеры запускаются по клику в окне браузера на странице ShinyProxy (http://IP:8080/)
по соответствующей ссылке.
