# docker-monitoring-sample

1. Setup `.env` file
   - `AWS_REGION` is required. AWS_CLUSTER is optional, if is empty then ecs discovering for all clusters
2. `docker-compose up`


```bash
git clone https://github.com/ColaGom/docker-monitoring-sample.git monitoring
cd monitoring
vim .env # setup environment
docker-compose up
```
