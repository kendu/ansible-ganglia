# Ganglia role ansible

## Ganglia
Ganglia is responsible for collection metrics from other servers

### Mandatory variables
* graphite_data_source_name - Name of the graphite data source(string) - pick one :)
* graphite_host - host to which the data is shipped
* graphite_collector_port - Destination port
