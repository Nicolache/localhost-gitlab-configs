You can lunch gitlab with docker runner with it 
Usage: 
cd local-gitlab-configs 
docker-compose up -d
docker exec -ti localhost-gitlab-configs_localhost-gitlab_1 bash 
docker-runner register 
