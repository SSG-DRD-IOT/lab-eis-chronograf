# Human-Machine Interfaces with Chronograf

## Using Chronograf

Chronograf is a web application that allows you to build dashboard style widgets that correspond to data from a variety of source such as influx DB for alerts from capacitor. Chronograph as an example of a human machine interface. In industrial applications human machine interfaces or HMI are flexible software programs that allow people to control and receive analytics from industry 4.0 machinery.

With chronograph you can do the following:
* Infrastructure monitoring
* Alert management
* Data visualization
* Database management
* Multi-organizational or multi-user support

Pre-created dashboards

Chronograph has a large number of precreated dashboards to help you jumpstart your HMI.

* apache
* consul
* docker
* elasticsearch
* haproxy
* iis
* influxdb
* kubernetes
* memcached
* mesos
* mysql
* nginx
* nsq
* phpfpm
* ping
* postgresql
* rabbitmq
* redis
* riak
* system
* varnish
* win_system

## Starting Chronograf

Go to the setup directory and change the .env file and IEI_SERVICES variable to **services_all.json**

```
IEI_SERVICES=services_all.json
```

Then rebuild and restart the Intel Edge Insights Software services

```
sudo make build run
```

Now open a browser and go to **https://localhost:8888**

You will be presented with chronograf's initial interface.








