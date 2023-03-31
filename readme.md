- docker -itd (-d: chạy ngầm, -i: trả về khi gõ command (stdin), -t: hiện cửa sổ dòng lệnh (terminal))
- docker ps/docker container ls (-a): list running contaienr/list all container
- docker create/docker container create: tạo mới container
- docker run/docker container run: chạy container 
- docker rm/docker container rm: xóa (-f: xóa container chưa stop)
- docker prune/ docker container prune: xóa tất container đang stop
- docker start/docker container start: start container (tương tự: stop/restart/pause/unpause/kill=stop)
- docker logs/docker container logs: hiển thị log của container
- docker inspect/docker container inspect: hiển thị thông tin chi tiết container
- docker stats/ docker container stats: hiển thị tài nguyên container
- docker top/docker container top: hiển thị tiến trình container
- docker port/docker container port: hiển thị port được map
- docker diff/docker container diff: hiển thị thay đổi về filesystem
- docker attach/docker container attach: attach 1 màsn hình cho phép nhập input/hiển thị output
- docker exec/docker container exec: thực thi 1 câu lệnh trong container đang chạy
- docker update "" container "": update resource cho container, mở rộng tài nguyên
- docker cp/docker container cp: copy file giữa host và container
- docker rename/docker container rename: đổi tên
- docker export/docker container export: export toàn bộ filesystem in container
- docker commit: tạo image từ running container

- docker images/docker image ls: list images
- docker image pull: download image (default: dockerhub)
- docker image push: push image
- docker inspect/docker image inspect: hiển thị chi tiết image
- docker image history: hiển thị lịch sử image 
- docker image tag: tạo 1 image tag mới
- docker image save/docker iamge load: save image > file tar (load từ file tar)
- docker image rm: xóa image



# Docker - Essential Commands
- The below are the list of essential commands we are in need 

|     Commands                 |    Description                                  |
| ------------------------------- | --------------------------------------------- |
| docker ps | List all running containers |
| docker ps -a | List all containers stopped, running |
| docker stop container-id | Stop the container which is running |
| docker start container-id | Start the container which is stopped |
| docker restart container-id | Restart the container which is running |
| docker port container-id | List port mappings of a specific container |
| docker rm container-id or name | Remove the stopped container |
| docker rm -f container-id or name| Remove the running container forcefully |
| docker pull image-info | Pull the image from docker hub repository |
| docker pull stacksimplify/springboot-helloworld-rest-api:2.0.0-RELEASE | Pull the image from docker hub repository |
| docker exec -it container-name /bin/sh | Connect to linux container and execute commands in container |
| docker rmi image-id | Remove the docker image |
| docker logout | Logout from docker hub |
| docker login -u username -p password | Login to docker hub |
| docker stats | Display a live stream of container(s) resource usage statistics |
| docker top container-id or name | Display the running processes of a container |
| docker version | Show the Docker version information |
