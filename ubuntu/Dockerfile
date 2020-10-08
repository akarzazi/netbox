FROM ubuntu:20.10

RUN apt-get update && apt-get install -y --no-install-recommends \
    curl \
	dnsutils \ 
	iperf \
	iputils-ping \
	vim \
 && rm -rf /var/lib/apt/lists/*
 
CMD ["bash"]
