# Elasticsearch Example

## Useful Commands

Startup Elasticsearch + Kibana + ElasticHQ

`docker compose -f .\docker-compose.yml up -d`

Shut down

`docker compose -f .\docker-compose.yml down -v`

## Elastic HQ

Cluster URL: <https://es01:9200>

If UNAUTHORIZED, use basic Auth: <https://elastic:elastic@es01:9200>

## Fill Sample Car Data

- Option 1: Use the Kibana data import tool (FASTER, if possible)
- Option 2: Run the `loader.py` script found in `scripts/` folder.
  - NOTE: Set up python env and install dependencies first
