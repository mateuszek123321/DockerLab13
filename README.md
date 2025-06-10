# Labolatrium 13
Stworzenie secretes dla stacka LEMP z labolatorium 12 

### Polecenie 1
uruchomienie pliku compose:
Sprawdzenie statusu kontenerów -> docker compose ps 
docker compose up -d
![alt text](image-3.png)


### Polecenie 2
Sprawdzenie montowania sekretów:
docker exec mysql ls -la /run/secrets/
![alt text](image-4.png)

### Polecenie 3
Sprawdzenie zawartości sekretów w kontenerze:
docker exec mysql cat /run/secrets/mysql_root_password
![alt text](image-2.png)

### Polecenie 4
Sprawdzenie działa strony:
![alt text](image-5.png)
![alt text](image-6.png)


### Polecenie 
Zatrzymanie lempa:
docker compose down 