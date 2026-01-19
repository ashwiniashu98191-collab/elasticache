# elasticache

## Steps to run:

sudo su

ssh -i web.pem ec2-user@13.60.72.41

yum install -y redis

redis-cli -h my-redis-cluster.f7suci.0001.eun1.cache.amazonaws.com -p 6379 ping
