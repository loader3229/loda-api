# LODA API Server and Monitoring

This project consists of the following parts:

* LODA API server implementations written in Go.
* Monitoring of LODA miners using InfluxDB and Grafana.
* Docker image for running everything in one container.

There are separate API servers for:

* OEIS cache
* Program submissions
* Stats

## Recommended Hardware Setup

We recommend running this on a micro-instance with 1 GB memory, 1 shared CPU,
30 GB of standard persistent disk with Container-optimized OS.
