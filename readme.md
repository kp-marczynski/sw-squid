# Readme 
## Test execution
   
### Lab 1
    
    docker-compose up --build -d
    docker exec -it client bash
    curl -x z<task_nr>_p<machine_nr>:3128 http://www.deepsloweasy.com/

### Lab 2

    docker-compose up --build -d
And then change system proxy settings to use localhost:3128    
