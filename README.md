# riot
# install
docker-compose run --rm -e SYNAPSE_SERVER_NAME=example.com -e SYNAPSE_REPORT_STATS=yes synapse generate
docker-compose up -d
