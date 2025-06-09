# Zadanie 12

### Plik główny:

docker-compose.yaml

### Polecenia

polecenie stratujące:

```CMD
docker compose up --build
```

polecenie kończące:

```CMD
docker compose down -v
```

flaga '-v' została dodana w celu usunięcia tworzonego wolumenu 'mysql_data'

### Działanie

Na porcie 4001 znajduje się strona startowa [index.php](http://localhost:4001) wywołująca funkcję ``` phpinfo()```



Na porcie 6001 znajduje się strona [phpmyadmin](http://localhost:6001) w której jest przykładowa baza 'testdb' 

