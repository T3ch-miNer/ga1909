FROM ubuntu

RUN apt-get update
RUN apt-get -y install python3
RUN apt-get install -y git
RUN apt-get -y install python3-pip
RUN mkdir sajjad
RUN cd sajjad
RUN git clone https://github.com/saz2nitk/ga1909.git
RUN cd ga1909
RUN pip3 install -r ga1909/requirements.txt
RUN cd bin

CMD ["python3","ga1909/bin/summaryservice.py"]
