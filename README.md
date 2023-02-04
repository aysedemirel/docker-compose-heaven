# docker-compose-heaven
Docker-compose.yml for tools

## POSTGRES, PGADMIN
`docker pull postgres`
`docker pull docker pull dpage/pgadmin4`
`docker-compose -f docker-compose_postgre.yml up -d`

## KAFKA
`docker pull confluentinc/cp-zookeeper`
`docker pull confluentinc/cp-kafka`
`docker pull confluentinc/cp-kafka-rest`
`docker pull obsidiandynamics/kafdrop`
`docker-compose -f docker-compose_kafka.yml up -d`