FROM ubuntu:16.04

RUN apt-get update && apt-get install -y \
    kafkacat

ENTRYPOINT ["kafkacat"]
CMD ["-b", "kafka-service", "-L"]
