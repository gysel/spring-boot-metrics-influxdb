# Spring Boot Metrics Example

A Spring Boot application capturing metrics using [Micrometer](http://micrometer.io/) 
and sending them to an [InfluxDB](https://www.influxdata.com/products/influxdb-overview/).
Reporting is done in [Grafana](https://grafana.com/).


## Start the Example

```sh
docker-compose up -d
./gradlew bootRun
```

The example is accessible on:

* Spring Boot: http://localhost:8080/
* Grafana: http://localhost:3000
    * User: admin
    * Password: admin
* InfluxDB: http://localhost:8086 (only API, no UI)

The Influx Datasource and a simple dashboard are automatically provisioned in Grafana.