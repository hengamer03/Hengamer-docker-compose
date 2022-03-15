# Hengamer docker compose
## dette er min docker compose oppgave, dette er bare en test i hvordan docker compose funker, så jeg brukte en allerede eksisterende yaml fil til denne oppgaven
## denne funner du her : https://github.com/docker/awesome-compose/blob/master/nextcloud-redis-mariadb/docker-compose.yaml

### start med å laste ned docker compose som vist på denne siden : https://docs.docker.com/compose/install/
### test at docker compose funker med å skrive ```docker-compose --version```
### lag et directory, jeg kalte dette docker-compose
### deretter lager du en fil som heter docker-compose.yaml og så kopoerte jeg inholdet fra denne linken : https://github.com/docker/awesome-compose/blob/master/nextcloud-redis-mariadb/docker-compose.yaml over til yaml filen.
### så skrev jeg ```docker-compose up``` og da vill du se at containerne begynner å starte, så kan du sjekke på http://0.0.0.0 om nextcloud kommer opp, da har dette funket. 
### jeg tok ikke å satt op mariadb eller redis fordi oppgaven handlet bare om å sette opp docker compose
