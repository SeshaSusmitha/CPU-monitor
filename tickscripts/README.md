# Trigger alert from Stream data using Tickscript

## Define Tickscript

kapacitor define cpu_alert -type stream -tick cpu_alert.tick -dbrp telegraf.autogen

## Enable Tickscript

```s
kapacitor enable cpu_alert
```

Show Kapacitor task

```s
kapacitor show cpu_alert
```

Running task on Kapacitor to bring CPU usage to above 70

```shell
while true; do i=0; done
```

For detail explanation please look at the [Kapacitor geting started
guide](https://docs.influxdata.com/kapacitor/v1.2/introduction/getting_started/)