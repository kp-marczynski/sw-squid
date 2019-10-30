##Wykonanie testów
    docker-compose up --build -d
    docker exec -it client bash
    curl -x z<nr_zadania>_x<nr_maszyny>:3128 http://www.deepsloweasy.com/
