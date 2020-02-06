## Setup
- Before running the `mongodb-replicaset.yml` file, add this to your system **hosts** file **127.0.0.1 mongodb_replicaset_primary mongodb_replicaset_secondary mongodb_replicaset_arbiter**

## NoSQL Client
- Run command **`docker-compose -f mongodb-replicaset-client.yml up`**
- Open browser and go to **localhost:5001**
