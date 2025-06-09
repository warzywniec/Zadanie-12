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

![image](https://github.com/user-attachments/assets/a950a064-cc29-4049-a412-a0a9f1207c45)

Na porcie 6001 znajduje się strona [phpmyadmin](http://localhost:6001) w której jest przykładowa baza 'testdb' 

![image](https://github.com/user-attachments/assets/0a9df735-688e-410d-af9f-4a92eacbbe3b)
