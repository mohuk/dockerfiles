FROM java:openjdk-8

RUN wget -P /tmp/ "https://archive.apache.org/dist/jmeter/binaries/apache-jmeter-3.2.tgz"
RUN tar -xzf /tmp/apache-jmeter-3.2.tgz

ENV PATH "$PATH:/apache-jmeter-3.2/bin"

ENTRYPOINT ["jmeter"]
