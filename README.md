# plumberpackage

/home/ubuntu/projects/plumberpackage/inst
docker build -t dockerfile .
docker-compose up -d
# to kill 
docker-compose down


siege -t10s http://3.16.48.38/wait?n=1
siege -t10s http://3.14.247.34:8000/wait?n=1
