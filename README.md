# logstash-delete-index

This is a simple script to delete Logstash indices from Elasticsearch.

As example if you want to delete all indices that are older than 180 days:

    # Just for debugging
    logstash-delete-index -H 192.169.100.10:9200 -D 180

    # Delete the indices
    logstash-delete-index -H 192.169.100.10:9200 -D 180 -R

