# plumberpackage

/home/ubuntu/projects/plumberpackage/inst
docker build -t dockerfile .
docker-compose up -d
# to kill 
docker-compose down


siege -t10s http://3.16.48.38/wait
siege -t10s http://3.16.48.38:8003/wait
