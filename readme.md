# Environment Node JS dockerized
`docker-compose build` <br />
`docker-compose up -d` <br />

Api listens on port 3001. (Change it in docker-compose.yml and api/docker/Dockerfile). <br />
MySQL: `mysql -h 127.0.0.1 --port=3307 -u root -ppassword`

## Docker containers
API container:   `projectx_api_1` <br />
MySQL container: `projectx_mysqldb_1` <br />