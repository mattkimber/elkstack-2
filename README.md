# ELK Stack with Docker Compose - Part 2

This is a simple example of using Docker Compose to set up the ELK stack with an nginx reverse proxy, some custom configuration for ElasticSearch, and a persistent data volume.

Contents:

* docker-compose.yml file to set up the three components
* Example logstash.conf file
* Example log which works with the grok filter in the supplied logstash.conf
* nginx configuration files for the reverse proxy

For more information, see http://mattkimber.co.uk/elk-stack-in-25-minutes-with-docker/
