FROM golang:1.16

WORKDIR /go/src
ENV PATH="/go/bin:${PATH}"

RUN apt-get update && \
    apt-get install build-essential librdkafka-dev -y

# Para manter o processo ativo
CMD [ "tail", "-f", "/dev/null" ] 
