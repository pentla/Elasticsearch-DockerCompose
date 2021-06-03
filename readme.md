```bash

docker-compose up -d

# embulk
dcc exec embulk /bin/ash
```

## embulk

embulk guess ./embulk/seed.yml -o config.yml
embulk run config.yml -c diff.yml

## kibana

localhost:6501

## elasticSearch

localhost:9200
