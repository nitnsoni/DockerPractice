docker pull postgres
or
docker pull postgres:14.2

docker run --name local-psql -v local_psql_data:/var/lib/postgresql/data -p 54320:5432 -e POSTGRES_PASSWORD=123 -d postgres
