# twitter-elk

This repo contains the configuration files of logstash used to monitor some keywords on Twitter and saving all tweets on ElasticSearch.

## Requirements
* ElasticSearch <a href="https://www.elastic.co/products/elasticsearch" target="_blank">+Info</a>
* Logstash <a href="https://www.elastic.co/products/logstash" target="_blank">+Info</a>
* Kibana <a href="https://www.elastic.co/products/kibana" target="_blank">+Info</a>
* Twitter - Apps <a href="https://apps.twitter.com" target="_blank">+Info</a>

## How to run

> ../kibana-5.0.1-linux-x86_64/bin$ ./logstash -f ~/twitter_run.config

## Explanation
Go to the following post => 
[Entrada de blog](https://vcatalan.com/2017/12/pila-elk-parte-ii-monitorizando-twitter-con-elk.html)