# prometheus-pushgateway-pushdata

- how to run
  $ cat <<EOF | curl --data-binary @- http://localhost:9091/metrics/job/brandon-test/instance/192.168.1.16
    api_calls 2
    EOF
 $ cat <<EOF | curl --data-binary @- http://localhost:9091/metrics/job/brandon-test/instance/192.168.1.16
    api_calls 12
    EOF

- reference
  1. [Scrape data using Bash script and push it to Prometheus using PushGateway](https://medium.com/avmconsulting-blog/pushing-bash-script-result-to-prometheus-using-pushgateway-a0760cd261e)
