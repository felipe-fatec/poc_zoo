# poc_zoo

## Part1
docker compose up

## Part2
zkCli -timeout 3000 -server localhost:2181

ls /

create /app01 "Meu App"

ls /

create /app01/no01 192.30.0.1

create /app01/no02 192.30.0.2

get /app1

get /app01/no01

get /app01/no02

quit

zkCli -timeout 3000 -server localhost:2182

get /app01/no01

quit

## Part3
docker compose down
