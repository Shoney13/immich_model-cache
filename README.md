clone the current repo

# note immich-machine-learning id
docker ps
docker cp clip MACHINE_ID:/cache/
docker cp facial-recognition MACHINE_ID:/cache/
docker cp ocr MACHINE_ID:/cache/
docker exec -u 0 MACHINE_ID chmod -R 777 /cache