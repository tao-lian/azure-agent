# azure-agent
Azure agent in arm64 docker

# how to get it
docker pull taolian/azure-agent

# how to use (easy way)
Using host docker engine by mounting the host file /var/run/docker.sock into the container

-v /var/run/docker.sock:/var/run/docker.sock

# how to use (better way)
Using "Docker in Docker" to create an isolated docker environemnt, check docker-compose for more details

# how to build an agent
https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops#linux