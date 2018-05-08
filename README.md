# Metrics script
   This script allows you to print basic server metrics about your CPU and memory.

   Allowed commands:
   ```$xslt
   cpu
   mem
```

##Script usage examples

#### print CPU metrics

Execute script with **cpu** argument: `./metrics.sh cpu`

#### print memory metrics

Execute script with **mem** argument:  `./metrics.sh mem`

##Docker usage

Run docker with container with command specified in allowed command list
#####Example

```
docker run -t --rm artem7mag/testtask:latest cpu

user		17.25 
nice		0.00 
system		1.95 
iowait		0.21 
steal		0.00 
idle		80.60

```