# kopk

ELK stack alternative for the brave and true.

KOPK stands for Kakfa, ObjectStore(like S3), PrestoDB, Kibana stack that intended to replace ELK stack for logging.

## Motivation

The biggest motivation is that ElasticSearch is not my favorite piece of software of all times while Kafka and PrestoDB are pretty solid foundation for any data pipeline. 


## Features

Store, query and visualize logging information

We live in a world where hosts are coming up and going down all time as part of dynamic workloads, many applications are containerized and not allowed to write logging information to local disk. These circumstances lead to the question how to do logging properly? I think using an external service is the answer but found out that building on clud services provided by cloud vendors is sometimes a bit limited experience. AWS has CloudWatch logging but I found it limited to our use cases. We are going to investigate if we can provide a better alternative using FOSS components.

