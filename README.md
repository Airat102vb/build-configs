# build-configs

На новом окружении, перед запуском `docker compose up -d`, может потребоваться настройка сети 
`docker network create --driver=bridge --subnet=172.10.0.0/16 --gateway=172.10.0.1 mycustomnetwork`
