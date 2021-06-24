### XI.	Logs

Logs provide visibility into the behavior of a running app. Logs are the stream of aggregated, time-ordered events collected from the output streams of all running processes and backing services. The principle suggests separating the two processes - log generation and processing the log's information. 

A tool such as Fluentd can be one of the examples to collect the stream of logs and can feed into Elasticsearch for storage and indexing. Finally, meaningful dashboards can be rendered for visualization in Kibana.

##### Sample Gradle dependency to include logging apis in the application -
```sh
dependencies {
    //Log4j dependency 
    implementation group: 'log4j', name: 'log4j', version: '1.2.17'
}
```

