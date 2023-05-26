# Redis_learn

- Create an instance of Redis cloud
- rbook.cloud
- SET key value
- set mess 'hi there' -> send mess to redis server
- String (set,get,append)
- Redis orginal caching server so it has some expire options
- API server makes request to cache server first then to traditional DB
- automatic expiring time
- SETEX same as SET + EX
- MSET color red brand toyota -> {color:"red", brand:"toyota}
- GETRANGE model 0 2 -> model[0:2]
- redis - synchrononous

Serialize: take info, encode and store them
Deserialize: take info, decode
