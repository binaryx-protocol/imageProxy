sudo docker compose stop
sudo rm -rf cache/
sudo docker compose up -d --build --remove-orphans --force-recreate

