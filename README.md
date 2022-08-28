Start the prometheus container : 

docker run -d -p 9090:9090 -v <absolutepathtoyourprometheusfile>:/etc/prometheus/prometheus.yml prom/prometheus

Start the grafana container: 

docker run -d -p 3000:3000 grafana/grafana
