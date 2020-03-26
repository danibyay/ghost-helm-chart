# My own Ghost chart

This is a helm chart, it is in no way better than the official ghost chart. 

It was just a practice project to create my own chart.

## Requirements

* To have a Kubernetes cluster running
* To have helm installed
* To have kubectl installed in your local machine

## How to create a release

> helm install ghost-example-chart ./myghostchart

In this command, ghost-example-chart is the name of the release, 
and myghostchart is the directory where the chart is. Relative to your cwd.

The service is a Load Balancer, so you can navigate to 
the IP of the load balancer to see the ghost site.
