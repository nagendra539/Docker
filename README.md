# Docker
This is sample python script which will print the key value pair in the browser by using uvicorn and FastApi packages.

Commands to build the container images:
docker build -t json-api
docker run -p 8000:8000 --name mycontainer json-api 
Please open the browser and run 127.0.0.1:8000  --> you will see the key-value pair which were used in main.py script.
use "&" to run the process in background.
for log into the docker container use below commands
docker exec -it <container-id> /bin/bash.
For listing the container ids use below command
docker ps
