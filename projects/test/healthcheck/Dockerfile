FROM prefecthq/prefect:2.4.1-python3.10
RUN apt update
RUN apt upgrade -y

ADD flow.py /opt/prefect/flows
ADD requirements.txt .

RUN pip install -r requirements.txt