# TvTropes Indexer
Simple program prepare to index tropes data.

# ES interacting with curl
## Searching
curl -XGET localhost:9200/twitter/_search/?pretty=true
curl -XGET localhost:9200/tropes/_search/?pretty=true

## Mapping
curl -XGET localhost:9200/twitter/_mapping/?pretty=true
curl -XGET localhost:9200/tropes/_mapping/?pretty=true


