# simplilearn-dockercoins

```
git clone https://github.com/academiaonline/simplilearn-dockercoins 
cd simplilearn-dockercoins/
git checkout 2021-09

alias docker='sudo docker'

docker image build --file Dockerfile-hasher --tag local/simplilearn-dockercoins:test-hasher /mnt/
docker image build --file Dockerfile-rng --tag local/simplilearn-dockercoins:test-rng /mnt/
docker image build --file Dockerfile-webui --tag local/simplilearn-dockercoins:test-webui /mnt/
docker image build --file Dockerfile-worker --tag local/simplilearn-dockercoins:test-worker /mnt/ 


```
