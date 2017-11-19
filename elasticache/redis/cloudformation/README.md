# Overview
The purpose of this stack is to build three Elasticache Redis nodes in a Replication Group.

# Validate CloudFormation
`aws cloudformation validate-template --template-body file://ec_redis_with_replica.json`

# Create an ECRedisReplica Stack
`aws cloudformation create-stack --stack-name ECRedisReplica --template-body file://ec_redis_with_replica.json`

# Update an ECRedisReplica Stack
`aws cloudformation update-stack --stack-name ECRedisReplica --template-body file://ec_redis_with_replica.json`

# Delete an ECRedisReplica Stack
`aws cloudformation delete-stack --stack-name ECRedisReplica`
