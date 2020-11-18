# Дневник погоды

Приложение, позволяющее делать записи наблюдений о погоде с загрузкой фотографии
 (png или jpg формат) и показывающее некоторую статистику по температуре.
 
# Установка

Для установки необходимо скчать данный репозиторий, а затем из него выполнить 
``docker-compose up`` (необходимо, чтобы были установлены [Docker](https://www.docker.com/get-started) и [Docker Compose](https://docs.docker.com/compose/install/)).
После чего запустится сервер и можно будет начать работу с приложением по адресу [http://localhost:5000/](http://localhost:5000/). 

# Примечание 
Все поля для заполнения являются необязательными (можно вообще ничего не заполнить и отправить пустую 
форму, но она сохранится в истории). На отправку фотографий стоит ограничение в 100 Мб. Если отправляется файл 
не подходящего расширения, то он не будет сохранен.