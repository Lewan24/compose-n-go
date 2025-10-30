# 🐳 Compose Starter Kit

Prosty szablon `docker-compose.yml` do szybkiego uruchomienia podstawowego środowiska developerskiego:
- **Portainer** – zarządzanie kontenerami przez UI  
- **MySQL** – baza danych  
- **phpMyAdmin** – interfejs webowy do MySQL  

Idealny do szybkiego startu po formacie lub do testowania projektów lokalnie.

---

## 🚀 Szybki start

### 0. One liner
```bash
git clone https://github.com/Lewan24/compose-n-go.git && cd compose-n-go && docker compose up -d
```
Lub poniżej krok po kroku

### 1. Sklonuj repozytorium
```bash
git clone https://github.com/Lewan24/compose-n-go.git
cd compose-n-go
```

Lub skopiuj/pobierz sobie plik docker-compose.yml

### 2. Uruchom środowisko
```bash
docker-compose up -d
```

### 3. Dostęp do usług
| Usługa     | URL                                            | Login                                 | Hasło    |
| :--------- | :--------------------------------------------- | :------------------------------------ | :------- |
| Portainer  | [https://localhost:9443](https://localhost:9443) | admin                                 | -        |
| phpMyAdmin | [http://localhost:8080](http://localhost:8080) | root                                  | toor     |
| MySQL      | localhost:3306                                 | root                                  | toor     |
