# Logstash with docker


### Launching

    docker-compose up

The kibana are available on the exposed port `5601`.


### Test

    nc -w0 -u localhost 5000 <<< "Test logtrail"
