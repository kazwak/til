# Log Collectors
It's necessary to use log collectors on purpose
### purpose
- simple  
logstash : logstash is good compatibility with elastic search(and kibana)
- realtime  
fluentd : fluentd can collect many server logs on realtime. but high performance PC required.   
I tried using fluentd : [efk_for_nginx](https://github.com/kazwak/efk_for_nginx)
- Large amounts of log data processing
embulk : something like a batch version of fluentd. it's uses when want to send large file to elasticsearch.