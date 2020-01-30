FROM python:2.7-slim

ADD . /awscli

RUN pip install -e awscli/ && pip install awsprocesscreds

WORKDIR /project

ENTRYPOINT ["aws"]