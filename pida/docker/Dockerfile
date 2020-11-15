FROM python:2
ADD blackbox_decode /
ADD pid-analyzer.py /
ADD requirements.txt /
ADD testlog.bbl /
ADD run /
RUN apt-get -y update
RUN apt-get -y install xvfb
RUN pip install -r requirements.txt
ENTRYPOINT ["/run"]
