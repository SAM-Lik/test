FROM ubuntu:20.04

RUN apt-get update && \
   apt-get install -y python3 && \
   rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY script.py .

VOLUME ["/data_example"]

ENTRYPOINT ["python3", "script.py"]

CMD ["--help"]
