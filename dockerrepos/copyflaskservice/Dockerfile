FROM ubuntu

RUN apt-get update
RUN apt-get -y install python3
RUN apt-get install -y git
RUN apt-get -y install python3-pip
RUN mkdir sajjad
RUN git clone https://github.com/saz2nitk/ga1909.git
WORKDIR ga1909
RUN pip3 install -r requirements.txt
ENV JAVA_HOME /usr/local
COPY dummy.txt sajjad/dummy.txt
WORKDIR bin
CMD ["python3","summaryservice.py"]
