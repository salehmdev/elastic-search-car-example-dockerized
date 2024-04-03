# Elastic Search Example

## Getting Started

Startup Elasticsearch + Kibana + ElasticHQ:

```terminal
docker compose -f .\docker-compose.yml up -d
```

Shut down:

```terminal
docker compose -f .\docker-compose.yml down -v
```

Local Kibana URL: <http://localhost:5601>

- Username: elastic
- Password: elastic

## Elastic HQ

Local ElasticHQ URL: <http://localhost:5000>

Cluster URL: <https://es01:9200>

If UNAUTHORIZED, use basic Auth: <https://elastic:elastic@es01:9200>

## Fill Sample Car Data

- Option 1: Use the Kibana data import tool (FASTER, if possible)

  - From the home page, there should be an option to upload data, or use their starter sample data. The e-commence example is a nice option.

- Option 2: Run the `loader.py` script found in `scripts/` folder.
  - NOTE: Set up python env and install dependencies first
