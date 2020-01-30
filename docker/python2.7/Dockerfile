FROM python:2.7

ADD . /awscli

RUN pip install -e awscli/ && pip install awsprocesscreds

WORKDIR /project

ENTRYPOINT ["aws"]